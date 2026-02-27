<template>



<!-- banner and search -->

<section
  class=" h-[500px] flex items-center justify-center text-white w-full banner">


  <img
    src="https://images.unsplash.com/photo-1521737604893-d14cc237f11d"
    class="absolute inset-0 w-full h-full object-cover"/>


  <div class="absolute inset-0 bg-black/60"></div>


  <div class="relative z-10 text-center px-4 max-w-4xl w-full">

    <h1 class="text-4xl md:text-6xl font-bold mb-6">
      Find Your Next Job
    </h1>

    <p class="text-lg md:text-xl mb-8 text-gray-200">
      Discover thousands of opportunities from top companies
    </p>


  <!-- select job and location     -->

<section class=" py-12 mx-auto">
  <div class="max-w-6xl mx-auto px-4">


    <div class="flex flex-col md:flex-row items-center gap-3  shadow-lg rounded-2xl p-3 bg-white/8">


      <div class="flex-1">
        <select class="w-full border rounded-xl px-4 py-2 outline-none  text-[#ffffff] bg-secondary" >
          <option>All Locations</option>
          <option>Phnom Penh</option>
          <option>Siem Reap</option>
          <option>Battambang</option>
          <option>Prey Veng</option>
          <option>Kompong spue</option>
        </select>
      </div>

      <div class="flex-1">
        <select class="w-full border rounded-xl px-4 py-2 outline-none text-[#ffffff] bg-secondary">
          <option>All Categories</option>
          <option>IT</option>
          <option>Full stack Engineer</option>
          <option>Frontend Engineer</option>
          <option>Backend Engineer</option>
          <option>Designer</option>
        
        </select>
      </div>

         <NuxtLink
            to="/skills"
            class="inline-flex items-center justify-center rounded-xl bg-white px-8 py-4 text-base font-bold text-black transition-all hover:bg-secondary hover:ring-4 hover:ring-blue-100 active:scale-95"
          >
            Search
           
          </NuxtLink>

    </div>

  </div>
</section>

</div>

</section>


<!-- job list -->

<section class="mx-auto max-w-5xl px-4 py-12 ">

  <div class="max-w-4xl  p-4 mx-auto ml-5 ">
    <BR></BR><BR></BR>
    <h1 class="text-2xl font-bold text-white mb-4">Trending startup jobs</h1>
    <div class="group flex flex-col md:flex-row items-start md:items-center justify-between p-6 bg-white/8 border border-gray-200 rounded-3xl hover:border-primary hover:shadow-[0_20px_50px_rgba(8,_112,_184,_0.07)] transition-all duration-300 gap-6">
      
      <div class="flex items-center gap-5">
        <div class="w-16 h-16 shrink-0 p-1 bg-gray-50 rounded-2xl border border-gray-100 group-hover:scale-105 transition-transform">
          <img 
            alt="Logo" 
            src="https://photos.wellfound.com/startups/i/8534738-b6be765945a32f867f9399a49b7de89c-medium_jpg.jpg" 
            class="w-full h-full object-contain rounded-xl"
          >
        </div>

        <div class="space-y-1">
          <h3 class="text-xl font-bold text-white group-hover:text-primary transition-colors tracking-tight">
            Email Growth & v-for Infrastructure Lead
          </h3>
          <div class="flex flex-wrap items-center gap-2 text-sm">
            <span class="font-semibold text-gray-700">Edit on the Spot</span>
            <span class="text-gray-300">•</span>
            <span class="text-gray-500">Remote only • Everywhere</span>
            <span class="hidden md:inline text-gray-300">•</span>
            <span class="px-2 py-0.5 text-emerald-700 font-bold rounded-md  border-emerald-100">
              $25k – $30k
            </span>
            <span class="text-xs text-gray-400 font-medium">yesterday</span>
          </div>
        </div>
      </div>

      <div class="flex items-center gap-3 mt-6 md:mt-0 w-full md:w-auto">
       
         <NuxtLink
            to="/sign-up"
            class="flex-1 md:flex-none px-6 py-2.5 text-sm font-bold text-gray-700 bg-gray-50 border border-gray-200 rounded-xl hover:bg-white hover:border-gray-400 transition-all active:scale-95"
          >
            Save
         
          </NuxtLink>
         <NuxtLink
            to="/apply"
            class="flex-1 md:flex-none px-8 py-2.5 text-sm font-bold text-white bg-black rounded-xl hover:bg-secondary shadow-lg shadow-black/5 transition-all active:scale-95"
          >
            Apply
         
          </NuxtLink>

        <!-- <button class="flex-1 md:flex-none px-8 py-2.5 text-sm font-bold text-white bg-black rounded-xl hover:bg-secondary shadow-lg shadow-black/5 transition-all active:scale-95">
          Apply
        </button> -->
      </div>

    </div>
       <BR></BR>
      <div class="group flex flex-col md:flex-row items-start md:items-center justify-between p-6 bg-white/8 border border-gray-200 rounded-3xl hover:border-primary hover:shadow-[0_20px_50px_rgba(8,_112,_184,_0.07)] transition-all duration-300 gap-6">
      
      <div class="flex items-center gap-5">
        <div class="w-16 h-16 shrink-0 p-1 bg-gray-50 rounded-2xl border border-gray-100 group-hover:scale-105 transition-transform">
          <img 
            alt="Logo" 
            src="https://i.pinimg.com/736x/9f/06/dd/9f06dd53afe2c8723e992ec1373e83c1.jpg" 
            class="w-full h-full object-contain rounded-xl"
          >
        </div>

        <div class="space-y-1">
          <h3 class="text-xl font-bold text-white group-hover:text-primary transition-colors tracking-tight">
            Senior Full-Stack Engineer
          </h3>
          <div class="flex flex-wrap items-center gap-2 text-sm">
            <span class="font-semibold text-gray-700">Edit on the Spot</span>
            <span class="text-gray-300">•</span>
            <span class="text-gray-500">Remote only • Everywhere</span>
            <span class="hidden md:inline text-gray-300">•</span>
            <span class="px-2 py-0.5 text-emerald-700 font-bold rounded-md  border-emerald-100">
              $25k – $30k
            </span>
            <span class="text-xs text-gray-400 font-medium">yesterday</span>
          </div>
        </div>
      </div>

      <div class="flex items-center gap-3 mt-6 md:mt-0 w-full md:w-auto">
           <NuxtLink
            to="/sign-up"
            class="flex-1 md:flex-none px-6 py-2.5 text-sm font-bold text-gray-700 bg-gray-50 border border-gray-200 rounded-xl hover:bg-white hover:border-gray-400 transition-all active:scale-95"
          >
            Save
         
          </NuxtLink>
         <NuxtLink
            to="/apply"
            class="flex-1 md:flex-none px-8 py-2.5 text-sm font-bold text-white bg-black rounded-xl hover:bg-secondary shadow-lg shadow-black/5 transition-all active:scale-95"
          >
            Apply
         
          </NuxtLink>
      </div>

    </div>

    <BR></BR>

      <div class="group flex flex-col md:flex-row items-start md:items-center justify-between p-6 bg-white/8 border border-gray-200 rounded-3xl hover:border-primary hover:shadow-[0_20px_50px_rgba(8,_112,_184,_0.07)] transition-all duration-300 gap-6">
      
      <div class="flex items-center gap-5">
        <div class="w-16 h-16 shrink-0 p-1 bg-gray-50 rounded-2xl border border-gray-100 group-hover:scale-105 transition-transform">
          <img 
            alt="Logo" 
            src="https://i.pinimg.com/1200x/72/ae/95/72ae95fb1ff1bc72ca1d4aeef05c2bcb.jpg" 
            class="w-full h-full object-contain rounded-xl"
          >
        </div>

        <div class="space-y-1">
          <h3 class="text-xl font-bold text-white group-hover:text-primary transition-colors tracking-tight">
            Tech Lead, Infrastructure
          </h3>
          <div class="flex flex-wrap items-center gap-2 text-sm">
            <span class="font-semibold text-gray-700">Edit on the Spot</span>
            <span class="text-gray-300">•</span>
            <span class="text-gray-500">Remote only • Everywhere</span>
            <span class="hidden md:inline text-gray-300">•</span>
            <span class="px-2 py-0.5 text-emerald-700 font-bold rounded-md  border-emerald-100">
              $2k – $60k
            </span>
            <span class="text-xs text-gray-400 font-medium">Today</span>
          </div>
        </div>
      </div>

      <div class="flex items-center gap-3 mt-6 md:mt-0 w-full md:w-auto">
           <NuxtLink
            to="/sign-up"
            class="flex-1 md:flex-none px-6 py-2.5 text-sm font-bold text-gray-700 bg-gray-50 border border-gray-200 rounded-xl hover:bg-white hover:border-gray-400 transition-all active:scale-95"
          >
            Save
         
          </NuxtLink>
         <NuxtLink
            to="/apply"
            class="flex-1 md:flex-none px-8 py-2.5 text-sm font-bold text-white bg-black rounded-xl hover:bg-secondary shadow-lg shadow-black/5 transition-all active:scale-95"
          >
            Apply
         
          </NuxtLink>
      </div>

    </div>

    
    <BR></BR>

      <div class="group flex flex-col md:flex-row items-start md:items-center justify-between p-6 bg-white/8 border border-gray-200 rounded-3xl hover:border-primary hover:shadow-[0_20px_50px_rgba(8,_112,_184,_0.07)] transition-all duration-300 gap-6">
      
      <div class="flex items-center gap-5">
        <div class="w-16 h-16 shrink-0 p-1 bg-gray-50 rounded-2xl border border-gray-100 group-hover:scale-105 transition-transform">
          <img 
            alt="Logo" 
            src="https://i.pinimg.com/1200x/31/a4/6f/31a46f35dbbc2c6a3cd541ff9ef311cf.jpg" 
            class="w-full h-full object-contain rounded-xl"
          >
        </div>

        <div class="space-y-1">
          <h3 class="text-xl font-bold text-white group-hover:text-primary transition-colors tracking-tight">
            Go-to-Market Architect, Revenue Operations

          </h3>
          <div class="flex flex-wrap items-center gap-2 text-sm">
            <span class="font-semibold text-gray-700">Edit on the Spot</span>
            <span class="text-gray-300">•</span>
            <span class="text-gray-500">Remote only • Everywhere</span>
            <span class="hidden md:inline text-gray-300">•</span>
            <span class="px-2 py-0.5 text-emerald-700 font-bold rounded-md  border-emerald-100">
              $25k – $30k
            </span>
            <span class="text-xs text-gray-400 font-medium">Today</span>
          </div>
        </div>
      </div>

      <div class="flex items-center gap-3 mt-6 md:mt-0 w-full md:w-auto">
           <NuxtLink
            to="/sign-up"
            class="flex-1 md:flex-none px-6 py-2.5 text-sm font-bold text-gray-700 bg-gray-50 border border-gray-200 rounded-xl hover:bg-white hover:border-gray-400 transition-all active:scale-95"
          >
            Save
         
          </NuxtLink>
         <NuxtLink
            to="/apply"
            class="flex-1 md:flex-none px-8 py-2.5 text-sm font-bold text-white bg-black rounded-xl hover:bg-secondary shadow-lg shadow-black/5 transition-all active:scale-95"
          >
            Apply
         
          </NuxtLink>
      </div>

    </div>

    <BR></BR>

      <div class="group flex flex-col md:flex-row items-start md:items-center justify-between p-6 bg-white/8 border border-gray-200 rounded-3xl hover:border-primary hover:shadow-[0_20px_50px_rgba(8,_112,_184,_0.07)] transition-all duration-300 gap-6">
      
      <div class="flex items-center gap-5">
        <div class="w-16 h-16 shrink-0 p-1 bg-gray-50 rounded-2xl border border-gray-100 group-hover:scale-105 transition-transform">
          <img 
            alt="Logo" 
            src="https://i.pinimg.com/1200x/6f/2c/38/6f2c38e24433f388d66cb38acfd3eb26.jpg" 
            class="w-full h-full object-contain rounded-xl"
          >
        </div>

        <div class="space-y-1">
          <h3 class="text-xl font-bold text-white group-hover:text-primary transition-colors tracking-tight">
            
              Design Engineer
          </h3>
          <div class="flex flex-wrap items-center gap-2 text-sm">
            <span class="font-semibold text-gray-700">Edit on the Spot</span>
            <span class="text-gray-300">•</span>
            <span class="text-gray-500">Remote only • Everywhere</span>
            <span class="hidden md:inline text-gray-300">•</span>
            <span class="px-2 py-0.5 text-emerald-700 font-bold rounded-md  border-emerald-100">
              $25k – $30k
            </span>
            <span class="text-xs text-gray-400 font-medium">Today</span>
          </div>
        </div>
      </div>

      <div class="flex items-center gap-3 mt-6 md:mt-0 w-full md:w-auto">
           <NuxtLink
            to="/sign-up"
            class="flex-1 md:flex-none px-6 py-2.5 text-sm font-bold text-gray-700 bg-gray-50 border border-gray-200 rounded-xl hover:bg-white hover:border-gray-400 transition-all active:scale-95"
          >
            Save
         
          </NuxtLink>
         <NuxtLink
            to="/apply"
            class="flex-1 md:flex-none px-8 py-2.5 text-sm font-bold text-white bg-black rounded-xl hover:bg-secondary shadow-lg shadow-black/5 transition-all active:scale-95"
          >
            Apply
         
          </NuxtLink>
      </div>

    </div>
    
  </div>
  

</section>



<section class="mx-auto max-w-5xl px-4 py-12 ">

  <div class="max-w-4xl  p-4 mx-auto ml-5 ">
    <BR></BR><BR></BR>
    <h1 class="text-2xl font-bold text-white mb-4">Product jobs</h1>
    <div class="group flex flex-col md:flex-row items-start md:items-center justify-between p-6 bg-white/8 border border-gray-200 rounded-3xl hover:border-primary hover:shadow-[0_20px_50px_rgba(8,_112,_184,_0.07)] transition-all duration-300 gap-6">
      
      <div class="flex items-center gap-5">
        <div class="w-16 h-16 shrink-0 p-1 bg-gray-50 rounded-2xl border border-gray-100 group-hover:scale-105 transition-transform">
          <img 
            alt="Logo" 
            src="https://i.pinimg.com/736x/58/ef/63/58ef632598b45641b1364a1271f11a7a.jpg" 
            class="w-full h-full object-contain rounded-xl"
          >
        </div>

        <div class="space-y-1">
          <h3 class="text-xl font-bold text-white group-hover:text-primary transition-colors tracking-tight">
            Email Growth & Outreach Infrastructure Lead
          </h3>
          <div class="flex flex-wrap items-center gap-2 text-sm">
            <span class="font-semibold text-gray-700">Edit on the Spot</span>
            <span class="text-gray-300">•</span>
            <span class="text-gray-500">Remote only • Everywhere</span>
            <span class="hidden md:inline text-gray-300">•</span>
            <span class="px-2 py-0.5 text-emerald-700 font-bold rounded-md  border-emerald-100">
              $25k – $30k
            </span>
            <span class="text-xs text-gray-400 font-medium">yesterday</span>
          </div>
        </div>
      </div>

      <div class="flex items-center gap-3 mt-6 md:mt-0 w-full md:w-auto">
           <NuxtLink
            to="/sign-up"
            class="flex-1 md:flex-none px-6 py-2.5 text-sm font-bold text-gray-700 bg-gray-50 border border-gray-200 rounded-xl hover:bg-white hover:border-gray-400 transition-all active:scale-95"
          >
            Save
         
          </NuxtLink>
         <NuxtLink
            to="/apply"
            class="flex-1 md:flex-none px-8 py-2.5 text-sm font-bold text-white bg-black rounded-xl hover:bg-secondary shadow-lg shadow-black/5 transition-all active:scale-95"
          >
            Apply
         
          </NuxtLink>
      </div>

    </div>
       <BR></BR>
      <div class="group flex flex-col md:flex-row items-start md:items-center justify-between p-6 bg-white/8 border border-gray-200 rounded-3xl hover:border-primary hover:shadow-[0_20px_50px_rgba(8,_112,_184,_0.07)] transition-all duration-300 gap-6">
      
      <div class="flex items-center gap-5">
        <div class="w-16 h-16 shrink-0 p-1 bg-gray-50 rounded-2xl border border-gray-100 group-hover:scale-105 transition-transform">
          <img 
            alt="Logo" 
            src="https://i.pinimg.com/736x/e3/63/b1/e363b1539a5db236765dc787a08d9526.jpg" 
            class="w-full h-full object-contain rounded-xl"
          >
        </div>

        <div class="space-y-1">
          <h3 class="text-xl font-bold text-white group-hover:text-primary transition-colors tracking-tight">
            Senior Full-Stack Engineer
          </h3>
          <div class="flex flex-wrap items-center gap-2 text-sm">
            <span class="font-semibold text-gray-700">Edit on the Spot</span>
            <span class="text-gray-300">•</span>
            <span class="text-gray-500">Remote only • Everywhere</span>
            <span class="hidden md:inline text-gray-300">•</span>
            <span class="px-2 py-0.5 text-emerald-700 font-bold rounded-md  border-emerald-100">
              $25k – $30k
            </span>
            <span class="text-xs text-gray-400 font-medium">yesterday</span>
          </div>
        </div>
      </div>

      <div class="flex items-center gap-3 mt-6 md:mt-0 w-full md:w-auto">
          <NuxtLink
            to="/sign-up"
            class="flex-1 md:flex-none px-6 py-2.5 text-sm font-bold text-gray-700 bg-gray-50 border border-gray-200 rounded-xl hover:bg-white hover:border-gray-400 transition-all active:scale-95"
          >
            Save
         
          </NuxtLink>
         <NuxtLink
            to="/apply"
            class="flex-1 md:flex-none px-8 py-2.5 text-sm font-bold text-white bg-black rounded-xl hover:bg-secondary shadow-lg shadow-black/5 transition-all active:scale-95"
          >
            Apply
         
          </NuxtLink>
      </div>

    </div>

    <BR></BR>

      <div class="group flex flex-col md:flex-row items-start md:items-center justify-between p-6 bg-white/8 border border-gray-200 rounded-3xl hover:border-primary hover:shadow-[0_20px_50px_rgba(8,_112,_184,_0.07)] transition-all duration-300 gap-6">
      
      <div class="flex items-center gap-5">
        <div class="w-16 h-16 shrink-0 p-1 bg-gray-50 rounded-2xl border border-gray-100 group-hover:scale-105 transition-transform">
          <img 
            alt="Logo" 
            src="https://i.pinimg.com/1200x/06/51/78/065178b8bc3c102bb219017f76c4c08f.jpg" 
            class="w-full h-full object-contain rounded-xl"
          >
        </div>

        <div class="space-y-1">
          <h3 class="text-xl font-bold text-white group-hover:text-primary transition-colors tracking-tight">
            Frontix
          </h3>
          <div class="flex flex-wrap items-center gap-2 text-sm">
            <span class="font-semibold text-gray-700">Edit on the Spot</span>
            <span class="text-gray-300">•</span>
            <span class="text-gray-500">Remote only • Everywhere</span>
            <span class="hidden md:inline text-gray-300">•</span>
            <span class="px-2 py-0.5 text-emerald-700 font-bold rounded-md  border-emerald-100">
              $2k – $60k
            </span>
            <span class="text-xs text-gray-400 font-medium">Today</span>
          </div>
        </div>
      </div>

      <div class="flex items-center gap-3 mt-6 md:mt-0 w-full md:w-auto">
          <NuxtLink
            to="/sign-up"
            class="flex-1 md:flex-none px-6 py-2.5 text-sm font-bold text-gray-700 bg-gray-50 border border-gray-200 rounded-xl hover:bg-white hover:border-gray-400 transition-all active:scale-95"
          >
            Save
         
          </NuxtLink>
         <NuxtLink
            to="/apply"
            class="flex-1 md:flex-none px-8 py-2.5 text-sm font-bold text-white bg-black rounded-xl hover:bg-secondary shadow-lg shadow-black/5 transition-all active:scale-95"
          >
            Apply
         
          </NuxtLink>
      </div>

    </div>

    
    <BR></BR>

      <div class="group flex flex-col md:flex-row items-start md:items-center justify-between p-6 bg-white/8 border border-gray-200 rounded-3xl hover:border-primary hover:shadow-[0_20px_50px_rgba(8,_112,_184,_0.07)] transition-all duration-300 gap-6">
      
      <div class="flex items-center gap-5">
        <div class="w-16 h-16 shrink-0 p-1 bg-gray-50 rounded-2xl border border-gray-100 group-hover:scale-105 transition-transform">
          <img 
            alt="Logo" 
            src="https://i.pinimg.com/1200x/38/2e/60/382e60253fd798b407e0de484a0f7b8b.jpg" 
            class="w-full h-full object-contain rounded-xl"
          >
        </div>

        <div class="space-y-1">
          <h3 class="text-xl font-bold text-white group-hover:text-primary transition-colors tracking-tight">
            Go-to-Market Architect, Revenue Operations

          </h3>
          <div class="flex flex-wrap items-center gap-2 text-sm">
            <span class="font-semibold text-gray-700">Edit on the Spot</span>
            <span class="text-gray-300">•</span>
            <span class="text-gray-500">Remote only • Everywhere</span>
            <span class="hidden md:inline text-gray-300">•</span>
            <span class="px-2 py-0.5 text-emerald-700 font-bold rounded-md  border-emerald-100">
              $25k – $30k
            </span>
            <span class="text-xs text-gray-400 font-medium">Today</span>
          </div>
        </div>
      </div>

      <div class="flex items-center gap-3 mt-6 md:mt-0 w-full md:w-auto">
         <NuxtLink
            to="/sign-up"
            class="flex-1 md:flex-none px-6 py-2.5 text-sm font-bold text-gray-700 bg-gray-50 border border-gray-200 rounded-xl hover:bg-white hover:border-gray-400 transition-all active:scale-95"
          >
            Save
         
          </NuxtLink>
         <NuxtLink
            to="/apply"
            class="flex-1 md:flex-none px-8 py-2.5 text-sm font-bold text-white bg-black rounded-xl hover:bg-secondary shadow-lg shadow-black/5 transition-all active:scale-95"
          >
            Apply
         
          </NuxtLink>
      </div>

    </div>

    <BR></BR>

      <div class="group flex flex-col md:flex-row items-start md:items-center justify-between p-6 bg-white/8 border border-gray-200 rounded-3xl hover:border-primary hover:shadow-[0_20px_50px_rgba(8,_112,_184,_0.07)] transition-all duration-300 gap-6">
      
      <div class="flex items-center gap-5">
        <div class="w-16 h-16 shrink-0 p-1 bg-gray-50 rounded-2xl border border-gray-100 group-hover:scale-105 transition-transform">
          <img 
            alt="Logo" 
            src="https://i.pinimg.com/1200x/5a/01/80/5a0180169cf5c10d6ae9a4f883938f81.jpg" 
            class="w-full h-full object-contain rounded-xl"
          >
        </div>

        <div class="space-y-1">
          <h3 class="text-xl font-bold text-white group-hover:text-primary transition-colors tracking-tight">
            
              Design Engineer
          </h3>
          <div class="flex flex-wrap items-center gap-2 text-sm">
            <span class="font-semibold text-gray-700">Edit on the Spot</span>
            <span class="text-gray-300">•</span>
            <span class="text-gray-500">Remote only • Everywhere</span>
            <span class="hidden md:inline text-gray-300">•</span>
            <span class="px-2 py-0.5 text-emerald-700 font-bold rounded-md  border-emerald-100">
              $25k – $30k
            </span>
            <span class="text-xs text-gray-400 font-medium">Today</span>
          </div>
        </div>
      </div>

      <div class="flex items-center gap-3 mt-6 md:mt-0 w-full md:w-auto">
          <NuxtLink
            to="/sign-up"
            class="flex-1 md:flex-none px-6 py-2.5 text-sm font-bold text-gray-700 bg-gray-50 border border-gray-200 rounded-xl hover:bg-white hover:border-gray-400 transition-all active:scale-95"
          >
            Save
         
          </NuxtLink>
         <NuxtLink
            to="/apply"
            class="flex-1 md:flex-none px-8 py-2.5 text-sm font-bold text-white bg-black rounded-xl hover:bg-secondary shadow-lg shadow-black/5 transition-all active:scale-95"
          >
            Apply
         
          </NuxtLink>
      </div>

    </div>
    
  </div>
  

</section>




<!-- cta -->

  <section class="mx-auto max-w-5xl px-4 py-12">
    <div class="group relative overflow-hidden rounded-3xl bg-white border border-gray-100 shadow-xl transition-all hover:shadow-2xl md:flex">
      
      <div class="flex items-center justify-center bg-yellow-400 p-8 md:w-1/3">
        <img 
          src="/assets/images/find next hire 3.webp" 
          alt="Job Search Illustration" 
          class="w-40 transform transition-transform duration-500 group-hover:scale-110 md:w-48"
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
            to="/sign-up"
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



<!-- 
fillter -->

 
<div class="w-full banner">
        
        <div class="w-full bg-accent/10 py-6 ">
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


// import axios from 'axios'


// const config = {
//   headers: {
//     Authorization: 'Bearer 26753a48380e4da090f8b327f97bdb263af4f0476e49516a894a7d30c5f7d94f9e8d168198abbfd7c018116fca3ebd942ea5ed9559e284ee1576bdb711db5c58142a22b240a34d8df4f0752616f40a95efffcb3301f55bea80e14804d27bd76602315765c62391189c8c614120f19ad3f9bf9b5e9c1a5e7ac541231273dc5ba5'


//   }
// };


// const dataFetch = await axios.get('http://localhost:1337/api/recruiters',config);
// const jobPostingdatas = dataFetch.data.data;
// console.log(jobPostingdatas);


</script>



