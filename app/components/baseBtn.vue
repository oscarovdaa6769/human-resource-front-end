<script setup lang="ts">
  defineProps({
    name: String
  })
</script>

<template>
  <NuxtLink to="/sign-up" class="text-[#000] hover:text-[#fff] border-2 border-primary bg-primary hover:bg-accent hover:border-accent rounded-full px-4 py-2 transition-all duration-300 ease-in-out self-start">{{ name }}</NuxtLink>
</template>

