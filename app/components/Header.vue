<script setup="ts">
import baseBtn from './baseBtn.vue';
</script>

<template>
  <div class="w-full bg-secondary fixed top-0 border-b-1 border-accent z-[1000]">
    <div class="flex justify-between items-center py-8 w-7xl m-auto">
      <NuxtLink to="/"><img src="/assets/images/logo brand.png" alt="People-Resolution"></NuxtLink>
      <nav class="header-nav flex gap-4">
        <NuxtLink to="/">Home</NuxtLink>
        <NuxtLink to="/discover">Discover</NuxtLink>
        <NuxtLink to="/find-next-job">For Job Seeker</NuxtLink>
        <NuxtLink to="/find-next-hire">For Companies</NuxtLink>
      </nav>
      <div class="flex gap-2 items-center">
        <NuxtLink to="/login" class=" border-2 border-primary text-primary rounded-full px-4 py-2 hover:border-accent hover:bg-accent hover:text-[#fff] transition-all duration-300 ease-in-out">Login</NuxtLink>
        <baseBtn name="Sign up" to="/candidate-profile" />
      </div>
      <div class="bg-primary"></div>
    </div>
  </div>
</template>
