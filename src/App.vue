<script setup>
import Navbar from './components/Navbar.vue'
</script>

<template>
  <div class="main-app">
    <Navbar />
    <main class="flex justify-center items-center max-w-lg mx-auto w-full">
      <RouterView />
    </main>
  </div>
</template>
