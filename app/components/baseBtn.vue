<script setup lang="ts">
  defineProps({
    name: String
  })
</script>

<template>
  <NuxtLink class="text-[#000] hover:text-[#fff] border-2 border-primary bg-primary hover:bg-accent hover:border-accent rounded-full px-4 py-2 transition-all duration-300 ease-in-out self-start cursor-pointer">{{ name }}</NuxtLink>
</template>

