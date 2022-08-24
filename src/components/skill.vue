<script setup> 
import WelcomeItem from './WelcomeItem.vue' 
import html from './icons/html.vue' 
import css from './icons/css.vue' 
import figma from './icons/figma.vue' 
import bootstrap from './icons/boostrap.vue' 
import SupportIcon from './icons/IconSupport.vue' 
import Html from './icons/html.vue' 
// import Figma from './icons/figma.vue' 
// import Figma from './icons/figma.vue' 
// import Figma from './icons/figma.vue' 
</script> 
 
<template> 
  <WelcomeItem> 
    <template #icon> 
      <Html /> 
    </template> 
    <div class="div"> 
      <div class="flex"> 
        <h3>HTML</h3> 
        <h3>80%</h3> 
      </div> 
      <div class="skills_bar"> 
        <span class="skills_percetage skills_html"></span> 
      </div> 
    </div>   
  </WelcomeItem> 
 
  <WelcomeItem> 
    <template #icon> 
      <css /> 
    </template> 
    <div class="div"> 
      <div class="flex"> 
        <h3>CSS</h3> 
        <h3>65%</h3> 
      </div> 
      <div class="skills_bar"> 
        <span class="skills_percetage skills_css"></span> 
      </div> 
    </div>   
  </WelcomeItem> 
 
  <WelcomeItem> 
    <template #icon> 
      <figma /> 
    </template> 
    <div class="div"> 
      <div class="flex"> 
        <h3>Figma</h3> 
        <h3>80%</h3> 
      </div> 
      <div class="skills_bar"> 
        <span class="skills_percetage skills_figma"></span> 
      </div> 
    </div>   
  </WelcomeItem> 
 
  <WelcomeItem> 
    <template #icon> 
      <bootstrap />  
    </template> 
    <div class="div"> 
      <div class="flex"> 
        <h3>Bootstrap</h3> 
        <h3>50%</h3> 
      </div> 
      <div class="skills_bar"> 
        <span class="skills_percetage skills_bootstrap"></span> 
      </div> 
    </div>   
  </WelcomeItem> 
 
  <!-- <WelcomeItem> 
    <template #icon> 
      <SupportIcon /> 
    </template> 
    <template #heading>Support Vue</template> 
 
    As an independent project, Vue relies on community backing for its sustainability. You can help 
    us by 
    <a target="_blank" href="https://vuejs.org/sponsor/">becoming a sponsor</a>. 
  </WelcomeItem> --> 
</template> 
 
<style> 
.div{ 
  height: 85px; 
} 
 
.flex{ 
  display: flex; 
  justify-content: space-between; 
} 
 
h3{ 
  font-size: 1.2rem; 
  font-weight: 500; 
  margin-bottom: 0.4rem; 
  color: var(--color-heading); 
} 
 
.skills_bar, 
.skills_percetage{ 
  margin-top: 5px; 
  height: 5px; 
  border-radius: .25rem; 
} 
 
.skills_bar{ 
  background-color: #fff; 
} 
 
.skills_percetage{ 
  display: block; 
  background-color: rgb(0, 113, 189); 
} 
 
.skills_html{ 
  width: 85%; 
} 
 
.skills_css{ 
  width: 70%; 
} 
 
.skills_figma{ 
  width: 85%; 
} 
 
.skills_bootstrap{ 
  width: 80%; 
} 
</style>