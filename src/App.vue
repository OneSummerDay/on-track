<script setup>

import { ClockIcon, ListBulletIcon, ChartBarIcon } from '@heroicons/vue/24/outline'
import TheHeader from './components/TheHeader.vue'

const navItems = {
  timeline: ClockIcon,
  activities: ListBulletIcon,
  progress: ChartBarIcon
}
</script>

<template>
<!--Header-->
  <TheHeader />
<!--Main block-->
  <main class="flex flex-grow flex-col"></main>

<!--Navigation menu-->
  
</template>

