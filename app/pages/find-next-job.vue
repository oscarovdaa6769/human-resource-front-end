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


<div class="px-2 py-2 flex items-center border rounded-2xl overflow-hidden w-full max-w-2xl mx-auto">
<select
  class="px-4 py-3 rounded-sm border  text-[#ffffff] bg-secondary"
>
  <option value="">Job little</option>
  <option>Frontend</option>
  <option>Backend</option>
  <option>Design</option>
  <option>Marketing</option>

</select>






  <input 
    type="select" 
    placeholder="" 
    class="flex-1 px-4 py-2 outline-none"
  />
  <button class="bg-primary text-[#333333] px-6 py-2 transition-all duration-300 ease-in-out hover:bg-accent rounded-xl ">
    Search
  </button>
</div>








 

  </div>
</section>


</template>