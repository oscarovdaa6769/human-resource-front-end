<template>
  <div class="min-h-screen  p-4 md:p-8 flex items-center justify-center font-sans w-full banner">
    
    <div v-if="submitted" class="max-w-md w-full bg-white rounded-2xl shadow-xl p-10 text-center border border-slate-200">
      <div class="w-20 h-20 bg-green-100 text-green-600 rounded-full flex items-center justify-center mx-auto mb-6">
        <svg class="w-10 h-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7" /></svg>
      </div>
      <h2 class="text-2xl font-bold text-slate-900">Application Sent!</h2>
      <p class="text-slate-500 mt-4">We've received your application for the <strong>{{ jobDetails.Position }}</strong> position.</p>
      <button @click="submitted = false" class="mt-8 text-blue-600 font-semibold hover:text-blue-800 transition">
        ← Back to application
      </button>
    </div>

    <div v-else class="max-w-5xl w-full bg-white rounded-2xl shadow-xl overflow-hidden flex flex-col lg:flex-row border border-slate-200">
      
      <aside class="w-full lg:w-72 bg-slate-900 text-white p-8 flex flex-col gap-8">
        <div class="flex items-center gap-4">
          <div class="h-14 w-14 bg-white rounded-full flex items-center justify-center p-1 overflow-hidden">
            <img src="https://photos.wellfound.com/startups/i/4358711-21319e6bc09262cddf945f132f22bd85-thumb_jpg.jpg?buster=1501329308" alt="IonQ Logo" />
          </div>
          <div>
            <p class="text-xs uppercase tracking-widest text-slate-400 font-semibold">Applying To</p>
            <h2 class="text-xl font-bold">IonQ</h2>
          </div>
        </div>

        <div class="space-y-6">
          <div v-for="(val, label) in jobDetails" :key="label">
            <p class="text-xs text-slate-400 uppercase tracking-wider mb-1">{{ label }}</p>
            <p class="text-md font-medium text-slate-100">{{ val }}</p>
          </div>
        </div>

        <div class="mt-auto pt-8 border-t border-slate-700">
          <p class="text-xs text-slate-400 leading-relaxed">
            IonQ is building the world's best quantum computers to solve the world's most complex problems.
          </p>
        </div>
      </aside>

      <main class="flex-1 p-8 lg:p-12">
        <header class="mb-10">
          <h1 class="text-3xl font-bold text-slate-900">Your Application</h1>
          <p class="text-slate-500 mt-2">
            Complete the details below or <a href="#" class="text-blue-600 hover:underline font-medium">Log in</a> to autofill.
          </p>
        </header>

        <form @submit.prevent="submitForm" class="space-y-6">
          
          <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div class="flex flex-col gap-2">
              <label class="text-sm font-semibold text-slate-700">Full Name*</label>
              <input type="text" placeholder="Jane Doe" class="input-field" required />
            </div>
            <div class="flex flex-col gap-2">
              <label class="text-sm font-semibold text-slate-700">Email Address*</label>
              <input type="email" placeholder="jane@example.com" class="input-field" required />
            </div>
          </div>

          <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div class="flex flex-col gap-2">
              <label class="text-sm font-semibold text-slate-700">Password*</label>
              <input type="password" placeholder="Min. 12 characters" class="input-field" required />
            </div>
            <div class="flex flex-col gap-2">
              <label class="text-sm font-semibold text-slate-700">Confirm Password*</label>
              <input type="password" placeholder="Repeat password" class="input-field" required />
            </div>
          </div>

          <hr class="border-slate-100 my-4" />

          <div class="grid grid-cols-1 md:grid-cols-2 gap-6 items-end">
            <div class="flex flex-col gap-2">
              <label class="text-sm font-semibold text-slate-700">Current Location*</label>
              <input type="text" placeholder="e.g. Bothell, WA" class="input-field" required />
            </div>
            <label class="flex items-center gap-3 p-3 border border-transparent rounded-lg cursor-pointer hover:bg-slate-50 transition">
              <input type="checkbox" class="w-4 h-4 rounded text-blue-600 border-slate-300 focus:ring-blue-500" />
              <span class="text-sm text-slate-600">Open to work remotely</span>
            </label>
          </div>

          <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div class="flex flex-col gap-2">
              <label class="text-sm font-semibold text-slate-700">Years of Experience*</label>
              <select class="input-field bg-white" required>
                <option value="">Select range</option>
                <option>0-2 years</option>
                <option>3-5 years</option>
                <option>6-10 years</option>
                <option>10+ years</option>
              </select>
            </div>
            <div class="flex flex-col gap-2">
              <label class="text-sm font-semibold text-slate-700">Desired Salary (USD)*</label>
              <input type="number" placeholder="Enter annual amount" class="input-field" required />
            </div>
          </div>

          <div class="bg-secondary/8 p-6 rounded-xl space-y-4">
            <p class="font-semibold text-slate-800 text-sm italic">Work Authorization</p>
            <div class="flex flex-col md:flex-row md:items-center justify-between gap-4">
              <span class="text-sm text-slate-600">Legally authorized to work in the US?</span>
              <div class="flex gap-4">
                <label class="radio-label"><input type="checkbox" name="auth" value="yes" required /> Yes</label>
                <label class="radio-label"><input type="checkbox" name="auth" value="no" /> No</label>
              </div>
            </div>
          </div>

          <div class="flex flex-col gap-2">
            <label class="text-sm font-semibold text-slate-700">Cover Letter</label>
            <textarea rows="4" placeholder="Briefly tell IonQ why you're a great fit..." class="input-field resize-none"></textarea>
          </div>


          <button type="submit" class="w-full py-4 bg-primary hover:bg-secondary text-[#000] hover:text-[#fff] font-bold rounded-xl shadow-lg shadow-blue-200 transition-all transform hover:-translate-y-0.5 active:scale-95">
            Submit 
          </button>
          
          <p class="text-center text-[10px] text-slate-400 uppercase tracking-widest">
            By continuing you accept our terms and privacy policy
          </p>
        </form>
      </main>
    </div>
  </div>
</template>

<script setup>
import { ref } from 'vue';

const submitted = ref(false);

const jobDetails = {
  "Position": "Staff Data Engineer",
  "Location": "Bothell, WA",
  "Job Type": "Full Time",
  "Visa": "Sponsorship Not Available"
}

const submitForm = () => {
  // Toggle the view to the success state
  submitted.value = true;
}
</script>

<style scoped>

@reference "tailwindcss";

.input-field {
  @apply w-full px-4 py-3 rounded-lg border border-slate-200 focus:border-blue-500 focus:ring-4 focus:ring-blue-100 outline-none transition-all text-slate-800 placeholder:text-slate-400;
}

.radio-label {
  @apply flex items-center gap-2 text-sm font-medium text-slate-700 cursor-pointer;
}

input[type="radio"] {
  @apply w-4 h-4 text-blue-600 border-slate-300 focus:ring-blue-500;
}
</style>


