<script setup>

const categories = [
  { name: 'Biotech', count: 143, emoji: '🧬' },
  { name: 'Healthcare', count: 816, emoji: '🏥' },
  { name: 'Fintech', count: 422, emoji: '💳' },
  { name: 'AI / ML', count: 1205, emoji: '🤖' }
];

const articles = [
  {
    title: "Security in the Skies: 5 High Altitude Balloon Startups",
    author: "Russ Rizzo",
    image: "https://images.unsplash.com/photo-1517976487492-5750f3195933?auto=format&fit=crop&w=800&q=80"
  }
];

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

<template>
  <main class="max-w-7xl mx-auto px-6 py-12 antialiased selection:bg-indigo-100">
    
    <header class="text-center mb-16">
      <h1 class="text-5xl font-[900] tracking-tight mb-8 text-slate-900">Discover</h1>
      <nav class="inline-flex p-1 bg-slate-100 rounded-full border border-slate-200">
        <NuxtLink to="/" class="px-8 py-2.5 rounded-full text-sm font-bold text-[#000000] hover:text-secondary transition-all bg-secondary">All</NuxtLink>
        <NuxtLink to="/startups" class="px-8 py-2.5 rounded-full text-sm font-bold text-slate-600 hover:text-black transition-all">Startups</NuxtLink>
        <NuxtLink to="/blog" class="px-8 py-2.5 rounded-full text-sm font-bold text-slate-600 hover:text-black transition-all">Blog</NuxtLink>
        
      </nav>
    </header>

    <section class="relative overflow-hidden  p-10 mb-12 text-white">
      <div class="absolute top-0 right-0 w-2/3 h-full bg-[#E9357B]/2 to-transparent lex items-center justify-center ">
        <h3 class="text-center mt-5 italic">THE ULTIMATE STARTUP DIGEST, SENT WEEKLY</h3>
        <span class="text-xl font-black italic tracking-tighter ml-5">Trending stories, startups to watch, what's next in tech, & so much more...</span>

        </div>
      
      <div class="relative z-10 flex flex-col lg:flex-row items-center justify-between gap-10">
        <div class="flex flex-col items-center lg:items-start gap-1 lg:border-r lg:border-white/10 lg:pr-12">
          <span class="text-3xl font-black italic tracking-tighter">PEOPLESULUTION</span>
          <span class="text-[10px] tracking-[0.4em] font-bold text-indigo-400 uppercase">Newsletter</span>
        </div>
      </div>
    </section>

    <div class="columns-1 md:columns-2 lg:columns-3 gap-6 space-y-6">
      
      <div v-for="article in articles" :key="article.title" 
        class="break-inside-avoid group bg-white/10 border border-slate-200 rounded-[2.5rem] overflow-hidden hover:border-indigo-500 transition-all duration-500 hover:shadow-2xl hover:shadow-secondary">
        <img :src="article.image" class="w-full h-56 object-cover grayscale-[40%] group-hover:grayscale-0 transition-all duration-700" />
        <div class="p-8">
          <h3 class="text-xl font-extrabold leading-tight text-[#ffffff] group-hover:text-indigo-600 transition-colors">{{ article.title }}</h3>
          <div class="mt-8 flex items-center justify-between">
            <span class="text-sm font-bold text-slate-400">{{ article.author }}</span>
            <span class="text-xs font-black text-indigo-600 group-hover:translate-x-1 transition-transform tracking-widest">READ →</span>
          </div>
        </div>
      </div>

     <div class="break-inside-avoid bg-white/10 border border-slate-200 rounded-[2rem] p-6 hover:shadow-xl transition-all flex items-center gap-5 cursor-pointer hover:scale-[1.02]">
        <div class="w-16 h-16 bg-slate-900 rounded-2xl flex-shrink-0 flex items-center justify-center font-black text-xl text-[#ffffff]"><img src="https://i.pinimg.com/736x/a1/ff/bf/a1ffbf948bcc663e2907d9f22fdece64.jpg" alt="" class="rounded-2xl"></div>
        <div class="flex-1">
          <h4 class="font-bold text-lg">Paysfe</h4>
          <p class="text-sm text-[#ffffff] line-clamp-1 font-medium italic">Making performance management software for forward-thinking organizations</p>
        </div>
      </div>

      <div class="break-inside-avoid bg-white/10 border border-slate-200 rounded-[2rem] p-6 hover:shadow-xl transition-all flex items-center gap-5 cursor-pointer hover:scale-[1.02]">
        <div class="w-16 h-16 bg-slate-900 rounded-2xl flex-shrink-0 flex items-center justify-center font-black text-xl text-[#ffffff]"><img src="https://i.pinimg.com/736x/79/38/c7/7938c7cd786b3db0b4a1942b23c76ca5.jpg" alt="" class="rounded-2xl"></div>
        <div class="flex-1">
          <h4 class="font-bold text-lg">Paytek</h4>
          <p class="text-sm text-[#ffffff] line-clamp-1 font-medium italic">Our vision is a world where every real estate transaction is simple, certain, and satisfyi</p>
        </div>
      </div>

      <div class="break-inside-avoid bg-white/10 border border-slate-200 rounded-[2rem] p-6 hover:shadow-xl transition-all flex items-center gap-5 cursor-pointer hover:scale-[1.02]">
        <div class="w-16 h-16 bg-slate-900 rounded-2xl flex-shrink-0 flex items-center justify-center font-black text-xl text-[#ffffff]"><img src="https://i.pinimg.com/736x/19/8a/fd/198afdb944d6fd89cb167f35ae2a611f.jpg" alt="" class="rounded-2xl"></div>
        <div class="flex-1">
          <h4 class="font-bold text-lg">Grammarly</h4>
          <p class="text-sm text-[#ffffff] line-clamp-1 font-medium italic">Improving lives by improving communication</p>
        </div>
      </div>

          <div class="break-inside-avoid group bg-white/8 border border-slate-200 rounded-3xl overflow-hidden hover:border-blue-500 transition-all duration-300 shadow-sm hover:shadow-2xl hover:shadow-blue-500/5">
        <img src="https://d2gn4xht817m0g.cloudfront.net/p/job_collections/heros/original/000/000/241/241-0d38ddb7596d1dfa9194c8c80092e59ba3d064e1.webp" class="w-full h-48 object-cover grayscale-[20%] group-hover:grayscale-0 transition-all" />
        <div class="p-6">
          <h3 class="text-xl font-bold leading-snug group-hover:text-blue-600 transition-colors">Security in the Skies: 5 High Altitude Balloon Startups</h3>
          <div class="mt-6 flex items-center justify-between">
            <span class="text-sm font-medium text-slate-500">Russ Rizzo</span>
            <span class="text-xs font-bold text-blue-500 flex items-center gap-1">READ ARTICLE →</span>
          </div>
        </div>
      </div>

    </div>

 
   
   <!-- fillter -->


<div class="w-full banner">
        
        <div class="w-full bg-primary/10 py-6 rounded-2xl ">
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




    

  </main>
</template>

<style scoped>
/* Optional: Fine-tune the masonry break behavior */
.break-inside-avoid {
  -webkit-column-break-inside: avoid;
  page-break-inside: avoid;
  break-inside: avoid;
}
</style>