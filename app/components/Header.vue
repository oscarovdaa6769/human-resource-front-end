<template>
  <header class="bg-white shadow-md sticky top-0 z-50">
    <div class="container mx-auto px-6">
      <div class="flex items-center justify-between h-16">

        <!-- Logo -->
        <NuxtLink to="/" class="text-2xl font-bold text-blue-600">
          JobFinder
        </NuxtLink>

        <!-- Desktop Menu -->
        <nav class="hidden md:flex items-center gap-8 font-medium text-gray-700">
          <NuxtLink to="/" class="hover:text-blue-600 transition">Home</NuxtLink>
          <NuxtLink to="/jobs" class="hover:text-blue-600 transition">Jobs</NuxtLink>
          <NuxtLink to="/companies" class="hover:text-blue-600 transition">Companies</NuxtLink>
          <NuxtLink to="/about" class="hover:text-blue-600 transition">About</NuxtLink>
        </nav>

        <!-- Right Buttons -->
        <div class="hidden md:flex items-center gap-4">
          <NuxtLink
            to="/login"
            class="px-4 py-2 text-blue-600 font-semibold hover:underline"
          >
            Login
          </NuxtLink>

          <NuxtLink
            to="/register"
            class="bg-blue-600 text-white px-5 py-2 rounded-lg hover:bg-blue-700 transition"
          >
            Sign Up
          </NuxtLink>
        </div>

        <!-- Mobile Button -->
        <button
          class="md:hidden"
          @click="isOpen = !isOpen"
        >
          ☰
        </button>
      </div>

      <!-- Mobile Menu -->
      <div v-if="isOpen" class="md:hidden pb-4 flex flex-col gap-3 text-gray-700">
        <NuxtLink to="/" @click="isOpen=false">Home</NuxtLink>
        <NuxtLink to="/jobs" @click="isOpen=false">Jobs</NuxtLink>
        <NuxtLink to="/companies" @click="isOpen=false">Companies</NuxtLink>
        <NuxtLink to="/about" @click="isOpen=false">About</NuxtLink>
        <NuxtLink to="/login" @click="isOpen=false">Login</NuxtLink>
        <NuxtLink to="/register" @click="isOpen=false">Sign Up</NuxtLink>
      </div>
    </div>
  </header>
</template>

<script setup>
import { ref } from "vue"

const isOpen = ref(false)
</script>

