<template>
  <div class="w-full bg-secondary">
    <div class="flex justify-between items-center py-4 w-7xl m-auto">
      <NuxtLink to="/"><img src="/assets/images/logo brand.png" alt="People-Resolution"></NuxtLink>
      <nav class="header-nav flex gap-4">
        <NuxtLink to="/">Home</NuxtLink>
        <NuxtLink to="/discover">Discover</NuxtLink>
        <NuxtLink to="/job-seeker">For Job Seeker</NuxtLink>
        <NuxtLink to="/companies">For Companies</NuxtLink>
        

      </nav>
      <div class="flex gap-2 items-center">
        <NuxtLink to="/login" class=" border-2 border-primary text-primary rounded-full px-4 py-2 hover:border-accent hover:bg-accent hover:text-[#fff] transition-all duration-300 ease-in-out">Login</NuxtLink>
        <NuxtLink to="/sign-up" class="text-[#000] hover:text-[#fff] border-primary bg-primary hover:bg-accent hover:border-accent rounded-full px-4 py-2 transition-all duration-300 ease-in-out">Sign Up</NuxtLink>
      </div>
    </div>
  </div>
</template>
