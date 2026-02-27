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
        <span>Culture</span>
        <div class="w-10 h-0.5 bg-primary"></div>
        <span>Resume/CV</span>
        <div class="w-10 h-0.5 bg-primary"></div>
        <span>Review</span>
      </div>
      <h2 class="font-black text-4xl">Culture & Values</h2>
      <p>Match with the right company</p>
      <div class="bg-secondary p-10 rounded-lg flex flex-col gap-12 w-[1000px]">
        <div class="flex flex-col gap-6">
          <div class="flex gap-4 items-center">
            <form class="flex flex-col gap-2 w-full">
              <label>Company size</label>
              <select class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
                <option>Startup</option>
                <option>Medium</option>
                <option>Enterprise</option>
              </select>
            </form>
            <form class="flex flex-col gap-2 w-full">
              <label>Work environment</label>
              <select class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
                <option>Fast-paced</option>
                <option>Flexible</option>
                <option>Structured</option>
              </select>
            </form>
          </div>
          <div class="flex gap-4 items-center">
            <form class="flex flex-col gap-2 w-full">
              <label>Team style</label>
              <select class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
                <option>Collaborative</option>
                <option>Independent</option>
                <option>Mixed</option>
              </select>
            </form>
            <form class="flex flex-col gap-2 w-full">
              <label>Communication</label>
              <select class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
                <option>Async first</option>
                <option>Meetings heavy</option>
                <option>Balanced</option>
              </select>
            </form>
          </div>
          <div class="flex flex-col gap-2 w-full">
            <label>Company values (multi)</label>
            <div class="flex items-center gap-10">
              <label class="flex gap-2 items-center">
                <input type="checkbox" class="w-4 h-4">
                Innovation
              </label>
              <label class="flex gap-2 items-center">
                <input type="checkbox" class="w-4 h-4">
                Diversity
              </label>
              <label class="flex gap-2 items-center">
                <input type="checkbox" class="w-4 h-4">
                Work-life balance
              </label>
              <label class="flex gap-2 items-center">
                <input type="checkbox" class="w-4 h-4">
                Career growth
              </label>
            </div>
          </div>
          <label>Work-life balance importance</label>
          <div class="flex items-center gap-4">
            <input type="range" min="0" max="100" value="85" class="w-full">
            85%
          </div>
        </div>
        <div class="flex items-center gap-4">
          <baseBtn name="Back" @click="goBack"/>
          <baseBtn name="Next" to="candidate-profile-4"/>
        </div>
      </div>
    </div>
  </div>
</template>
