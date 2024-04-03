<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Pendidikan</template>

    
    <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
  Saat ini saya menjalani kuliah di salah satu kampus Riau yaitu Universitas Islam Riau.sebelumnya saya bersekolah di Perguruan Wahidin.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tempat, tanggal Lahir</template>

    Saya lahir di provinsi Rokan Hilir yaitu kota Bagansiapi-api. pada tanggal 04 September 2004.
    <a href="https://vitejs.dev/guide/features.html" target="_blank" rel="noopener"></a>
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener"></a> 
    <a href="https://github.com/johnsoncodehk/volar" target="_blank" rel="noopener"></a>
    <a href="https://www.cypress.io/" target="_blank" rel="noopener"></a> 
    <a href="https://on.cypress.io/component" target="_blank" rel="noopener"
      ></a
    >

    <br />

     <code></code>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Jurusan</template>

    jurusan yang saya ambil adalah program didik teknik informatika atau disebut IT, sekarang saya berada di semester 4.
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener"></a> 
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener"></a> 
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener"></a>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Hobi</template>

    <h3>Hobi Saya hanya bermain game pc kompetitif seperti :</h3>
<ol>
  <ul>
    <li><a href="https://playvalorant.com/" target="_blank" rel="noopener">Valorant</a></li>
    <li><a href="https://www.callofduty.com/playnow/warzone" target="_blank" rel="noopener">COD Warzone</a></li>
    <li><a href="https://en.bandainamcoent.eu/tekken/tekken-8" target="_blank" rel="noopener">Tekken 8</a></li>
    <li><a href="https://pubg.com/en-na/events/7th_anniversary" target="_blank" rel="noopener">PUBG</a></li>
  </ul>
</ol>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Sosial Media</template>
    saya lebih sering aktif di discord dan ig 
    <li><a href="https://www.instagram.com/m.ffarhannn/" target="_blank" rel="noopener">instagram</a></li>
  
  </WelcomeItem>
</template>
