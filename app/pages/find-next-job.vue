<template>



<!-- banner and search -->

<section
  class="relative h-[500px] flex items-center justify-center text-white banner">

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

      <button
        class="bg-primary text-black px-8 py-3 rounded-xl hover:bg-secondary transition text-[#000000]"
      >
        Search
      </button>

    </div>

  </div>
</section>

</div>

</section>


<!-- job list -->

<section class="w-[1820px] mx-auto">
 <div class="ax-w-6xl mx-auto px-8">
  <BR></BR><BR></BR>
  <h1 class="text-2xl text-prima">Trending startup jobs</h1><BR></BR>
  <div class="mb-2 flex flex-col justify-between border-b border-gray-400 py-3 transition-all duration-0 ease-linear md:flex-row">
    <div class="flex flex-block">
      <div class="w-12 ">
        <img src="https://i.pinimg.com/736x/a1/2b/11/a12b1163bcad6c21c514486b9c0ab87b.jpg" alt="">
        <div class="ml-4 flex-1">
          <div class="mb-1">
            
          </div>
        </div>

      </div>
           <h2 class="text-xl ml-4 nb-1 flex-block">Software Engineer, II</h2> 
          
           
           
    </div>
    
  </div>

 </div>
</section>



</template>