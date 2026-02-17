<template>
  <div class="w-full banner">
    <div class="container pt-10 pb-10 flex flex-col items-center gap-10">
      <p class="uppercase text-primary font-black">from pre-seed to post-IPO</p>
      <h2 class="text-[#fff] text-7xl font-black text-center">The all-in-one platform to find, connect & hire your team</h2>
      <p class="uppercase text-primary font-black">Get started in 10 minutes or less</p>
      <div class="flex items-center gap-4">
        <NuxtLink to="/sign-up" class="text-[#000] hover:text-[#fff] border-2 border-primary bg-primary hover:bg-accent hover:border-accent rounded-full px-4 py-2 transition-all duration-300 ease-in-out w-[200px] text-center">Sign up now</NuxtLink>
        <NuxtLink to="/schedule" class=" border-2 border-primary text-primary rounded-full px-4 py-2 hover:border-accent hover:bg-accent hover:text-[#fff] transition-all duration-300 ease-in-out w-[200px] text-center ">Schedule a demo</NuxtLink>
      </div>
      <div class="flex items-center justify-between w-full px-15">
        <div class="flex flex-col items-center">
          <h2 class="font-black text-7xl text-primary">10M+</h2>
          <p class="font-semibold">Startup-ready talent</p>
        </div>
        <div class="w-[2px] h-[150px] bg-primary"></div>
        <div class="flex flex-col items-center">
          <h2 class="font-black text-7xl text-primary">25k+</h2>
          <p class="font-semibold">Companies</p>
        </div>
        <div class="w-[2px] h-[150px] bg-primary"></div>
        <div class="flex flex-col items-center">
          <h2 class="font-black text-7xl text-primary">100k+</h2>
          <p class="font-semibold">Hires made</p>
        </div>
      </div>
    </div>
  </div>
  <div class="w-full bg-secondary">
    <div class="container grid grid-cols-2 items-center gap-4">
      <div class="p-15">
        <img src="/assets/images/find next hire 1.webp" alt="World of Talent">
      </div>
      <div class="flex flex-col gap-4">
        <span class="uppercase font-black text-primary">a world of talent at your fingertips</span>
        <h2 class="font-black text-6xl">Instant access to a talent pool of 10M+</h2>
        <p>Access the largest talent pool of startup-minded job seekers in seconds. Our diverse community comes to Wellfound from across the globe to find their next job, spanning a variety of industries, skill levels, and backgrounds. No matter what you’re looking for in your next hire, you’ll find it here.</p>
        <NuxtLink to="/discover" class="font-semibold text-primary flex items-center gap-2 group">Discover our talent <Icon name="mi:arrow-right" class="transition-transform duration-300 group-hover:translate-x-2"/></NuxtLink>
      </div>
    </div>
  </div>
  <div class="w-full">
    <div class="container grid grid-cols-2 items-center gap-4">
      <div class="flex flex-col gap-4">
        <span class="uppercase font-black text-primary">A job board built for connection</span>
        <h2 class="font-black text-6xl">High exposure, great connection</h2>
        <p>Post an infinite amount of jobs (for free) and instantly reach a massive pool of responsive and engaged talent. Our job listings provide a comprehensive look into the job, work style, team culture & more, so you can lay it all out there and find the perfect fit.</p>
        <NuxtLink to="/discover" class="font-semibold text-primary flex items-center gap-2 group">Post a job for free <Icon name="mi:arrow-right" class="transition-transform duration-300 group-hover:translate-x-2"/></NuxtLink>
      </div>
      <div class="p-15">
        <img src="/assets/images/find next hire 2.webp" alt="World of Talent">
      </div>
    </div>
  </div>
  <div class="w-full bg-secondary">
    <div class="container grid grid-cols-2 items-center gap-4">
      <div class="p-15">
        <img src="/assets/images/find next hire 3.webp" alt="World of Talent">
      </div>
      <div class="flex flex-col gap-4">
        <span class="uppercase font-black text-primary">Branding at its best</span>
        <h2 class="font-black text-6xl">Make a great first impression</h2>
        <p>Our Company Profiles are designed to tell your story, showcase your uniqueness, and establish your brand. Profiles highlight startup-focused signals, but are dynamically useful as your team grows. Profiles are easily shareable so you can connect with millions of Wellfound users, plus a world of others across your own platforms.</p>
        <NuxtLink to="/discover" class="font-semibold text-primary flex items-center gap-2 group">Create your company profile <Icon name="mi:arrow-right" class="transition-transform duration-300 group-hover:translate-x-2"/></NuxtLink>
      </div>
    </div>
  </div>
  <div class="w-full">
    <div class="container grid grid-cols-2 items-center gap-4">
      <div class="flex flex-col gap-4">
        <span class="uppercase font-black text-primary">visual workflow, efficient pipeline</span>
        <h2 class="font-black text-6xl">A 100% free, lightweight ATS</h2>
        <p>Save time & hire faster with our all-in-one, streamlined tracking system. Take just <span class="font-black">10 minutes to set up</span> and have centralized recruiting data that consolidates email correspondence, internal notes, and interview scorecards into one easy-to-manage dashboard. Sync with your existing tools for an easy & efficient hiring process.</p>
        <NuxtLink to="/discover" class="font-semibold text-primary flex items-center gap-2 group">Build your pipeline <Icon name="mi:arrow-right" class="transition-transform duration-300 group-hover:translate-x-2"/></NuxtLink>
      </div>
      <div class="p-15">
        <img src="/assets/images/find next hire 4.webp" alt="World of Talent">
      </div>
    </div>
  </div>
  <div class="w-full bg-highlight">
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
  <div class="w-full">
    <div class="container py-15">
      <div class="flex flex-col gap-8">
        <span class="uppercase font-black text-primary flex items-center gap-2">Find the right plan for you</span>
        <h2 class="font-black text-6xl w-[50%]">Flexible solutions for every stage of your hiring journey</h2>
        <p>From free job posting and inbound applicants to advanced, all-in-one solutions that take care of everything for you — we provide every level of support your team may need, no matter the scale.</p>
        <p>Looking for something a bit more specific? We're happy to create a custom solution fit for your team.</p>
        <p class="flex items-center gap-2">To find you the best option, we just need a few details <Icon name="mi:arrow-right"/></p>
        <div class="rounded-lg bg-highlihgt shadow-[0_0_15px_primary] shadow-primary p-25">
          <div class="grid grid-cols-[40%_60%] border-1 border-accent rounded-sm">
            <div class="flex flex-col items-center">
              <div class="p-15 ">
                <img src="/assets/images/logo brand.png" alt="People-Resolution">
              </div>
              <div class="px-15 flex flex-col gap-4">
                <h2>Schedule call with Wellfound</h2>
                <p>Please tell us a bit about you so we can route you to the right person.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
