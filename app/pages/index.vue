
<template>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css">
  <section class="relative w-full min-h-[500px] bg-gray-900">
    <img
      src="https://i.pinimg.com/1200x/97/24/93/972493565630ab9a985f2a5156dddb8f.jpg"
      alt="Team working together"
      class="absolute inset-0 w-full h-full object-cover opacity-40"
    />
    <div class="relative z-10 max-w-7xl mx-auto px-6 py-24 flex items-center">
      <div class="max-w-xl text-white">


        <h1 class="text-4xl md:text-5xl font-bold leading-tight mb-6 mt-30 text-primary">
         Job-Opprtunties
        </h1>

        <p class="text-gray-100 mb-8 ">
          I build secure and intuitive HR web solutions that streamline
           recruitment, employee records, payroll, attendance, and performance
           management. These solutions reduce manual work, improve data accuracy,
            and enhance the overall employee experience while helping HR teams
            operate more efficiently.
        </p>

        <div class="flex gap-4">
           <NuxtLink  to="/candidate-profile"
            class="bg-primary hover:bg-accent text-[#000] hover:text-[#fff] px-6 py-3 rounded-full font-medium transition"> Send Cv →
            </NuxtLink>

        </div>
      </div>

    </div>

  </section>
  <section class="py-40 flex items-center bg-secondary  justify-center px-4">
    <div class="text-center max-w-3xl">
      <h1 class="text-3xl sm:text-4xl  font-bold text-white mb-10">
        Where startups and job seekers connect
      </h1>
      <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
        <NuxtLink  to="/find-next-job"
          class="bg-primary text-secondary px-8 py-4 rounded-full text-lg font-medium hover:bg-accent hover:text-white transition"
        >
          Find your next hire
         </NuxtLink>
        <NuxtLink  to="/find-next-hire"
          class="border-2 border-primary text-primary px-8 py-4 rounded-full text-lg font-medium hover:bg-accent transition hover:text-white"
        >
          Find your next job
        </NuxtLink>
      </div>
    </div>
  </section>

  <div class=" text-blue-900 text-white py-40 px-4 ">
    <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-8 text-center">

      <div class="flex flex-col items-center">
        <div class="text-6xl md:text-7xl font-bold mb-3  text-primary">8M+</div>
        <div class="text-xl font-medium text-gray-200">Matches Made</div>
      </div>

      <div class="flex flex-col items-center">
        <div class="text-6xl md:text-7xl font-bold mb-3 text-primary" >150K+</div>
        <div class="text-xl font-medium text-gray-200">Tech Jobs</div>
      </div>

      <div class="flex flex-col items-center">
        <div class="text-6xl md:text-7xl font-bold mb-3  text-primary">10M+</div>
        <div class="text-xl font-medium text-gray-200">Startup Ready Candidates</div>
      </div>

    </div>
  </div>

  <section class="w-full flix ">
    <div class="max-w-full  grid grid-cols-1 md:grid-cols-2">

      <div class="px-8 md:px-16">
        <p class="text-2xl font-semibold text-white mb-3 pt-9">Got talent?</p>
        <h2 class="text-4xl  text-primary font-bold mb-12">
          Why job seekers love us
        </h2>

        <div class="space-y-10">
          <div class="flex gap-5">
            <div class="w-15 h-12 flex items-center justify-center rounded-full bg-primary-100 text-accent">
            <i class="fa-solid fa-arrow-trend-up"></i>

            </div>
            <p class="text-white">
              Connect directly with founders at top startups – no third party recruiters allowed.
            </p>
          </div>

          <div class="flex gap-5">
            <div class="w-17 h-12 flex items-center justify-center rounded-full bg-primary-100  text-accent">
            <i class="fa-solid fa-book-open"></i>
            </div>
            <p class="text-white">
              Everything you need to know, all upfront. View salary, stock options, and more before applying.
            </p>
          </div>

          <div class="flex gap-5">
            <div class="w-17 h-12 flex items-center justify-center rounded-full bg-primary-100  text-accent">
            <i class="fa-solid fa-arrows-down-to-people"></i>

            </div>
            <p class="text-white">
              Say goodbye to cover letters – your profile is all you need. One click to apply and you're done.
            </p>
          </div>

          <div class="flex gap-5">
            <div class="w-13 h-12 flex items-center justify-center rounded-full bg-primary-100 text-accent">
            <i class="fa-solid fa-star"></i>

            </div>
            <p class="text-white">
              Unique jobs at startups and tech companies you can’t find anywhere else.
            </p>
          </div>
        </div>

        <div class="mt-12 flex gap-4 pb-8" >
          <NuxtLink  to="/Learn more"class="px-6 py-3  border-2 border-primary hover:bg-accent hover:text-secondary rounded-lg font-medium ">
            Learn more
          </NuxtLink>
          <NuxtLink  to="/candidate-profile"class="px-6 py-3  bg-primary hover:bg-accent  text-[#000] hover:text-[#fff] rounded-lg font-medium">
            Sign up
          </NuxtLink>
        </div>
      </div>
      <div class="px-8 md:px-16 bg-highlight">
        <p class="text-2xl font-semibold text-white mb-3 pt-9">Need talent?</p>
        <h2 class="text-4xl  text-primary font-bold mb-12">
          Why recruiters love us
        </h2>

        <div class="space-y-10">
          <div class="flex gap-5">
            <div class="w-15 h-12 flex items-center justify-center rounded-full bg-primary-100 text-accent">
            <i class="fa-solid fa-arrow-trend-up"></i>

            </div>
            <p class="text-white">
              Everything you need to know, all upfront. View salary, stock options, and more before applying.
            </p>
          </div>

          <div class="flex gap-5">
            <div class="w-17 h-12 flex items-center justify-center rounded-full bg-primary-100  text-accent">
            <i class="fa-solid fa-book-open"></i>
            </div>
            <p class="text-white">
              Everything you need to know, all upfront. View salary, stock options, and more before applying.
            </p>
          </div>

          <div class="flex gap-5">
            <div class="w-17 h-12 flex items-center justify-center rounded-full bg-primary-100  text-accent">
            <i class="fa-solid fa-arrows-down-to-people"></i>

            </div>
            <p class="text-white">
              A free applicant tracking system, or free integration with any ATS you may already use.
            </p>
          </div>

          <div class="flex gap-5">
            <div class="w-13 h-12 flex items-center justify-center rounded-full bg-primary-100 text-accent">
            <i class="fa-solid fa-star"></i>

            </div>
            <p class="text-white">
              Unique jobs at startups and tech companies you can’t find anywhere else.
            </p>
          </div>
        </div>

        <div class="mt-12 flex gap-4 pb-8" >
            <NuxtLink  to="/Learn more"class="px-6 py-3  border-2 border-primary hover:bg-accent hover:text-secondary rounded-lg font-medium ">
            Learn more
          </NuxtLink>
          <NuxtLink  to="/candidate-profile"class="px-6 py-3  bg-primary hover:bg-accent  text-[#000] hover:text-[#fff] rounded-lg font-medium">
            Sign up
          </NuxtLink>
        </div>
      </div>
    </div>

    <div class="w-full bg-secondary">
    <div class="container grid grid-cols-2 items-center gap-4">
      <div class="p-15">
        <img src="/assets/images/find next hire 5.webp" alt="World of Talent">
      </div>
      <div class="flex flex-col gap-4">
        <span class="uppercase font-black text-primary flex items-center gap-2">wellfound:ai <Icon name="icon-park-twotone:add-music" class="text-2xl"/> autopilot</span>
        <h2 class="font-black text-6xl">Stop scrolling, start hiring</h2>
        <p>We’ll review hundreds of profiles each week and reach out to the best fits with hyper-personalized templates. When interested candidates respond, we’ll handle the back-and-forth. All that’s needed from you is one-click to approve and they’ll be instantly booked on your calendar. <NuxtLink to="/learn-more" class="underline hover:text-primary">Learn more</NuxtLink></p>
        <NuxtLink to="/discover" class="font-semibold text-primary flex items-center gap-2 group">Schedule a demo <Icon name="mi:arrow-right" class="transition-transform duration-300 group-hover:translate-x-2"/></NuxtLink>
      </div>
    </div>
  </div>
  </section>

  <div class="text-blue-900 py-16 px-4">
    <div class="max-w-7xl mx-auto">

      <div class="flex justify-between items-center mb-10">
        <div>
          <h2 class="text-2xl font-semibold text-white mb-1">Quotes</h2>
          <h1 class="text-4xl font-bold text-primary">From our users</h1>
        </div>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">

        <div class="bg-secondary p-8 rounded-2xl flex flex-col gap-4  ">
         <div class="w-14 h-14 flex items-center justify-center rounded-full bg-primary-100  text-accent">
          <img
              src="https://i.pinimg.com/736x/18/5f/08/185f08b480520518e9407d20a035df73.jpg"
              alt="User avatar"
              class="w-14 h-14 flex items-center justify-center rounded-full"
            />
         </div>

          <p class="text-lg text-white leading-relaxed">
            I got my tech job on Wellfound 4 years ago and I'm still happy! Pays well, great culture, and unlimited PTO.
          </p>
        </div>

        <div class="bg-secondary p-8 rounded-2xl flex flex-col gap-4">
          <div class="w-14 h-14 flex items-center justify-center rounded-full bg-primary-100  text-accent">
          <img
              src="https://i.pinimg.com/736x/18/5f/08/185f08b480520518e9407d20a035df73.jpg"
              alt="User avatar"
              class="w-14 h-14 flex items-center justify-center rounded-full"
            />
         </div>
          <p class="text-lg text-white leading-relaxed">
            I love Wellfound. I got my current job at a startup entirely through the site last year - it's super easy to use and I love the UI.
          </p>
        </div>

        <div class="bg-secondary p-8 rounded-2xl flex flex-col gap-4">
          <div class="w-14 h-14 flex items-center justify-center rounded-full bg-primary-100  text-accent">
          <img
              src="https://i.pinimg.com/736x/18/5f/08/185f08b480520518e9407d20a035df73.jpg"
              alt="User avatar"
              class="w-14 h-14 flex items-center justify-center rounded-full"
            />
         </div>
          <p class="text-lg text-white leading-relaxed">
            I can't imagine my day to day without this platform. Life would be a lot more difficult.
          </p>
        </div>

      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mt-8">

        <div class="bg-secondary p-8 rounded-2xl flex flex-col gap-4 ">
         <div class="w-14 h-14 flex items-center justify-center rounded-full bg-primary-100  text-accent">
          <img
              src="https://i.pinimg.com/736x/18/5f/08/185f08b480520518e9407d20a035df73.jpg"
              alt="User avatar"
              class="w-14 h-14 flex items-center justify-center rounded-full"
            />
         </div>

          <p class="text-lg text-white leading-relaxed">
            I got my tech job on Wellfound 4 years ago and I'm still happy! Pays well, great culture, and unlimited PTO.
          </p>
        </div>

        <div class="bg-secondary p-8 rounded-2xl flex flex-col gap-4">
          <div class="w-14 h-14 flex items-center justify-center rounded-full bg-primary-100  text-accent">
          <img
              src="https://i.pinimg.com/736x/18/5f/08/185f08b480520518e9407d20a035df73.jpg"
              alt="User avatar"
              class="w-14 h-14 flex items-center justify-center rounded-full"
            />
         </div>
          <p class="text-lg text-white leading-relaxed">
            I love Wellfound. I got my current job at a startup entirely through the site last year - it's super easy to use and I love the UI.
          </p>
        </div>

        <div class="bg-secondary p-8 rounded-2xl flex flex-col gap-4">
          <div class="w-14 h-14 flex items-center justify-center rounded-full bg-primary-100  text-accent">
          <img
              src="https://i.pinimg.com/736x/18/5f/08/185f08b480520518e9407d20a035df73.jpg"
              alt="User avatar"
              class="w-14 h-14 flex items-center justify-center rounded-full"
            />
         </div>
          <p class="text-lg text-white leading-relaxed">
            I can't imagine my day to day without this platform. Life would be a lot more difficult.
          </p>
        </div>

      </div>
    </div>
  </div>



  <div class="p-6 md:p-10 text-blue-900 font-sans text-gray-900">

    <div class="bg-gray-950 text-white p-8 md:p-12 rounded-2xl flex flex-col md:flex-row items-center justify-between gap-8 mb-16">
      <div class="flex-shrink-0 w-64 h-64 bg-white rounded-3xl flex flex-col justify-center items-center text-gray-950 p-4 shadow-xl transform rotate-0 md:-rotate-6">
        <img src="https://wellfound.com/logo.svg" alt="Wellfound" class="h-6 mb-2" />
        <div class="flex items-end gap-1">
          <span class="text-6xl font-extrabold tracking-tighter text-red-600">10</span>
          <span class="text-2xl font-bold pb-1 text-gray-700">OF</span>
          <span class="text-6xl font-extrabold tracking-tighter text-red-600">10</span>
        </div>
        <div class="flex items-center gap-2 mt-1">
          <div class="h-0.5 w-8 bg-gray-300"></div>
          <span class="text-4xl font-black tracking-tight">IN 2025</span>
          <div class="h-0.5 w-8 bg-gray-300"></div>
        </div>
      </div>

      <div class="flex-grow text-center md:text-left">
        <h2 class="text-3xl md:text-4xl font-bold mb-4 tracking-tight text-primary">
          Our top picks for 2025 are here!
        </h2>
        <p class="text-gray-300 mb-8 max-w-2xl text-lg leading-relaxed">
          Wellfound has selected 10 startups across 10 trending industries that
          should be on your radar in 2025. See what teams our community is most
          excited about in the year ahead!
        </p>

      </div>
    </div>

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

            <div
                v-for="(menu, index) in menus"
                :key="index"
                class="relative"
            >

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
