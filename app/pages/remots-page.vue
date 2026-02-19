<template>
    <div class="w-full banner">
        <div class="container pt-10 pb-10 flex flex-col items-center gap-10">
            <h2 class="text-7xl font-black text-center mt-15">Skip the commute. We're bringing the office to you.</h2>
            <p class=" text-center font-black">Introducing a new suite of tools to help you find a remote tech job, from anywhere in the world.</p>
           <div class="flex gap-2 items-center ">
                <NuxtLink to="/create your profile" class="w-[200px] text-center text-[#000] hover:text-[#fff] border-2 border-primary bg-primary hover:bg-accent hover:border-accent rounded-full px-4 py-2 transition-all duration-300 ease-in-out mr-5">Find a remote jobs</NuxtLink>
            </div>
        </div>
    </div>
<div class="w-full banner">
     <div class="w-full flex justify-center">
    <div
      class="relative w-full max-w-4xl rounded-xl overflow-hidden shadow-lg cursor-pointer group"
      @click="openVideo"
    >
      <!-- Thumbnail Image -->
      <img
        src="/assets/images/job-search-preview.png"
        alt="Video Preview"
        class="w-full h-full object-cover"
      />

      <!-- Dark overlay -->
      <div class="absolute inset-0 bg-black/30 group-hover:bg-black/40 transition"></div>

      <!-- Play Button -->
      <div
        class="absolute inset-0 flex items-center justify-center"
      >
        <div class="bg-red-600 rounded-full p-4 shadow-lg group-hover:scale-110 transition">
          ▶
        </div>
      </div>
    </div>
  </div>
</div>
<div class="w-full h-0.5 bg-primary items-center justify-center mx-auto mt-20 "></div>
 <div class="w-full banner "></div>
        <div class="w-full">
        <div class="container grid grid-cols-2 items-center gap-4">
             <div class=" p-15">
            <img src="/assets/images/job seeker3.png" alt="World of Talent">
        </div>
        <div class="flex flex-col gap-4">
            <h2 class="font-black text-5xl">Remote work the way you want it</h2>
            <div class="flex  items-center ">
                    <NuxtLink
                        to="/click"
                        class="w-[50px] h-[50px] flex items-center justify-center
                                border-4 border-primary bg-primary
                                hover:bg-accent hover:border-accent
                                rounded-full transition-all duration-300 ease-in-out mr-5">
                        <img
                            src="/assets/images/click6.png"
                            alt="click"
                            class="w-8 h-8 object-contain">
                    </NuxtLink>
                    <div class="mt-6">
                            <h2 class="text-2xl font-black mt-5 text-primary">Remote</h2>
                            <span class="mt-2">Tell recruiters you're open to remote work </span>
                    </div>
            </div>
            <div class="flex  items-center ">
                    <NuxtLink
                        to="/click"
                        class="w-[50px] h-[50px] flex items-center justify-center
                                border-4 border-primary bg-primary
                                hover:bg-accent hover:border-accent
                                rounded-full transition-all duration-300 ease-in-out mr-5">
                        <img
                            src="/assets/images/click7.png"
                            alt="click"
                            class="w-8 h-8 object-contain">
                    </NuxtLink>
                    <div class="mt-6">
                            <h2 class="text-2xl font-black mt-5 text-primary">Culture</h2>
                            <span class="mt-2">Share what kind of remote culture you're looking for</span>
                    </div>
            </div>
             <div class="flex  items-center ">
                    <NuxtLink
                        to="/click"
                        class="w-[50px] h-[50px] flex items-center justify-center
                                border-4 border-primary bg-primary
                                hover:bg-accent hover:border-accent
                                rounded-full transition-all duration-300 ease-in-out mr-5">
                        <img
                            src="/assets/images/click8.png"
                            alt="click"
                            class="w-8 h-8 object-contain">
                    </NuxtLink>
                    <div class="mt-6">
                            <h2 class="text-2xl font-black mt-5 text-primary">Timezones</h2>
                            <span class="mt-2">Set your timezone and whether you're willing to work US hours</span>
                    </div>
            </div>
        </div>
    </div>
</div>
<div class="w-full h-0.5 bg-primary items-center justify-center mx-auto mt-20 "></div>


    
    <div class="w-full banner "></div>
        <div class="w-full">
        <div class="container grid grid-cols-2 items-center gap-4">
        <div class="flex flex-col gap-4">
            <h2 class="font-black text-6xl">Showcase your skills across borders</h2>
            <div class="flex  items-center ">
                    <NuxtLink
                        to="/click"
                        class="w-[50px] h-[50px] flex items-center justify-center
                                border-4 border-primary bg-primary
                                hover:bg-accent hover:border-accent
                                rounded-full transition-all duration-300 ease-in-out mr-5">
                        <img
                            src="/assets/images/click9.png"
                            alt="click"
                            class="w-8 h-8 object-contain">
                    </NuxtLink>
                    <div class="mt-6">
                            <h2 class="text-2xl font-black mt-5 text-primary">Engineering assessments</h2>
                            <span class="mt-2">Take engineering assessments to showcase your skills beyond the resume</span>
                    </div>
            </div>
            <div class="flex  items-center ">
                    <NuxtLink
                        to="/click"
                        class="w-[50px] h-[50px] flex items-center justify-center
                                border-4 border-primary bg-primary
                                hover:bg-accent hover:border-accent
                                rounded-full transition-all duration-300 ease-in-out mr-5">
                        <img
                            src="/assets/images/click10.png"
                            alt="click"
                            class="w-8 h-8 object-contain">
                    </NuxtLink>
                    <div class="mt-6">
                            <h2 class="text-2xl font-black mt-5 text-primary">Video assessments</h2>
                            <span class="mt-2">Take a video assessment to personalize your profile</span>
                    </div>
            </div>
        </div>
        <div class=" p-15">
            <img src="/assets/images/job seeker4.png" alt="World of Talent">
        </div>
        </div>
    </div>


<div class="w-full h-0.5 bg-primary items-center justify-center mx-auto mt-20 "></div>


    <div class="w-full banner ">
        <div class="w-full">
            <div class="container grid grid-cols-2 items-center gap-4">
                <div class=" p-15">
                <img src="/assets/images/job seeker5.png" alt="World of Talent">
            </div>
            <div class="flex flex-col gap-4">
                <h2 class="font-black text-6xl">Get your profile featured directly to recruiters</h2>
                <p>Apply to get your profile featured directly to companies that are hiring remotely (including internationally). This means your profile gets extra visibility for roles relevant to you.</p>
            </div>
        
            </div>
        </div>
    </div>





    <div class="w-full h-0.5 bg-primary items-center justify-center mx-auto mt-20 "></div>


    <div class="w-full banner ">
        <div class="w-full">
            <div class="container grid grid-cols-2 items-center gap-4">
                
                <div class="flex flex-col gap-4">
                    <h2 class="font-black text-6xl">Apply & get hired for US jobs without the need for a visa</h2>
                    <p>Filter by remote opportunities with companies hiring in your location. For these roles, you won't need to worry about visa requirements.</p>
                </div>
                <div class=" p-15">
                    <img src="/assets/images/job seeker6.png" alt="World of Talent">
                </div>
            </div>
        </div>
    </div>




    <div class="w-full banner">
        
        <div class="w-full bg-accent py-6 ">
            <div class="container mx-auto flex gap-4 items-center justify-center">

            <!-- Dropdown Item -->
            <div
                v-for="(menu, index) in menus"
                :key="index"
                class="relative"
            >
                <!-- Button -->
                <button
                @click="toggle(index)"
                class="flex items-center gap-2 px-6 py-3 rounded-xl border border-white/30 text-white hover:bg-white/10 transition"
                >
                {{ menu.title }}
                <svg
                    :class="{ 'rotate-180': openIndex === index }"
                    class="w-4 h-4 transition-transform duration-300"
                    fill="none"
                    stroke="currentColor"
                    viewBox="0 0 24 24"
                >
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/>
                </svg>
                </button>

                <!-- Dropdown -->
                <div
                v-if="openIndex === index"
                class="absolute left-0 mt-3 w-80 bg-gray-100 text-gray-800 rounded-2xl shadow-lg p-4 z-50"
                >
                <ul class="space-y-2">
                    <li
                    v-for="item in menu.items"
                    :key="item"
                    class="px-3 py-2 rounded-lg hover:bg-gray-200 hover:text-accent cursor-pointer"
                    >
                    {{ item }}
                    </li>
                </ul>
                </div>
            </div>

            </div>
        </div>
    </div>
</template>    


<script setup>
import { ref } from "vue";

const openIndex = ref(null);

const toggle = (index) => {
  openIndex.value = openIndex.value === index ? null : index;
};

const menus = [
  {
    title: "Job Collections",
    items: [
      "Remote First Future Jobs",
      "Jobs for Bootcamp Grads",
      "Junior Software Engineer Jobs",
      "Crypto Startups to Watch Out for",
      "Blockchain Startups That Are Hiring",
      "Companies Hiring Amidst Layoffs",
      "Hot Consumer Fintech Startups",
      "Y Combinator Startup Jobs",
      "Startup Jobs in Bay Area",
      "Top Women-Led Startups",
      "More Job Collections",
    ],
  },
  {
    title: "Remote Jobs",
    items: [
      "Remote Engineering Jobs",
      "Remote Design Jobs",
      "Remote Marketing Jobs",
      "Remote Product Jobs",
    ],
  },
  {
    title: "Jobs by Location",
    items: [
      "USA Jobs",
      "Europe Jobs",
      "Asia Jobs",
      "Remote Worldwide",
    ],
  },
  {
    title: "Jobs by Role",
    items: [
      "Frontend Developer",
      "Backend Developer",
      "Fullstack Developer",
      "UI/UX Designer",
    ],
  },
  {
    title: "Jobs by Role & Location",
    items: [
      "Frontend in USA",
      "Backend in Europe",
      "Designer in Asia",
      "Remote Fullstack",
    ],
  },
];



const openVideo = () => {
  window.open("https://youtu.be/QxaNqrFYDX4", "_blank")
}
</script>