<template>
  <div class="w-full bg-secondary pt-20 pb-10">
    <div class="grid grid-cols-2 py-4 w-7xl m-auto">
      <img src="/assets/images/logo brand.png" alt="People-Resolution">
      <div class="grid grid-cols-3 p-4">
        <div class="footer-nav flex flex-col items-start justify-start gap-4">
          <h2 class=" font-black">For Candidates</h2>
          <NuxtLink to="/overview">Overview</NuxtLink>
          <NuxtLink to="/startup-job">Startup Jobs</NuxtLink>
          <NuxtLink to="/web3-job">Web3 Jobs</NuxtLink>
          <NuxtLink to="/featured">Featured</NuxtLink>
          <NuxtLink to="/salary-calculator">Salary Calculator</NuxtLink>
          <NuxtLink to="/startup-hiring-data">Startup Hiring Data</NuxtLink>
          <NuxtLink to="/tech-startup">Tech Startups</NuxtLink>
          <NuxtLink to="/remote">Remote</NuxtLink>
        </div>
        <div class="footer-nav flex flex-col items-start justify-start gap-4">
          <h2 class=" font-black">For Recruiters</h2>
          <NuxtLink to="/overview">Overview</NuxtLink>
          <NuxtLink to="/startup-job">Recruit Pro</NuxtLink>
          <NuxtLink to="/web3-job">Curated</NuxtLink>
          <NuxtLink to="/featured">Hire Developers</NuxtLink>
          <NuxtLink to="/salary-calculator">Pricing</NuxtLink>
        </div>
        <div class="footer-nav flex flex-col items-start justify-start gap-4">
          <h2 class=" font-black">Company</h2>
          <NuxtLink to="/overview">About</NuxtLink>
          <NuxtLink to="/startup-job">Help</NuxtLink>
          <NuxtLink to="/web3-job">Blog</NuxtLink>
          <NuxtLink to="/featured">Terms & Risks</NuxtLink>
          <NuxtLink to="/salary-calculator">Privacy & Cookies</NuxtLink>
          <NuxtLink to="/salary-calculator">Trust</NuxtLink>
          <NuxtLink to="/salary-calculator">Platform Status</NuxtLink>
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
      <NuxtLink to="/" class="underline hover:text-primary">Cookie Preferences</NuxtLink>
      <div class="flex gap-1">
        <p>Browse by:</p>
        <NuxtLink to="/" class="hover:text-primary hover:underline">Jobs</NuxtLink>,
        <NuxtLink to="/" class="hover:text-primary hover:underline">Remote Jobs</NuxtLink>,
        <NuxtLink to="/" class="hover:text-primary hover:underline">Locations</NuxtLink>,
        <NuxtLink to="/" class="hover:text-primary hover:underline">Startups</NuxtLink>,
        <NuxtLink to="/" class="hover:text-primary hover:underline">Startups Hiring</NuxtLink>,
        <NuxtLink to="/" class="hover:text-primary hover:underline">Industries</NuxtLink>,
        <NuxtLink to="/" class="hover:text-primary hover:underline">Tech Hubs</NuxtLink>
      </div>
    </div>
  </div>
</template>
