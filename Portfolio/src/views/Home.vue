<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
    <div class="hero bg-base-200 min-h-screen">
  <div class="hero-content flex-col lg:flex-row">
    <img
      src="https://img.daisyui.com/images/stock/photo-1635805737707-575885ab0820.webp"
      class="max-w-lq rounded-sm shadow-2xl" />
    <div>
      <h1 class="text-5xl font-bold">Jack Lin</h1>
      <p class="py-6">
        Hello there! I'm Jack Lin, a full-stack developer based in New York City. 
        I specialize in building web applications using modern technologies like Vue.js, React, and Node.js.
      </p>
      <RouterLink to="/contact">
      <button class="btn btn-primary">Contact Me</button>
        </RouterLink>
    </div>
  </div>
</div>
</template>

<style scoped>
</style>
