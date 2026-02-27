<script setup lang="ts">
import baseBtn from '~/components/baseBtn.vue';

const router = useRouter()

const goBack = () => {
  router.back()
}
</script>

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
        <span>Resume/CV</span>
        <div class="w-10 h-0.5 bg-primary"></div>
        <span>Review</span>
      </div>
      <h2 class="font-black text-4xl">Resume & skills</h2>
      <p>Experience & files</p>
      <div class="bg-secondary p-10 rounded-lg flex flex-col gap-12 w-[1000px]">
        <div class="flex flex-col gap-6">
          CV upload (PDF/DOC)
          <div class="flex gap-4 items-center">
            <div class="flex gap-2 items-center bg-[#7ae2cf52] border border-[#eee] rounded-full px-4 py-2 self-start">
              <Icon name="mdi:file-pdf" class="text-lg"/> Upload CV
            </div>
            <span class="text-gray-600">Oudomveasna_Det_CV.pdf</span>
          </div>
        </div>
        <div class="flex flex-col gap-6">
          Skills (tag input + level bonus)
          <div class="flex gap-4 items-center">
            <div class="flex gap-2 items-center bg-[#7ae2cf52] border border-[#eee] rounded-full px-4 py-2 self-start">
              Vue <Icon name="iconamoon:sign-times-circle-fill" class="text-lg"/>
            </div>
            <div class="flex gap-2 items-center bg-[#7ae2cf52] border border-[#eee] rounded-full px-4 py-2 self-start">
              Nuxt <Icon name="iconamoon:sign-times-circle-fill" class="text-lg"/>
            </div>
            <div class="flex gap-2 items-center bg-[#7ae2cf52] border border-[#eee] rounded-full px-4 py-2 self-start">
              Tailwind <Icon name="iconamoon:sign-times-circle-fill" class="text-lg"/>
            </div>
            <div class="flex gap-2 items-center bg-[#7ae2cf52] border border-[#eee] rounded-full px-4 py-2 self-start">
              Strapi <Icon name="iconamoon:sign-times-circle-fill" class="text-lg"/>
            </div>
            <div class="flex gap-2 items-center bg-[#7ae2cf52] border border-[#eee] rounded-full px-4 py-2 self-start">
              <Icon name="line-md:plus-circle-filled" class="text-lg"/> Add
            </div>
          </div>
        </div>
        <div class="flex items-center gap-4 w-full">
          <div class="flex flex-col gap-2 w-full">
            Vue level:
            <form class="flex flex-col gap-2 w-full">
              <select class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
                <option>Beginner</option>
                <option>Intermediate</option>
                <option>Expert</option>
              </select>
            </form>
          </div>
          <div class="flex flex-col gap-2 w-full">
            Nuxt level:
            <form class="flex flex-col gap-2 w-full">
              <select class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
                <option>Beginner</option>
                <option>Intermediate</option>
                <option>Expert</option>
              </select>
            </form>
          </div>
        </div>
        <div class="flex flex-col gap-4 w-full">
          Work experience
          <div class="bg-[#07222d] border border-[#eee] flex flex-col gap-4 p-6 rounded-2xl">
            <input type="text" placeholder="Job title" class="px-4 py-3 h-13 border border-[#eee] rounded-xl bg-secondary">
            <input type="text" placeholder="Company" class="px-4 py-3 h-13 border border-[#eee] rounded-xl bg-secondary">
            <div class="flex items-center gap-4">
              <input type="text" placeholder="Start" class="px-4 py-3 h-13 border border-[#eee] rounded-xl bg-secondary">
              <input type="text" placeholder="End" class="px-4 py-3 h-13 border border-[#eee] rounded-xl bg-secondary">
            </div>
            <textarea class="px-4 py-3 h-13 border border-[#eee] rounded-xl bg-secondary h-20"></textarea>
          </div>
          <div class="flex gap-2 items-center bg-[#7ae2cf52] border border-[#eee] rounded-full px-4 py-2 self-start">
            <Icon name="line-md:plus-circle-filled" class="text-lg"/> Add another
          </div>
        </div>
        <div class="flex flex-col gap-4 w-full">
          Education
          <div class="bg-[#07222d] border border-[#eee] flex flex-col gap-4 p-6 rounded-2xl">
            <input type="text" placeholder="School" class="px-4 py-3 h-13 border border-[#eee] rounded-xl bg-secondary">
            <input type="text" placeholder="Degree" class="px-4 py-3 h-13 border border-[#eee] rounded-xl bg-secondary">
            <input type="text" placeholder="Year" class="px-4 py-3 h-13 border border-[#eee] rounded-xl bg-secondary w-40">
          </div>
          <div class="flex gap-2 items-center bg-[#7ae2cf52] border border-[#eee] rounded-full px-4 py-2 self-start">
            <Icon name="line-md:plus-circle-filled" class="text-lg"/> Add another
          </div>
        </div>
        <div class="flex flex-col gap-4 w-full">
          Languages:
          <div class="bg-[#07222d] border border-[#eee] flex flex-col gap-4 p-6 rounded-2xl">
            <div class="flex items-center gap-4">
              <div class="flex flex-col gap-2 w-full">
                English:
                <form class="flex flex-col gap-2 w-full">
                  <select class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
                    <option>Fluent</option>
                  </select>
                </form>
              </div>
              <div class="flex flex-col gap-2 w-full">
                Khmer:
                <form class="flex flex-col gap-2 w-full">
                  <select class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
                    <option>Native</option>
                  </select>
                </form>
              </div>
              <div class="flex flex-col gap-2 w-full">
                Other:
                <input type="text" placeholder="e.g. French" class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
              </div>
            </div>
          </div>
        </div>
        <div class="flex items-center gap-4">
          <baseBtn name="Back" @click="goBack"/>
          <baseBtn name="Next" to="candidate-profile-5"/>
        </div>
      </div>
    </div>
  </div>
</template>
