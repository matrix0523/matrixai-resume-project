<script setup lang="ts">
import { RouterLink, RouterView, routeLocationKey } from 'vue-router'
import PersonalInfo from '@/components/Info/PersonalInfo.vue';
import PersonalAdvant from '@/components/Info/PersonalAdvant.vue';
import PersonalEdu from '@/components/Info/PersonalEdu.vue';
import PersonalIntern from '@/components/Info/PersonalIntern.vue';
import PersonalProj from '@/components/Info/PersonalProj.vue';
import PersonalProf from '@/components/Info/PersonalProf.vue';
import SiteFront from '@/components/Info/SiteFront.vue'
</script>

<template>
  <SiteFront />
  <PersonalInfo />
  <PersonalAdvant />
  <PersonalEdu />
  <PersonalIntern />
  <PersonalProj />
  <PersonalProf />
  <footer>
      <RouterLink class="footer"  to="/about">
        <h4 style="color: white;">&copy; 2018~2024 创世CreativeAI</h4>
      </RouterLink>
    <!-- <RouterView /> -->
  </footer>
</template>
<style> 
.footer {
  margin-top: 0;
  margin-bottom: 0;
  margin-left: 0;
  margin-right: 0;
  padding-left: 0;
  padding-right: 0;
  padding-top: 0;
  padding-bottom: 0;
}
</style>