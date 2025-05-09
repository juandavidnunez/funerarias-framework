<script setup>
import Sidebar from './components/Sidebar.vue'
import MainContent from './components/MainContent.vue'
</script>

<template>
  <div class="flex h-screen">
    <Sidebar />
    <MainContent />
  </div>
</template>

<style scoped>
/* No se necesitan estilos personalizados, Tailwind lo cubre */
</style>
