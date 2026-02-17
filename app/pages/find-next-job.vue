<template>

<section
  class="relative h-[500px] flex items-center justify-center text-white">

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


<section class=" py-12 mx-auto">
  <div class="max-w-6xl mx-auto px-4">


    <div class="flex flex-col md:flex-row items-center gap-3  shadow-lg rounded-2xl p-3 bg-white/8">

      <div class="flex items-center flex-1 border rounded-xl px-4 py-2">
        <svg class="w-5 h-5 text-[#333333] mr-2" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
          <path d="M21 21l-4.3-4.3m1.8-5.2a7 7 0 11-14 0 7 7 0 0114 0z"/>
        </svg>

        <input
          type="text"
          placeholder="Job title or keyword"
          class="w-full outline-none bg-transparent"
        />
      </div>

      <div class="flex-1 ">
        <select class="w-full border rounded-xl px-4 py-2 outline-none ">
          <option>All Locations</option>
          <option>Phnom Penh</option>
          <option>Siem Reap</option>
          <option>Battambang</option>
        </select>
      </div>

      <div class="flex-1">
        <select class="w-full border rounded-xl px-4 py-2 outline-none">
          <option>All Categories</option>
          <option>IT</option>
          <option>Marketing</option>
          <option>Finance</option>
        </select>
      </div>

   
      <button
        class="bg-primary text-[#333333] px-8 py-3 rounded-xl hover:bg-secondary transition"
      >
        Search
      </button>

    </div>
  </div>
</section>


</div>

</section>



</template>