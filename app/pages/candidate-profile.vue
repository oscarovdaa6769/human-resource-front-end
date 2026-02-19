<script setup lang="ts">
import baseBtn from '~/components/baseBtn.vue';
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
        <span>Done</span>
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
      </div>
    </div>
  </div>
</template>
