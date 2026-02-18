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
</script>

<template>
  <main class="max-w-7xl mx-auto px-6 py-12 antialiased selection:bg-indigo-100">
    
    <header class="text-center mb-16">
      <h1 class="text-5xl font-[900] tracking-tight mb-8 text-slate-900">Discover</h1>
      <nav class="inline-flex p-1 bg-slate-100 rounded-full border border-slate-200">
        <NuxtLink to="/" class="px-8 py-2.5 rounded-full text-sm font-bold bg-black text-white shadow-lg">All</NuxtLink>
        <NuxtLink to="/startups" class="px-8 py-2.5 rounded-full text-sm font-bold text-slate-600 hover:text-black transition-all">Startups</NuxtLink>
        <NuxtLink to="/blog" class="px-8 py-2.5 rounded-full text-sm font-bold text-slate-600 hover:text-black transition-all">Blog</NuxtLink>
        <NuxtLink to="/feature-list" class="px-8 py-2.5 rounded-full text-sm font-bold text-slate-600 hover:text-black transition-all">feature List</NuxtLink>
      </nav>
    </header>

    <section class="relative overflow-hidden  p-10 mb-12 text-white">
      <div class="absolute top-0 right-0 w-2/3 h-full bg-[#E9357B]/2 to-transparent"></div>
      
      <div class="relative z-10 flex flex-col lg:flex-row items-center justify-between gap-10">
        <div class="flex flex-col items-center lg:items-start gap-1 lg:border-r lg:border-white/10 lg:pr-12">
          <span class="text-3xl font-black italic tracking-tighter">WELLFOUND</span>
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

      <div class="break-inside-avoid grid grid-cols-2 gap-4">
        <div v-for="cat in categories" :key="cat.name"
          class="bg-white/10 p-6 rounded-[2.2rem] border border-slate-100 hover:bg-secondary/10 hover:border-indigo-300 hover:shadow-lg transition-all cursor-pointer group">
          <div class="text-3xl mb-4 group-hover:scale-110 transition-transform duration-300">{{ cat.emoji }}</div>
          <h4 class="font-black text-lg text-">{{ cat.name }}</h4>
          <p class="text-sm text-[#ffffff] font-bold uppercase tracking-tighter">{{ cat.count }} startups</p>
        </div>
      </div>

      <div class="break-inside-avoid grid grid-cols-2 gap-4">
      
      </div>

      <div class="break-inside-avoid bg-white/10 border border-slate-200 rounded-[2rem] p-6 hover:shadow-xl transition-all flex items-center gap-5 cursor-pointer hover:scale-[1.02]">
        <div class="w-16 h-16 bg-slate-900 rounded-2xl flex-shrink-0 flex items-center justify-center font-black text-xl text-[#ffffff]">FN</div>
        <div class="flex-1">
          <h4 class="font-bold text-lg">FiscalNote</h4>
          <p class="text-sm text-[#ffffff] line-clamp-1 font-medium italic">Mitigating risks and managing issues.</p>
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