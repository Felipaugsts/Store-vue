<template>
    <div > 
    
<v-layout row wrap class="pa-5"  justify-center=""> 
<v-flex  md5 sm6  class=" white pa-1"    v-for="item in items" :key="item.name"> 



    <v-card  class=" mx-auto grey lighten-5" outlined >
      <v-list-item three-line class="text-center mt-12" >
         <v-list-item-content>
          <div id="text">
            <p  id="text" class="mb-4 mt-5 font-weight-bold" >{{item.name}}</p>
               </div>
              <v-list-item-title  class="grey--text"> <div id="ano">{{item.ano}} </div> <br> 
        
        <div id="btn" >
        <v-btn  :to="item.path" text outlined="2px" class="mt-5 mb-2 text-capitalize">Saiba mais</v-btn>
        </div>
        </v-list-item-title>
          

        <v-list-item-subtitle> <v-img  height="345px" min-height="auto"  min-width="auto"  :src="item.image"/></v-list-item-subtitle>                           
      </v-list-item-content>

    
    </v-list-item>


  </v-card>

</v-flex>
</v-layout>
    </div>  
</template>
<script>
import gsap from 'gsap'
import scrollStrigger from 'gsap/ScrollTrigger'
  gsap.registerPlugin(scrollStrigger);
export default {
    data() {
        return { 
            items: [ 
                { name: "Google mini", ano: "2019", path: "/google" , image: require ("../assets/google.png")},
                { name: "Apple TV ", ano: "2019",path: "/apple", image: require("../assets/appletv.png")},
                { name: "Chromebook Plus Samsung", path: "/chromebook" , ano: "2017", image: require("../assets/chromebook.png")},
               { name: "Apple Life Printer Video", path: "/printer", ano: "2018", image: require("../assets/printer.png")}
                    ]
        }
    },
  mounted() {
   gsap.fromTo('#btn',{opacity:0, y: 50 }, {opacity: 1 , y: 0 ,delay:0.2, duration: 1 });
    gsap.fromTo('#ano',{opacity:0, y: 50 }, {opacity: 1 , delay: 0.6, y: 0 , duration: 1 });
     gsap.fromTo('#text',{opacity:0, y: 18 }, {opacity: 1 , delay: 1, y: 0 , duration: 1 });
  }
}
</script>
<style> 
#card {
    background-color: white;
    height: auto;
    width: 40%;
}

 { 
    font-size: 30px;
    color: #616161
    
}
</style>