<script setup>
import VHeader from './components/VHeader.vue'
import { RouterView } from 'vue-router'
import VFooter from './components/VFooter.vue'
</script>

<template>
  <VHeader />
  <RouterView />
  <VFooter />
</template>

<style scoped></style>
