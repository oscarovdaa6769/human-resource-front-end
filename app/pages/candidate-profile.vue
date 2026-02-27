<script setup lang="ts">
import baseBtn from '~/components/baseBtn.vue';

const otDg = "nh mix dg"

console.log(otDg);

</script>

<template>
  <div class="w-full banner">
    <div class="container flex flex-col items-center gap-12 py-15">
      <div class="flex border-1 items-center gap-4 border-primary rounded-full py-5 px-10">
        <span>Profile</span>
        <div class="w-10 h-0.5 bg-primary"></div>
        <span>Preferences</span>
        <div class="w-10 h-0.5 bg-primary"></div>
        <span>Culture</span>
        <div class="w-10 h-0.5 bg-primary"></div>
        <span>Resume/CV</span>
        <div class="w-10 h-0.5 bg-primary"></div>
        <span>Review</span>
      </div>
      <h2 class="font-black text-4xl">Create your profile</h2>
      <p>Apply privately to thousands of tech companies & startups with one profile.</p>
      <div class="bg-secondary p-10 rounded-lg flex flex-col gap-12 w-[1000px]">
        <div class="flex items-center gap-4">
          <div class="w-[70px] h-[70px] border-2 border-primary border-dashed rounded-full flex items-center justify-center ">
            <Icon name="material-symbols:camera-enhance-outline-rounded" class="text-3xl text-primary"/>
          </div>
          <button class="flex items-center gap-2 text-[#000] hover:text-[#fff] border-2 border-primary bg-primary hover:bg-accent hover:border-accent rounded-full px-4 py-2 transition-all duration-300 ease-in-out">
            <Icon name="material-symbols:upload" class="text-xl"/>upload photo
          </button>
        </div>
        <div class="flex flex-col gap-6">
          <div class="flex gap-4 items-center">
            <form class="flex flex-col gap-2 w-full">
              <label>First Name</label>
              <input type="text" placeholder="Det" class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
            </form>
            <form class="flex flex-col gap-2 w-full">
              <label>Last Name</label>
              <input type="text" placeholder="Oudomveasna" class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
            </form>
          </div>
          <div class="flex gap-4 items-center">
            <form class="flex flex-col gap-2 w-full">
              <label>Email</label>
              <input type="email" placeholder="oudomveasnadet@gmail.com" class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
            </form>
            <form class="flex flex-col gap-2 w-full">
              <label>Phone</label>
              <input type="tel" required placeholder="+855 12 345 678" class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
            </form>
          </div>
          <div class="flex gap-4 items-center">
            <form class="flex flex-col gap-2 w-full">
              <label>Date of birth</label>
              <input type="date" placeholder="mm/dd/yyyy" class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
            </form>
            <form class="flex flex-col gap-2 w-full">
              <label>Gender (optional)</label>
              <select class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
                <option>Choose your gender</option>
                <option>Male</option>
                <option>Female</option>
                <option>Prefer not to say</option>
              </select>
            </form>
          </div>
          <form class="flex flex-col gap-2 w-full">
            <label>Current location</label>
            <input type="text" placeholder="Phnom Penh, Cambodia" class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
          </form>
          <form class="flex flex-col gap-2 w-full">
            <label>Professional headline</label>
            <input type="text" placeholder="Frontend Developer" class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
          </form>
          <div class="flex gap-4 items-center">
            <form class="flex flex-col gap-2 w-full">
              <label>Years of experience</label>
              <select class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
                <option>0-1</option>
                <option>2-3</option>
                <option>4-6</option>
                <option>7+</option>
              </select>
            </form>
            <form class="flex flex-col gap-2 w-full">
              <label>Portfolio / Website</label>
              <input type="text" placeholder="Oudomveasna-Portfolio.com" class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
            </form>
          </div>
          <form class="flex flex-col gap-2 w-full">
            <label>LinkedIn URL</label>
            <input type="text" placeholder="linkedin.com/in/oudomveasna" class="px-4 py-3 h-13 border border[#eee] rounded-xl">
          </form>
          <label>Short bio</label>
          <textarea placeholder="Bio" class="px-4 py-3 border border-[#eee] rounded-xl"></textarea>
        </div>
        <baseBtn name="Next" to="/candidate-profile-2"/>
      </div>
    </div>
  </div>
</template>
