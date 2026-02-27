
<script setup>


import { ref } from 'vue';

const email = ref('');
const password = ref('');
const rememberMe = ref(false);

const handleLogin = () => {
  console.log('Logging in with:', {
    email: email.value,
    password: password.value,
    remember: rememberMe.value
  });
};
</script>

<template>
  <div class="min-h-screen bg-secondary flex items-center justify-center p-4 md:p-10 font-sans mt-15">

    <div class="flex flex-col md:flex-row w-full max-w-6xl bg-[#1c252e] rounded-[2.5rem] overflow-hidden shadow-2xl border border-white/5">

      <div class="relative w-full md:w-1/2 min-h-[500px] flex flex-col justify-between p-12 text-white">
          <div class="absolute inset-0 z-0">
            <img
              src="https://images.unsplash.com/photo-1522071820081-009f0129c71c?auto=format&fit=crop&q=80"
              alt="HR Team"
              class="w-full h-full object-cover"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-[#1c252e] via-black/20 to-black/40"></div>
          </div>

          <div class="relative z-10">
            <div class="flex items-center gap-2 mb-2"></div>
          </div>

          <div class="relative z-10">
            <h2 class="text-4xl md:text-5xl font-semibold leading-tight mb-6 italic">
              Find the job made for you
            </h2>
            <p class="text-gray-200 mb-6">Browse over 130K jobs at top companies and fast-growing startups.</p>
            <div class="flex gap-2">
              <div class="h-1.5 w-12 bg-white rounded-full"></div>
              <div class="h-1.5 w-6 bg-white/30 rounded-full"></div>
              <div class="h-1.5 w-6 bg-white/30 rounded-full"></div>
            </div>
          </div>
      </div>

      <div class="w-full md:w-1/2 flex flex-col justify-center px-8 md:px-16 lg:px-24 py-12 bg-highlight">
        <div class="max-w-md w-full mx-auto md:ml-0">


          <h2 class="text-4xl font-bold mb-2 text-primary">Welcome Back</h2>
          <p class="text-white mb-8 font-medium">Find the job made for you!</p>

          <NuxtLink  to="google" class="w-full flex items-center justify-center gap-3 border-2 border-accent rounded-md py-3 px-4 transition-colors mb-6">
            <img src="https://www.gstatic.com/firebasejs/ui/2.0.0/images/auth/google.svg" class="w-5 h-5" alt="Google">
            <span class="font-semibold  text-white">Log in with Google</span>
          </NuxtLink>

          <div class="relative flex items-center mb-6">
            <div class="flex-grow border-t border-gray-200"></div>
            <span class="flex-shrink mx-4 text-white text-xs uppercase tracking-widest font-semibold">or Login with Email</span>
            <div class="flex-grow border-t border-gray-200"></div>
          </div>

          <form @submit.prevent="handleLogin" class="space-y-4">
            <input
              v-model="email"
              type="email"
              placeholder="Email"
              class="w-full border-2 border-accent text-white rounded-md px-4 py-3 focus:outline-none focus:ring-2 focus:ring-accent focus:border-transparent transition-all"
            />
            <input
              v-model="password"
              type="password"
              placeholder="Password"
              class="w-full border-2 border-accent text-white rounded-md px-4 py-3 focus:outline-none focus:ring-2  focus:ring-accent  focus:border-transparent transition-all"
            />

            <div class="text-right">
              <a href="#" class="text-sm font-semibold text-white underline decoration-gray-400 underline-offset-4 hover:text-black">Forgot password?</a>
            </div>

              <button type="submit" class="w-full bg-primary text-white font-bold py-4 rounded-md hover:bg-accent transition-colors mt-4">
              Log in
             </button>
          </form>

          <p class="mt-8 text-center md:text-left text-white font-medium">
            Not registered?
            <a href="/sign-up" class="text-primary font-bold underline decoration-black underline-offset-4">Create an Account</a>
          </p>
        </div>
      </div>

    </div>
  </div>
</template>



