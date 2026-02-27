<template>
  <div class="w-full bg-secondary pt-20 pb-10">
    <div class="grid grid-cols-2 py-4 w-7xl m-auto">
      <img src="/assets/images/logo brand.png" alt="People-Resolution">
      <div class="grid grid-cols-3 p-4">
        <div class="footer-nav flex flex-col items-start justify-start gap-4">
          <h2 class=" font-black">For Candidates</h2>
          <NuxtLink to="/discover">Overview</NuxtLink>
          <NuxtLink to="/discover">Startup Jobs</NuxtLink>
          <NuxtLink to="/discover">Web3 Jobs</NuxtLink>
          <NuxtLink to="/discover">Featured</NuxtLink>
          <NuxtLink to="/discover">Salary Calculator</NuxtLink>
          <NuxtLink to="/discover">Startup Hiring Data</NuxtLink>
          <NuxtLink to="/discover">Tech Startups</NuxtLink>
          <NuxtLink to="/remots-page">Remote</NuxtLink>
        </div>
        <div class="footer-nav flex flex-col items-start justify-start gap-4">
          <h2 class=" font-black">For Recruiters</h2>
          <NuxtLink to="/discover">Overview</NuxtLink>
          <NuxtLink to="/discover">Recruit Pro</NuxtLink>
          <NuxtLink to="/discover">Curated</NuxtLink>
          <NuxtLink to="/discover">Hire Developers</NuxtLink>
          <NuxtLink to="/discover">Pricing</NuxtLink>
        </div>
        <div class="footer-nav flex flex-col items-start justify-start gap-4">
          <h2 class=" font-black">Company</h2>
          <NuxtLink to="/companies-page">About</NuxtLink>
          <NuxtLink to="/discover">Help</NuxtLink>
          <NuxtLink to="/discover">Blog</NuxtLink>
          <NuxtLink to="/discover">Terms & Risks</NuxtLink>
          <NuxtLink to="/discover">Privacy & Cookies</NuxtLink>
          <NuxtLink to="/discover">Trust</NuxtLink>
          <NuxtLink to="/discover">Platform Status</NuxtLink>
        </div>
      </div>
    </div>
  </div>
  <div class="w-full bg-secondary pb-10 text-xs">
    <div class="w-7xl m-auto flex items-center justify-between">
      <div class="flex gap-4 items-center">
        <Icon name="uil:twitter" class="[#fff] text-2xl hover:bg-primary transition-all duration-300 ease-in-out" />
        <Icon name="uil:instagram" class="[#fff] text-2xl hover:bg-primary transition-all duration-300 ease-in-out" />
      </div>
      <p>Copyright © 2026 People-Resolution. All rights reserved.</p>
      <NuxtLink to="/discover" class="underline hover:text-primary">Cookie Preferences</NuxtLink>
      <div class="flex gap-1">
        <p>Browse by:</p>
        <NuxtLink to="/discover" class="hover:text-primary hover:underline">Jobs</NuxtLink>,
        <NuxtLink to="/remots-page" class="hover:text-primary hover:underline">Remote Jobs</NuxtLink>,
        <NuxtLink to="/discover" class="hover:text-primary hover:underline">Locations</NuxtLink>,
        <NuxtLink to="/discover" class="hover:text-primary hover:underline">Startups</NuxtLink>,
        <NuxtLink to="/find-next-hire" class="hover:text-primary hover:underline">Startups Hiring</NuxtLink>,
        <NuxtLink to="/discover" class="hover:text-primary hover:underline">Industries</NuxtLink>,
        <NuxtLink to="/discover" class="hover:text-primary hover:underline">Tech Hubs</NuxtLink>
      </div>
    </div>
  </div>
</template>
