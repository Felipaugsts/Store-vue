<template>
<div> 
<v-layout wrap  class=" justify-center mt-12"> 
<v-flex md4 sm5 xs10  class="  justify-center "> 

<v-img id="img"  src="@/assets/appletv.png" height="280px" max-width="600px" />
</v-flex>
<v-flex md4 sm6 xs7 class=" pt-10 text-center"> 
<div id="txt" >
<h1> Apple TV 4K</h1>
</div>

<v-flex class=" pl-5 pr-5 d-flex flex-column  justify-center align-center  mt-10" > 

<v-icon color="blue"> mdi-apple</v-icon> 
<div id="skill"  class="mt-2 mb-5  "> 

<div class="text-left mt-10 "> 

<h3 class="font-weight-light">Interface de conexão: HDMI.</h3>
<h3 class="font-weight-light">Sistema operacional tvOS 11.</h3>
<h3 class="font-weight-light"> 4K UHD.</h3>
<h3 class="font-weight-light">Com conectividade Wi-Fi e bluetooth para navegar na Internet em alta velocidade e sincronizar este dispositivo com a mídia.</h3>
<h3 class="font-weight-light">Novo controle de voz! Apenas falando, o dispositivo responderá aos seus pedidos. </h3>
<h3 class="font-weight-light">Acesse a diferentes plataformas de entretenimento.</h3>
</div>

</div>

</v-flex>
</v-flex>
<v-flex xs5 sm6 md5 class=" mb-10   d-flex flex-column justify-end align-center align-sm-end" >
<h3 > Preco: R$ 1780,00</h3>
<v-btn class="mt-12 primary pl-5 pr-5 font-weight-light">Comprar</v-btn>
</v-flex>

<v-flex xs12 md12 sm12 lg12 class="pa-12 grey lighten-4">
<p id="text" class="font-weight-light">
Desfrute todos os benefícios deste media player da Apple, que lhe permitirá acessar a filmes, séries, fotos e sites favoritos sem limites! Os fãs da maçã encontrarão o complemento perfeito para seus dispositivos de marca. Por sua vez, a Siri poderá responder a todas as suas perguntas e lhe facilitará a localização do conteúdo desejado.<br/>

Qualidade de imagem<br/>
Graças à sua compatibilidade com a transmissão em 4K, este player será sua melhor escolha se você procura desfrutar de tudo o que gosta com uma resolução significativamente superior ao HD e ao Full HD.<br/>

Uma nova forma de entretenimento<br/>
Você terá acesso a aplicativos que lhe permitirão ver o melhor do cinema e estar ao dia com seus programas favoritos. Acesse as plataformas de música que você querias e escutá os lançamentos de seus artistas preferidos. <br/>Você descobrirá todas as notícias e viverá o esporte como nunca antes. Por outro lado, seu controle de voz complementará sua experiência e facilitará seu manejo.</p>
</v-flex>
 
</v-layout>
</div>
</template>>
<script> 
import gsap from 'gsap';

export default { 
mounted() {
   gsap.from('#img',{ opacity: 0, bottom: -30, duration: 1.5 } );
   gsap.from('#txt',{ opacity: 0, bottom: -50, duration: 1.5 } );
  }
} 
</script>>