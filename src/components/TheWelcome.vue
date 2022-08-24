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
    <template #heading>Personal profil</template>
   I'm a software engineering student. I beginner web developer with basic web skills. Always want to learn and improve
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>EXPERIENCE</template>
    UI Desainer <br>
SMK TARUNA BHAKTI <br>
01/2022 - 05/2022 <br>
Use laravel 9 <br>
Use
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Experiance</template>
 <ul>
  <li>Desain food delivery</li>
  <li>Teacher Agenda</li>
  <li>Desain Kasir</li>
 </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Language</template>
  <ul>
    <li>Indonesia</li>
    <li>Inggris</li>
  </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Vue</template>
    <ul>
      <li>(+62)0881-1128-1678</li>
      <li>ahmadhilmy98@gmail.com</li>
      <li>github</li>
    </ul>
  </WelcomeItem>
</template>
