<template>
  <div class="max-w-7xl mx-auto px-6 py-12 antialiased selection:bg-indigo-100">
    
    <div class="absolute top-[-10%] left-[-10%] w-[40%] h-[40%] bg-[#7AE2CF]/10 blur-[120px] rounded-full"></div>
    <div class="absolute bottom-[-10%] right-[-10%] w-[30%] h-[30%] bg-[#0B3242]/40 blur-[100px] rounded-full"></div>

   <header class="text-center mb-16">
      <h1 class="text-5xl font-[900] tracking-tight mb-8 text-slate-900">Discover</h1>
      <nav class="inline-flex p-1 bg-slate-100 rounded-full border border-slate-200">
                <NuxtLink to="/discover" class="px-8 py-2.5 rounded-full text-sm font-bold text-slate-600 hover:text-black transition-all">All</NuxtLink>
                <NuxtLink to="/startups" class="px-8 py-2.5 rounded-full text-sm font-bold text-slate-600 hover:text-black transition-all">Startups</NuxtLink>
                <NuxtLink to="/blog" class="px-8 py-2.5 rounded-full text-sm font-bold text-[#000000] hover:text-secondary transition-all bg-secondary">Blog</NuxtLink>
        
      </nav>
    </header>

    <main class="max-w-7xl mx-auto relative z-10">
      
       <section class="mx-auto max-w-5xl px-4 py-12">
    <div class="group relative overflow-hidden rounded-3xl bg-white border border-gray-100 shadow-xl transition-all hover:shadow-2xl md:flex">
      
      <div class="flex items-center justify-center bg-yellow-400 p-8 md:w-1/3">
        <img 
          src="/assets/images/find next hire 4.webp" 
          alt="Job Search Illustration" 
          class="w-60  h-60 transform transition-transform duration-500 group-hover:scale-110 md:w-48"
        />
      </div>

      <div class="flex flex-col justify-center p-8 md:w-2/3 md:p-12 lg:p-16">
        <h3 class="mb-4 text-3xl font-bold tracking-tight text-gray-900 md:text-4xl lg:text-5xl">
          Get started today
        </h3>
        <p class="mb-8 text-lg leading-relaxed text-[#36454F] lg:text-xl">
          Apply to jobs with <span class="font-semibold ">one-click</span> and connect directly with founders looking for your specific skills.
        </p>
        
        <div class="flex flex-wrap gap-4">
          <NuxtLink
            to="/login"
            class="inline-flex items-center justify-center rounded-xl bg-black px-8 py-4 text-base font-bold text-white transition-all hover:bg-secondary hover:ring-4 hover:ring-blue-100 active:scale-95"
          >
            Create your profile
            <svg xmlns="" class="ml-2 h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6" />
            </svg>
          </NuxtLink>
        </div>
      </div>

    </div>
  </section>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">
        
        <div class="lg:col-span-1 lg:row-span-2 group bg-white/[0.03] border border-white/10 rounded-[2.5rem] overflow-hidden hover:bg-white/[0.06] transition-all duration-500">
          <div class="h-80 overflow-hidden relative">
            <img src="https://i.pinimg.com/736x/bb/6d/8b/bb6d8b197eb8292da006b4ec4fb35b40.jpg" 
                 class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-1000">
            <div class="absolute inset-0 bg-gradient-to-t from-[#010d12] to-transparent opacity-60"></div>
          </div>
          <div class="p-10">
            <span class="text-[10px] font-bold text-[#7AE2CF] uppercase tracking-[0.3em] mb-4 block italic">Trends / 2012</span>
            <h3 class="text-3xl font-black leading-tight mb-8 group-hover:text-[#7AE2CF] transition-colors">
               processor or processing unit is an electrical component.
            </h3>
            <div class="flex items-center justify-between border-t border-white/10 pt-8">
                <span class="text-xs font-bold text-gray-500 uppercase tracking-widest mt-5">Russ Rizzo</span>

            </div>
          </div>
        </div>


        <div class="lg:col-span-1 lg:row-span-2 group bg-white/[0.03] border border-white/10 rounded-[2.5rem] overflow-hidden hover:bg-white/[0.06] transition-all duration-500">
          <div class="h-80 overflow-hidden relative">
            <img src="https://i.pinimg.com/1200x/b6/fd/22/b6fd228ba4e85088d91b91c7c7797a17.jpg" 
                 class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-1000">
            <div class="absolute inset-0 bg-gradient-to-t from-[#010d12] to-transparent opacity-60"></div>
          </div>
          <div class="p-10">
            <span class="text-[10px] font-bold text-[#7AE2CF] uppercase tracking-[0.3em] mb-4 block italic">Trends / 2026</span>
            <h3 class="text-3xl font-black leading-tight mb-8 group-hover:text-[#7AE2CF] transition-colors">
              From the Founder | How General Assembly Became an AI Skills Leader by Listening to Inbound 
            </h3>
            <div class="flex items-center justify-between border-t border-white/10 pt-8">
              <span class="text-xs font-bold text-gray-500 uppercase tracking-widest mt-5">Russ Rizzo</span>
              
            </div>
          </div>
        </div>



          <div class="lg:col-span-1 lg:row-span-2 group bg-white/[0.03] border border-white/10 rounded-[2.5rem] overflow-hidden hover:bg-white/[0.06] transition-all duration-500">
          <div class="h-80 overflow-hidden relative">
            <img src="https://i.pinimg.com/736x/da/02/fd/da02fd087032746908846c1ee1427fa4.jpg" 
                 class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-1000">
            <div class="absolute inset-0 bg-gradient-to-t from-[#010d12] to-transparent opacity-60"></div>
          </div>
          <div class="p-10">
            <span class="text-[10px] font-bold text-[#7AE2CF] uppercase tracking-[0.3em] mb-4 block italic">Trends / 2036</span>
            <h3 class="text-3xl font-black leading-tight mb-8 group-hover:text-[#7AE2CF] transition-colors">
              Nexus is a Latin word for connection, usually where multiple elements meet. It may refer to.
            </h3>
            <div class="flex items-center justify-between border-t border-white/10 pt-8">
              <span class="text-xs font-bold text-gray-500 uppercase tracking-widest mt-5">Russ Rizzo</span>
              
            </div>
          </div>
        </div>




        



      </div>




    </main>



<div class="w-full banner">
        
        <div class="w-full bg-primary/10 py-6 rounded-2xl">
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
</script>





<style>
@import url('https://fonts.googleapis.com/css2?family=Epilogue:ital,wght@0,100..900;1,100..900&display=swap');
</style>