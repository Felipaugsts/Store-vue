<template>
<div> 
<v-layout wrap  class=" justify-center mt-12"> 
<v-flex md4 sm5 xs10  class="  justify-center "> 

<v-img id="img"  src="@/assets/chromebook.png" height="280px" max-width="600px" />
</v-flex>
<v-flex md4 sm6 xs7 class=" pt-10 text-center"> 
<div id="txt" >
<h1> Samsung ChromeBook PLUS</h1>
</div>

<v-flex class=" pl-5 pr-5 d-flex flex-column  justify-center align-center  mt-10" > 

<v-icon color="blue"> mdi-laptop</v-icon> 
<div id="skill"  class="mt-2 mb-5  "> 

<div class="text-left mt-10 "> 

<h3 class="font-weight-light"> Intel Celeron 3965Y</h3>
<h3 class="font-weight-light"> Velocidade: 1.50 GHz</h3>
<h3 class="font-weight-light"> Cache: 2 MB L3</h3>
<h3 class="font-weight-light"> Capacidade: 4 GB</h3>
<h3 class="font-weight-light">Velocidade: 1866 MHz</h3>
<h3 class="font-weight-light">Tamanho: 12.2"</h3>
</div>

</div>

</v-flex>
</v-flex>
<v-flex xs5 sm6 md5 class=" mb-10   d-flex flex-column justify-end align-center align-sm-end" >
<h3 > Preco: R$ 2450,00</h3>
<v-btn class="mt-12 primary pl-5 pr-5 font-weight-light">Comprar</v-btn>
</v-flex>

<v-flex xs12 md12 sm12 lg12 class="pa-12 grey lighten-4">
<p id="text" class="font-weight-light">
Com vários recursos, o Samsung Chromebook Plus (V2) ajuda a aumentar a produtividade e a criatividade. Criar e editar conteúdos é muito fácil. Escreva e fotografe momentos importantes para compartilhá-los com incrível facilidade. Aproveite para criar conteúdos melhores todos os dias de acordo com o que você desejar.
</p>
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