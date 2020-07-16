<template>
<div> 
<v-layout wrap  class=" justify-center mt-12"> 
<v-flex md4 sm5 xs10  class="  justify-center "> 

<v-img id="img"  src="@/assets/google.png" height="250px" max-width="600px" />
</v-flex>
<v-flex md4 sm6 xs7 class=" pt-10 text-center"> 
<div id="txt" >
<h1> Google Home Mini</h1>
</div>

<v-flex class=" pl-5 pr-5 d-flex flex-column  justify-center align-center  mt-10" > 

<v-icon color="blue"> mdi-google</v-icon> 
<div id="skill"  class="mt-2 mb-5  "> 

<div class="text-left mt-10 "> 

<h3 class="font-weight-light">Linguas : Todas</h3>
<h3 class="font-weight-light">Conexão Wi-Fi : sim </h3>
<h3 class="font-weight-light">Altura : 42 mm </h3>
<h3 class="font-weight-light">Funções Assistente virtual</h3>
<h3 class="font-weight-light">Bluetooth Sim </h3>
<h3 class="font-weight-light">Peso 173 g</h3>
</div>

</div>

</v-flex>
</v-flex>
<v-flex xs5 sm6 md5 class=" mb-10   d-flex flex-column justify-end align-center align-sm-end" >
<h3 > Preco: R$ 150,00</h3>
<v-btn class="mt-12 primary pl-5 pr-5 font-weight-light">Comprar</v-btn>
</v-flex>

<v-flex xs12 md12 sm12 lg12 class="pa-12 grey lighten-4">
<p id="text" class="font-weight-light">
Com conectividade Wi-Fi integrada, reconhecimento de voz e suporte de automação residencial.<br/> O Home Mini se conectará à sua rede sem fio para fornecer controle e acesso a praticamente todos os seus dispositivos inteligentes. 
<br/>Pode tocar música, verificar o tempo e o trânsito, contar a pontuação do esporte, controlar seu equipamento residencial inteligente compatível e muito mais. Usando a tecnologia de reconhecimento de voz de campo distante e o Assistente do Google, o microfone integrado permite que o Google Home Mini reconheça sua voz e execute a tarefa solicitada em um instante. Pode distinguir até seis vozes diferentes para fornecer controle para toda a família. Você pode transmitir música para o Home Mini a partir do seu dispositivo inteligente compatível via Wi-Fi.

Especificações:
Suporte Virtual Assistant: Assistente Virtual do Google
Compatibilidade com : <br/>
- Android 4.1 ou posterior<br/>
- iOS 8.0 ou posterior<br/>
Formatos de áudio suportados: FLAC, HE-AAC, LC-AAC +, MP3, Vorbis, WAV (LPCM)<br/>
Auto-falantes drivers: 1 x 1,58 "/ 40 mm<br/>
Serviços suportados (lista parcial): Spotify, Pandora, Google Play Music, Youtube, Netflix, Fotos do Google, Calendário do Google.<br/>
Microfone mudo: Sim<br/>
USB 1 x micro-USB<br/>
Padrões Wi-Fi Wi-Fi 5 (802.11ac)<br/>
Bandas de Wi-Fi: 2,4 GHz / 5 GHz<br/>
Potência de entrada CC: 5 VDC a 1,8 A<br/>
Material: Tecido, Plástico e Silicone<br/>
Dimensões (L x A x D): 1,6 x 3,9 x 3,9 "/ 42,0 x 98,0 x 98,0 mm<br/>
Peso: 6,1 oz / 173 g<br/>

Conteúdo da embalagem:
01 Mini home
01 Cabo de alimentação (PADRÃO AMERICANO)
Não possui manual.</p>
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