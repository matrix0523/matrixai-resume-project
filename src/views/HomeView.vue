<script setup lang="ts">
import { RouterLink, RouterView, routeLocationKey } from 'vue-router'
import PersonalInfo from '@/components/Info/PersonalInfo.vue';
import PersonalAdvant from '@/components/Info/PersonalAdvant.vue';
import PersonalEdu from '@/components/Info/PersonalEdu.vue';
import PersonalIntern from '@/components/Info/PersonalIntern.vue';
import PersonalProj from '@/components/Info/PersonalProj.vue';
import PersonalProf from '@/components/Info/PersonalProf.vue';
import SiteFront from '@/components/Info/SiteFront.vue';
import SiteFoot from '@/components/Info/SiteFoot.vue';
</script>

<template>
  <SiteFront />
  <PersonalInfo />
  <PersonalAdvant />
  <PersonalEdu />
  <PersonalIntern />
  <PersonalProj />
  <PersonalProf />
  <SiteFoot />
</template>
<style> 
/* style */
</style>