<template>
  <div class="w-full banner">
    <div class="container flex flex-col items-center gap-12 py-15">
      <div class="flex border-1 items-center gap-4 border-primary rounded-full py-5 px-10">
        <span class="text-primary">Profile</span>
        <div class="w-10 h-0.5 bg-primary"></div>
        <span class="text-primary">Preferences</span>
        <div class="w-10 h-0.5 bg-primary"></div>
        <span class="text-primary">Culture</span>
        <div class="w-10 h-0.5 bg-primary"></div>
        <span class="text-primary">Resume/CV</span>
        <div class="w-10 h-0.5 bg-primary"></div>
        <span>Review</span>
      </div>
      <h2 class="font-black text-4xl">Review & submit</h2>
      <p>Please check your information</p>
      <div class="bg-secondary p-10 rounded-lg flex flex-col gap-12 w-[1000px]">
        <div class="bg-[#07222d] border border-[#eee] flex flex-col gap-4 p-6 rounded-2xl">
          <div class="flex items-center justify-between">
            <div class="flex items-center gap-2 font-black">
              <Icon name="mdi:card-account-details" class="text-2xl"/> Profile
            </div>
            <NuxtLink class="text-primary hover:text-accent font-medium cursor-pointer">Edit</NuxtLink>
          </div>
          <div class="grid grid-cols-[40%_60%]">
            <div class="flex flex-col gap-2">
              <span class="text-accent">Name</span>
              <span class="text-accent">Email</span>
              <span class="text-accent">Location</span>
              <span class="text-accent">Headline</span>
            </div>
            <div class="flex flex-col gap-2">
              <span>Det Oudomveasna</span>
              <span>oudomveasnadet@gmail.com</span>
              <span>Phnom Penh, Cambodia</span>
              <span class="flex items-center">Frontend Developer <icon name="lucide:dot"/> 7+ years</span>
            </div>
          </div>
        </div>
        <div class="bg-[#07222d] border border-[#eee] flex flex-col gap-4 p-6 rounded-2xl">
          <div class="flex items-center justify-between">
            <div class="flex items-center gap-2 font-black">
              <Icon name="material-symbols:card-travel-rounded" class="text-2xl"/> Preferences
            </div>
            <NuxtLink class="text-primary hover:text-accent font-medium cursor-pointer">Edit</NuxtLink>
          </div>
          <div class="grid grid-cols-[40%_60%]">
            <div class="flex flex-col gap-2">
              <span class="text-accent">Desired role</span>
              <span class="text-accent">Employment</span>
              <span class="text-accent">Salary</span>
              <span class="text-accent">Relocate</span>
            </div>
            <div class="flex flex-col gap-2">
              <span>Senior Frontend</span>
              <span>Full‑time, remote</span>
              <span>$70k–90k</span>
              <span>No</span>
            </div>
          </div>
        </div>
        <div class="bg-[#07222d] border border-[#eee] flex flex-col gap-4 p-6 rounded-2xl">
          <div class="flex items-center justify-between">
            <div class="flex items-center gap-2 font-black">
              <Icon name="mdi:handshake" class="text-2xl"/> Culture
            </div>
            <NuxtLink class="text-primary hover:text-accent font-medium cursor-pointer">Edit</NuxtLink>
          </div>
          <div class="grid grid-cols-[40%_60%]">
            <div class="flex flex-col gap-2">
              <span class="text-accent">Company size</span>
              <span class="text-accent">Values</span>
              <span class="text-accent">Team</span>
            </div>
            <div class="flex flex-col gap-2">
              <span>Startup / Medium</span>
              <span>Innovation, Diversity, WLB</span>
              <span>Collaborative, async</span>
            </div>
          </div>
        </div>
        <div class="bg-[#07222d] border border-[#eee] flex flex-col gap-4 p-6 rounded-2xl">
          <div class="flex items-center justify-between">
            <div class="flex items-center gap-2 font-black">
              <Icon name="mdi:file-document" class="text-2xl"/> CV & skills
            </div>
            <NuxtLink class="text-primary hover:text-accent font-medium cursor-pointer">Edit</NuxtLink>
          </div>
          <div class="grid grid-cols-[40%_60%]">
            <div class="flex flex-col gap-2">
              <span class="text-accent">CV</span>
              <span class="text-accent">Skills</span>
            </div>
            <div class="flex flex-col gap-2">
              <span>Oudomveasna_Det_CV.pdf</span>
              <span>Vue (exp), Nuxt (intermediate), Tailwind</span>
            </div>
          </div>
        </div>
        <div class="flex items-center gap-4">
          <baseBtn name="Back" @click="goBack"/>
          <baseBtn name="Submit Profile"/>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import baseBtn from '~/components/baseBtn.vue';

const router = useRouter()

const goBack = () => {
  router.back()
}
</script>
