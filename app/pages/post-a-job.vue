<script setup lang="ts">
import baseBtn from '~/components/baseBtn.vue';
</script>

<template>
  <div class="w-full banner">
    <div class="container pt-10 pb-10 flex flex-col items-center gap-10">
      <p class="uppercase text-primary font-black">Job Listings</p>
      <h2 class="text-[#fff] text-7xl font-black text-center">A job board built for the startup world</h2>
      <p>Post an infinite amount of jobs (for free) and instantly reach the most responsive, startup-ready community looking for their next great opportunity.</p>
      <div class="flex items-center gap-4">
        <baseBtn name="Post a job" />
        <NuxtLink to="/" class=" border-2 border-primary text-primary rounded-full px-4 py-2 hover:border-accent hover:bg-accent hover:text-[#fff] transition-all duration-300 ease-in-out">Request a demo</NuxtLink>
      </div>
    </div>
  </div>
  <div class="w-full">
    <div class="container grid grid-cols-2 items-center gap-4">
      <div class="flex flex-col gap-4">
        <span class="uppercase font-black text-primary">high exposure, great connection</span>
        <h2 class="font-black text-6xl">Get posting, get visibility, get ready to hire</h2>
        <p>Job Listings are visible where job-seekers spend their time: Wellfound’s job search, candidate emails, and our newsletter. Your Job Listing typically gets thousands of views per week; if you need more exposure, promote your job with a few clicks and gain visibility on a larger scale.</p>
        <NuxtLink to="/discover" class="font-semibold text-primary flex items-center gap-2 group">Post a job for free <Icon name="mi:arrow-right" class="transition-transform duration-300 group-hover:translate-x-2"/></NuxtLink>
      </div>
      <div class="p-15">
        <img src="/assets/images/find next hire 2.webp" alt="World of Talent">
      </div>
    </div>
  </div>
  <div class="w-full">
    <div class="container flex flex-col items-center gap-4">
      <div class="flex flex-col gap-8 items-center text-center">
        <h2 class="font-black text-6xl text-primary w-[600px]">Tell your story with company profiles</h2>
        <p>Designed to show what makes you different; its branding at its best</p>
        <NuxtLink to="/discover" class="font-semibold text-primary flex items-center gap-2 group">Create your company profile <Icon name="mi:arrow-right" class="transition-transform duration-300 group-hover:translate-x-2"/></NuxtLink>
      </div>
      <div class="p-15">
        <img src="/assets/images/find next hire 6.webp" alt="World of Talent" class="h-[500px]">
      </div>
    </div>
  </div>
  <div class="w-full bg-secondary">
    <div class="container grid grid-cols-2 items-center gap-4">
      <div class="p-15">
        <img src="/assets/images/find next hire 7.webp" alt="World of Talent">
      </div>
      <div class="flex flex-col gap-4">
        <span class="uppercase font-black text-primary">a worldwide workforce</span>
        <h2 class="font-black text-6xl">Go global or local – we have the distribution</h2>
        <p>Our global community of 10M+ is at your fingertips. Specify the regions and time zones where you'll accept candidates to build a distributed team, or one a bit closer to home. We can promise there’s an ideal candidate waiting for you in any location you choose.</p>
        <NuxtLink to="/discover" class="font-semibold text-primary flex items-center gap-2 group">Hire talent now <Icon name="mi:arrow-right" class="transition-transform duration-300 group-hover:translate-x-2"/></NuxtLink>
      </div>
    </div>
  </div>
  <div class="w-full">
    <div class="container grid grid-cols-2 items-center gap-4">
      <div class="flex flex-col gap-4">
        <span class="uppercase font-black text-primary">more inbound, less clutter</span>
        <h2 class="font-black text-6xl">Handle inbound talent with ease</h2>
        <p>With custom application questions, smart filters, and an auto-organized functionality based on how well talent matches your criteria, we thought of everything to make your inbound management seamless. Spend less time sifting through applicants, and more time connecting with great matches.</p>
        <NuxtLink to="/discover" class="font-semibold text-primary flex items-center gap-2 group">Get started with Job Listings <Icon name="mi:arrow-right" class="transition-transform duration-300 group-hover:translate-x-2"/></NuxtLink>
      </div>
      <div class="p-15">
        <img src="/assets/images/find next hire 8.webp" alt="World of Talent">
      </div>
    </div>
  </div>
  <div class="w-full bg-secondary">
    <div class="container grid grid-cols-2 items-center gap-4">
      <div class="p-15">
        <img src="/assets/images/find next hire 9.webp" alt="World of Talent">
      </div>
      <div class="flex flex-col gap-4">
        <span class="uppercase font-black text-primary">synced & Streamlined</span>
        <h2 class="font-black text-6xl">Plug and play ATS Integrations</h2>
        <p>Sync jobs and process applications within your ATS without unnecessary back-and-forth. We're deeply integrated with Greenhouse, Lever, Workable, and Ashby.</p>
        <NuxtLink to="/discover" class="font-semibold text-primary flex items-center gap-2 group">Connect your ATS <Icon name="mi:arrow-right" class="transition-transform duration-300 group-hover:translate-x-2"/></NuxtLink>
      </div>
    </div>
  </div>
  <div class="w-full py-30">
    <div class="container flex flex-col items-center gap-12 text-center">
      <h2 class="font-black text-4xl w-[500px]">A world of talent is waiting to discover you</h2>
      <p>Get started now.</p>
      <NuxtLink to="/sign-up" class="text-[#000] hover:text-[#fff] border-2 border-primary bg-primary hover:bg-accent hover:border-accent rounded-full px-4 py-2 transition-all duration-300 ease-in-out w-[200px] text-center">Post a job</NuxtLink>
    </div>
  </div>
  <div class="w-full bg-highlight">
    <div class="container py-15">
      <div class="flex flex-col gap-8">
        <h2 class="text-3xl font-bold">FAQ</h2>
        <div class="flex flex-col gap-2">
          <h4 class="text-xl font-medium">How do I post my first job?</h4>
          <p>Start by making sure you have a <NuxtLink to="/" class="underline hover:text-primary">company profile</NuxtLink> set up. From there, follow our guide to <NuxtLink to="/" class="underline hover:text-primary">post your first job.</NuxtLink></p>
        </div>
        <div class="flex flex-col gap-2">
          <h4 class="text-xl font-medium">What are the best practices for job listings?</h4>
          <p>To get the most aligned applicants, we recommend you fill out as many parts of the job listing as you can -- this includes having a great company profile, a salary range, location specifications, style of work, and more.</p>
        </div>
        <div class="flex flex-col gap-2">
          <h4 class="text-xl font-medium">What is the cost to post a job?</h4>
          <p>It’s 100% free to post your jobs on People Resolution.</p>
        </div>
        <div class="flex flex-col gap-2">
          <h4 class="text-xl font-medium">Have more questions?</h4>
          <p><NuxtLink to="/" class="underline hover:text-primary">Schedule a call</NuxtLink> with our team and we’ll be happy to help.</p>
        </div>
      </div>
    </div>
  </div>
</template>

