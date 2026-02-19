<template>
    <div class="w-full banner">
        <div class="container pt-10 pb-10 flex flex-col items-center gap-10">
            <h2 class="text-7xl font-black text-center mt-15">Find the job made for you.</h2>
            <p class=" text-center font-black">We make it easy to find what's next. <br> Browse over 100,000 jobs — from top companies to fast-growing startups. </p>
           <div class="flex gap-2 items-center ">
                <NuxtLink to="/create your profile" class="w-[200px] text-center text-[#000] hover:text-[#fff] border-2 border-primary bg-primary hover:bg-accent hover:border-accent rounded-full px-4 py-2 transition-all duration-300 ease-in-out mr-5">Create your profile</NuxtLink>
                <NuxtLink to="/browse jobs" class="w-[200px] text-center border-2 border-primary text-primary rounded-full px-4 py-2 hover:border-accent hover:bg-accent hover:text-[#fff] transition-all duration-300 ease-in-out">Browse jobs</NuxtLink>
            </div>
        </div>
    </div>
    <div class="w-full bg-highlight  banner">
        <div class="container pt-20 pb-10 flex flex-row items-center gap-35 justify-center">
            
            <div class=" flex flex-col items-center gap-5">
                <h3 class="text-8xl text-primary font-black font-bold">8M+</h3>
                <p class="text-2xl font-black text-center">Matches Made</p>
            </div>
            <div class="ml-10 flex flex-col  items-center gap-5">
                <h3 class="text-8xl text-center text-primary font-black font-bold">150K+</h3>
                <p class="text-2xl font-black font-black text-center">Tech Jobs</p>
            </div>
            <div class="flex flex-col items-center gap-5">
                <h3 class="text-8xl text-primary font-black font-bold">10M+</h3>
                <p class="text-2xl font-black text-center">Startup Ready Candidates</p>
            </div>
        </div>
        <div class="w-200 h-0.5 bg-primary items-center justify-center mx-auto mt-20 "></div>
        <div class="container pt-20 pb-10 flex flex-row items-center gap-35 justify-center">
             <div class=" flex flex-col items-center gap-5">
                <p class=" font-black text-center">Startups who used our platform</p>
            </div>
        </div>
    </div>
     <div class="w-full banner">
        <div class="container  pb-10 flex flex-row items-center gap-35 justify-center">
            <div class="p-15">
                <img src="/assets/images/job seeker.webp" alt="World of Talent">
            </div>
            <div class="w-300">
                <h2 class="text-5xl font-black mb-10">Brand yourself for new opportunities</h2>
                <p class="text-1xl font-black ">Create a profile that highlights your unique skills and preferences, then apply to jobs with just one click</p>
                <div class="flex gap-2 items-center ">
                    <NuxtLink
                        to="/click"
                        class="w-[100px] h-[60px] flex items-center justify-center
                                border-4 border-primary bg-primary
                                hover:bg-accent hover:border-accent
                                rounded-full transition-all duration-300 ease-in-out mr-5"
                        >
                        <img
                            src="/assets/images/click.png"
                            alt="click"
                            class="w-10 h-10 object-contain"
                        >
                    </NuxtLink>
                   <div class="mt-10">
                            <h2 class="text-2xl font-black mt-5 text-primary">One click apply</h2>
                            <p class="mt-2">Say goodbye to cover letters - your profile is all you need. One click to apply then you're done.</p>
                        </div>
                </div>
                 <div class="flex gap-2 items-center ">
                    <NuxtLink
                        to="/click"
                        class="w-[100px] h-[60px] flex items-center justify-center
                                border-4 border-primary bg-primary
                                hover:bg-accent hover:border-accent
                                rounded-full transition-all duration-300 ease-in-out mr-5"
                        >
                        <img
                            src="/assets/images/click1.png"
                            alt="click"
                            class="w-10 h-10 object-contain"
                        >
                    </NuxtLink>
                        <div class="mt-10 pt-15">
                            <h2 class="text-2xl font-black mt-5 text-primary">Set your preferences</h2>
                            <p class="mt-2 mb-10">Streamline the interview process by setting your expectations (salary, industry, culture, etc.) upfront.</p>
                            <NuxtLink to="/discover" class="m-5 text-2xl font-semibold text-primary flex items-center gap-2 group">Create your profile<Icon name="mi:arrow-right" class="transition-transform duration-300 group-hover:translate-x-2"/></NuxtLink>
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
            <h2 class="font-black text-6xl">Find work that works for you</h2>
            <p>A personalized and private job search, with all the info you care about, all upfront</p>
            <div class="flex  items-center ">
                    <NuxtLink
                        to="/click"
                        class="w-[50px] h-[50px] flex items-center justify-center
                                border-4 border-primary bg-primary
                                hover:bg-accent hover:border-accent
                                rounded-full transition-all duration-300 ease-in-out mr-5">
                        <img
                            src="/assets/images/click.png"
                            alt="click"
                            class="w-8 h-8 object-contain">
                    </NuxtLink>
                    <div class="mt-6">
                            <h2 class="text-2xl font-black mt-5 text-primary">Stay in the know</h2>
                            <span class="mt-2">No guessing games. View salary and stock options before you apply.</span>
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
                            src="/assets/images/click2.png"
                            alt="click"
                            class="w-8 h-8 object-contain">
                    </NuxtLink>
                    <div class="mt-6">
                            <h2 class="text-2xl font-black mt-5 text-primary">Personalized search</h2>
                            <span class="mt-2">Personalized filters make it quick and easy to find the jobs you care about</span>
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
                            src="/assets/images/click3.png"
                            alt="click"
                            class="w-8 h-8 object-contain">
                    </NuxtLink>
                    <div class="mt-6">
                            <h2 class="text-2xl font-black mt-5 text-primary">Unique roles, exciting teams</h2>
                            <span class="mt-2">Discover unique jobs with future-defining teams</span>
                    </div>
            </div>
            <NuxtLink to="/discover" class="m-15 text-2xl font-semibold text-primary flex items-center gap-2 group">Browes Jobs<Icon name="mi:arrow-right" class="transition-transform duration-300 group-hover:translate-x-2"/></NuxtLink>
        </div>
        <div class=" p-15">
            <img src="/assets/images/job seeker1.webp" alt="World of Talent">
        </div>
        </div>
    </div>
    <div class="w-full h-0.5 bg-primary items-center justify-center mx-auto mt-20 "></div>
     <div class="w-full banner "></div>
        <div class="w-full">
        <div class="container grid grid-cols-2 items-center gap-4">
             <div class=" p-15">
            <img src="/assets/images/job seeker2.webp" alt="World of Talent">
        </div>
        <div class="flex flex-col gap-4">
            <h2 class="font-black text-5xl">FLet the opportunities come to you</h2>
            <div class="flex  items-center ">
                    <NuxtLink
                        to="/click"
                        class="w-[50px] h-[50px] flex items-center justify-center
                                border-4 border-primary bg-primary
                                hover:bg-accent hover:border-accent
                                rounded-full transition-all duration-300 ease-in-out mr-5">
                        <img
                            src="/assets/images/click4.png"
                            alt="click"
                            class="w-8 h-8 object-contain">
                    </NuxtLink>
                    <div class="mt-6">
                            <h2 class="text-2xl font-black mt-5 text-primary">Connect with founders</h2>
                            <span class="mt-2">Let founders pitch you directly on their opportunity. </span>
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
                            src="/assets/images/click5.png"
                            alt="click"
                            class="w-8 h-8 object-contain">
                    </NuxtLink>
                    <div class="mt-6">
                            <h2 class="text-2xl font-black mt-5 text-primary">Get featured</h2>
                            <span class="mt-2">Feature your profile even further and make 3x more connections</span>
                    </div>
            </div>
            <NuxtLink to="/discover" class="m-15 text-2xl font-semibold text-primary flex items-center gap-2 group">Get Started<Icon name="mi:arrow-right" class="transition-transform duration-300 group-hover:translate-x-2"/></NuxtLink>
        </div>
       
        </div>
    </div>

    <div class="w-full banner">
        <div class="max-w-7xl mx-auto">
      <div class="flex justify-between items-center mb-10">
        <h3 class="text-4xl text-primary font-bold tracking-tight">From the blog</h3>
    
      </div>

      <div class="space-y-8">
        <div v-for="(post, index) in blogPosts" :key="index" class="flex flex-col md:flex-row md:items-center gap-4 md:gap-8 border-b border-gray-100 pb-8 last:border-0">
          <div class="md:w-3/6 text-sm font-semibold text-gray-600">
            <h4 class="text-2xl font-bold tracking-tight  text-white  hover:text-primary cursor-pointer">
              {{ post.title }}
            </h4>
          </div>
          <div class="md:w-2/6 text-gray-100 leading-relaxed text-sm">
            {{ post.description }}
          </div>
          <div class="flex-shrink-0">
            <button class="w-12 h-12 rounded-full bg-primary-100  text-secondary flex items-center justify-center  transition">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3" />
              </svg>
            </button>
          </div>
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








const blogPosts = [
  {
    type: "Blog Post",
    title: "30 Questions to Ask Before Joining a Startup",
    description: "You're trying to evaluate the company while still impressing your interviewers, and that balance can be tricky..."
  },
  {
    type: "Job Collection",
    title: "18 Innovative Space Startups Hiring Now",
    description: "Few tech sectors are capturing the public's collective imagination as much as space. Privatized spaceflight, or \"NewSpace,\" is attracting..."
  },
   {
    type: "Job Collection",
    title: "18 Innovative Space Startups Hiring Now",
    description: "Few tech sectors are capturing the public's collective imagination as much as space. Privatized spaceflight, or \"NewSpace,\" is attracting..."
  },
   {
    type: "Job Collection",
    title: "18 Innovative Space Startups Hiring Now",
    description: "Few tech sectors are capturing the public's collective imagination as much as space. Privatized spaceflight, or \"NewSpace,\" is attracting..."
  },
  {
    type: "Job Collection",
    title: "19 Hot Crypto Startups Hiring Remotely in 2022",
    description: "Either Crypto has a great PR team, or the internet-based medium of exchange is truly taking the world by storm..."
  }
  
];
</script>
