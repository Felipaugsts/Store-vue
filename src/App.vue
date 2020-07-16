<template>
  <v-app>
    <v-app-bar
      app
      color="grey darken-3"
      dark
      id="nav"
    >
   <router-link class="pr-10    font-weight-light" to="/">Home</router-link> 
      <router-link class="pr-10    font-weight-light" to="#">Produtos</router-link> 

      
    </v-app-bar>

    <v-content>
    <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>


export default {
  name: 'App',


  data: () => ({
    //
  }),
};
</script>
<style> 

#nav {
 padding-left: 30px;

}

#nav a {

  text-decoration: none;
    color: white;
 

}

#nav a.router-link-exact-active {
  color: #42A5F5;
   font-size: 19px;

}
  </style>
