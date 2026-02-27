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
        <span>Preferences</span>
        <div class="w-10 h-0.5 bg-primary"></div>
        <span>Culture</span>
        <div class="w-10 h-0.5 bg-primary"></div>
        <span>Resume/CV</span>
        <div class="w-10 h-0.5 bg-primary"></div>
        <span>Review</span>
      </div>
      <h2 class="font-black text-4xl">Preferences</h2>
      <p>What kind of job you want</p>
      <div class="bg-secondary p-10 rounded-lg flex flex-col gap-12 w-[1000px]">
        <div class="flex flex-col gap-6">
          <form class="flex flex-col gap-2 w-full">
            <label>Desired job title</label>
            <input type="text" placeholder="Senior Frontend Developer" class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
          </form>
          <form class="flex flex-col gap-2 w-full">
            <label>Category</label>
            <select class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
              <option>Frontend Dev</option>
              <option>Full Stack</option>
            </select>
          </form>
          <div class="flex items-center justify-between w-full">
            <div class="flex flex-col gap-4">
              <label>Employment type</label>
              <div class="flex items-center gap-6">
                <label class="flex items-center gap-2">
                  <input type="checkbox" class="w-4 h-4">
                  Full-time
                </label>
                <label class="flex items-center gap-2">
                  <input type="checkbox" class="w-4 h-4">
                  Part-time
                </label>
                <label class="flex items-center gap-2">
                  <input type="checkbox" class="w-4 h-4">
                  Contract
                </label>
                <label class="flex items-center gap-2">
                  <input type="checkbox" class="w-4 h-4">
                  Internship
                </label>
                <label class="flex items-center gap-2">
                  <input type="checkbox" class="w-4 h-4">
                  Remote
                </label>
              </div>
            </div>
            <div class="flex flex-col gap-4">
              <label>Preferred work location</label>
              <div class="flex items-center gap-6">
                <label class="flex items-center gap-2">
                  <input type="radio" class="w-4 h-4">
                  On-site
                </label>
                <label class="flex items-center gap-2">
                  <input type="radio" class="w-4 h-4">
                  Remote
                </label>
                <label class="flex items-center gap-2">
                  <input type="radio" class="w-4 h-4">
                  Hybrid
                </label>
              </div>
            </div>
          </div>
          <div class="flex gap-4 items-center">
            <form class="flex flex-col gap-2 w-full">
              <label>Expected salary (USD)</label>
              <input type="text" placeholder="$1k - $1.5k" class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
            </form>
            <form class="flex flex-col gap-2 w-full">
              <label>Available start date</label>
              <input type="date" required placeholder="mm/dd/yyyy" class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
            </form>
          </div>
          <div class="flex gap-4 items-center">
            <form class="flex flex-col gap-2 w-full">
              <label>Willing to relocate?</label>
              <select class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
                <option>Yes</option>
                <option>No</option>
                <option>Maybe</option>
              </select>
            </form>
            <form class="flex flex-col gap-2 w-full">
              <label>Preferred country</label>
              <input type="text" placeholder="Cambodia / Remote" class="px-4 py-3 h-13 border border-[#eee] rounded-xl">
            </form>
          </div>
        </div>
        <div class="flex items-center gap-4">
          <baseBtn name="Back" @click="goBack"/>
          <baseBtn name="Next" to="candidate-profile-3"/>
        </div>
      </div>
    </div>
  </div>
</template>
