<script setup lang="ts">

</script>

<template>
  <div class="w-full banner">
    <div class="container flex flex-col items-center gap-8 py-15">
      <div class="flex border-1 items-center gap-4 border-primary rounded-full py-5 px-10">
        <span>Profile</span>
        <div class="w-10 h-0.5 bg-primary"></div>
        <span>Preferences</span>
        <div class="w-10 h-0.5 bg-primary"></div>
        <span>Culture</span>
        <div class="w-10 h-0.5 bg-primary"></div>
        <span>Resume/CV</span>
        <div class="w-10 h-0.5 bg-primary"></div>
        <span>Done</span>
      </div>
      <h2 class="font-black text-4xl">Create your profile</h2>
      <p>Apply privately to thousands of tech companies & startups with one profile.</p>
      <div class="bg-highlight p-10 rounded-lg flex flex-col gap-4 w-[800px]">
        <div class="grid grid-cols-[5%_95%]">
          <Icon name="material-symbols:asterisk-rounded" class="text-primary"/>
          <div class="flex flex-col gap-4">
            <h4 class="font-black text-xl">Where are you based?</h4>
            <p class="text-[#eee]">Tip: You can choose a city, state, or country</p>
            <div class="border border-[#eee] focus:ring focus:ring-primary focus:border-primary outline-none transition rounded-full flex items-center py-2 pl-6 pr-3">
              <input type="search" class="focus:outline-none focus:border-none focus:ring-none w-full" placeholder="Search for a different location">
              <Icon name="material-symbols:search-rounded" class="text-2xl hover:text-primary"/>
            </div>
          </div>
        </div>
        <div class="grid grid-cols-[5%_95%]">
          <Icon name="material-symbols:asterisk-rounded" class="text-primary"/>
          <div class="flex flex-col gap-4">
            <h4 class="font-black text-xl">What best describes your current role?</h4>
            <select class="border border-[#eee] focus:border-primary py-3 px-6 rounded-full">
              <option>Select a role</option>
              <option>Front end developer</option>
              <option>Back end developer</option>
              <option>Full Stack</option>
            </select>
          </div>
        </div>
        <div class="grid grid-cols-[5%_95%]">
          <Icon name="material-symbols:asterisk-rounded" class="text-primary"/>
          <div class="flex flex-col gap-4">
            <h4 class="font-black text-xl">How many years of experience do you have in your current role?</h4>
            <select class="border border-[#eee] focus:border-primary py-3 px-6 rounded-full">
              <option>Select years of experience</option>
              <option>less than 1 year</option>
              <option>1-5 years</option>
              <option>6-10 years</option>
            </select>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
