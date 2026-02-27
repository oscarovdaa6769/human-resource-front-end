<template>

  <main class="max-w-7xl mx-auto px-6 py-12 antialiased selection:bg-indigo-100">
    
    <header class="text-center mb-16">
      <h1 class="text-5xl font-[900] tracking-tight mb-8 text-slate-900">Discover</h1>
      <nav class="inline-flex p-1 bg-slate-100 rounded-full border border-slate-200">
                <NuxtLink to="/discover" class="px-8 py-2.5 rounded-full text-sm font-bold text-slate-600 hover:text-black transition-all">All</NuxtLink>
                <NuxtLink to="/startups" class="px-8 py-2.5 rounded-full text-sm font-bold text-[#000000] hover:text-secondary transition-all bg-secondary">Startups</NuxtLink>
                <NuxtLink to="/blog" class="px-8 py-2.5 rounded-full text-sm font-bold text-slate-600 hover:text-black transition-all">Blog</NuxtLink>
        
      </nav>
    </header>


    <!-- STARTUP -->
<section class="max-w-7xl mx-auto px-6 pb-16">

  <h3 class="text-2xl font-semibold mb-6">Popular startups</h3>

  <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6">

    <!-- Card 1 -->
    <div class="bg-white/8 rounded-xl p-6 shadow hover:shadow-lg transition">

      <img 
        src="https://i.pinimg.com/1200x/8c/65/b9/8c65b957b081443c80350e68df132119.jpg"
        class="w-14 h-14 rounded-lg mb-4"
      />

      <h4 class="font-semibold text-lg">Working towards your dreams is hard. Not reaching them is harder.</h4>
      <p class="text-gray-500 text-sm mt-2">Online payments for internet businesses</p>
      <p class="text-xs text-gray-400 mt-2">Remote</p>

      <button class="mt-2 border-2 border-primary text-primary rounded px-4 py-2 hover:border-accent hover:bg-accent hover:text-[#fff] transition-all duration-300 ease-in-out">
        Follow
      </button>
    </div>


    <!-- Card 2 -->
    <div class="bg-white/8 rounded-xl p-6 shadow hover:shadow-lg transition">

      <img 
        src="https://i.pinimg.com/1200x/b8/28/1d/b8281d3f3eb0cefa7a539f2c4ccf9b84.jpg"
        class="w-14 h-14 rounded-lg mb-4"
      />

      <h4 class="font-semibold text-lg">creating a distinct, memorable identity, likely for a tech-focused, </h4>
      <p class="text-gray-500 text-sm mt-2">All-in-one workspace for notes & docs</p>
      <p class="text-xs text-gray-400 mt-2">San Francisco</p>

      <button class="mt-2 border-2 border-primary text-primary rounded px-4 py-2 hover:border-accent hover:bg-accent hover:text-[#fff] transition-all duration-300 ease-in-out">
        Follow
      </button>
    </div>


    <!-- Card 3 -->
    <div class="bg-white/8 rounded-xl p-6 shadow hover:shadow-lg transition">

      <img 
        src="https://i.pinimg.com/1200x/46/83/ff/4683ffca76bc1b5f94004d6046f1181d.jpg"
        class="w-14 h-14 rounded-lg mb-4"
      />

      <h4 class="font-semibold text-lg">A routine cash pickup turns into a deadly pursuit</h4>
      <p class="text-gray-500 text-sm mt-2">Online design made simple</p>
      <p class="text-xs text-gray-400 mt-2">Remote</p>
       <button class="mt-2 border-2 border-primary text-primary rounded px-4 py-2 hover:border-accent hover:bg-accent hover:text-[#fff] transition-all duration-300 ease-in-out">
        Follow
      </button>
    </div>


    <!-- Card 4 -->
    <div class="bg-white/8 rounded-xl p-6 shadow hover:shadow-lg transition">

      <img 
        src="https://i.pinimg.com/1200x/d0/d5/1a/d0d51a9891442e8aeb425b537d5fd664.jpg"
        class="w-14 h-14 rounded-lg mb-4"
      />

      <h4 class="font-semibold text-lg">We use cookies to personalise content and ads, to provide social </h4>
      <p class="text-gray-500 text-sm mt-2">Collaborative interface design tool</p>
      <p class="text-xs text-gray-400 mt-2">Remote</p>

         <button class="mt-2 border-2 border-primary text-primary rounded px-4 py-2 hover:border-accent hover:bg-accent hover:text-[#fff] transition-all duration-300 ease-in-out">
        Follow
      </button>

    </div>


    <!-- Card 5 -->
    <div class="bg-white/8 rounded-xl p-6 shadow hover:shadow-lg transition">

      <img 
        src="https://i.pinimg.com/736x/b8/52/49/b852490ea1d90977b6ef23a3d0a93c70.jpg"
        class="w-14 h-14 rounded-lg mb-4"
      />

      <h4 class="font-semibold text-lg">The world's most loved .NET and game dev IDE</h4>
      <p class="text-gray-500 text-sm mt-2">Build and run online stores</p>
      <p class="text-xs text-gray-400 mt-2">Canada</p>

        <button class="mt-2 border-2 border-primary text-primary rounded px-4 py-2 hover:border-accent hover:bg-accent hover:text-[#fff] transition-all duration-300 ease-in-out">
        Follow
      </button>
    </div>


    <!-- Card 6 -->
    <div class="bg-white/8 rounded-xl p-6 shadow hover:shadow-lg transition">

      <img 
        src="https://i.pinimg.com/1200x/ef/23/f7/ef23f7ac15dd7e2f8c545649503f1c71.jpg"
        class="w-14 h-14 rounded-lg mb-4"
      />

      <h4 class="font-semibold text-lg">Innovating today for a smarter tomorrow</h4>
      <p class="text-gray-500 text-sm mt-2">Spreadsheet meets database</p>
      <p class="text-xs text-gray-400 mt-2">New York</p>

      <button class="mt-2 border-2 border-primary text-primary rounded px-4 py-2 hover:border-accent hover:bg-accent hover:text-[#fff] transition-all duration-300 ease-in-out">
        Follow
      </button>

    </div>

  </div>
</section>


<!-- 
fillter -->

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



    
  </main>
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

