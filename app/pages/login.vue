CHHEUN NYTA, [2/20/26 7:48 AM]
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
      
      <div class="relative w-full md:w-1/2 min-h-[400px] flex flex-col justify-between p-12 text-white">
          <div class="absolute inset-0 z-0">
            <img 
              src="https://images.unsplash.com/photo-1522071820081-009f0129c71c?auto=format&fit=crop&q=80" 
              alt="HR Team" 
              class="w-full h-full object-cover opacity-40"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-[#1c252e] via-transparent to-black/20"></div>
          </div>

          <div class="relative z-10">
            <div class="flex items-center gap-2 mb-2">
            </div>
      </div>

        <div class="relative z-10">
          <h2 class="text-4xl md:text-5xl font-semibold leading-tight mb-6 italic">
            Find the job made for you
          </h2>
          <p>Browse over 130K jobs at top companies and fast-growing startups.
</p>
          <div class="flex gap-2">
            <div class="h-1.5 w-12 bg-white rounded-full"></div>
            <div class="h-1.5 w-6 bg-white/30 rounded-full"></div>
            <div class="h-1.5 w-6 bg-white/30 rounded-full"></div>
          </div>
        </div>
      </div>

      <div class="w-full md:w-1/2 p-8 md:p-20 bg-highlight flex flex-col justify-center">
        <div class="max-w-md mx-auto w-full text-white">
          <header class="mb-10">
            <h1 class="text-4xl font-bold mb-3">Welcome Back</h1>
            <p class="text-gray-400">Find the job made for you! </p>
          </header>

          <form @submit.prevent="handleLogin" class="space-y-6">
            <div class="relative group">
              <span class="absolute left-4 top-1/2 -translate-y-1/2 text-gray-500 group-focus-within:text-teal-400 transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 12a4 4 0 10-8 0 4 4 0 008 0zm0 0v1.5a2.5 2.5 0 005 0V12a9 9 0 10-9 9m4.5-1.206a8.959 8.959 0 01-4.5 1.207" /></svg>
              </span>
              <input 
                v-model="email"
                type="email" 
                placeholder="Work Email" 
                class="w-full bg-[#e8f0fe] text-gray-900 pl-12 pr-4 py-4 rounded-xl focus:outline-none focus:ring-2 focus:ring-teal-500 transition-all placeholder:text-gray-500"
              />
            </div>

            <div class="relative group ">
              <span class="absolute left-4  top-1/2 -translate-y-1/2 text-gray-500 group-focus-within:text-teal-400 transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5" fill="none" viewBox="0 0 24 24"  stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z" /></svg>
              </span>
              <input 
                v-model="password"
                type="password" 
                placeholder="Password" 
                class="w-full bg-[#e8f0fe] text-gray-900 pl-12 pr-12 py-4 rounded-xl focus:outline-none focus:ring-2 focus:ring-teal-500 transition-all placeholder:text-gray-500"
              />
              <NuxtLink to="/button" type="button" class="absolute right-4 top-1/2 -translate-y-1/2 text-gray-400 hover:text-gray-600">
             </NuxtLink>
            </div>


<div class="flex items-center justify-between text-sm">
              <a href="#" class="text-gray-400 hover:text-teal-400 transition-colors">Forgot Password?</a>
              <div class="flex items-center gap-3">
            
              
              </div>
            </div>
             <NuxtLink to="/Apple"  class="flex items-center justify-center  bg-teal-600 hover:bg-teal-500 text-white font-bold  gap-3 py-4 rounded-xl transition shadow-sm ">
              Login
             </NuxtLink>

             
          </form>

          <div class="relative my-8">
            <div class="absolute inset-0 flex items-center"><div class="w-full border-t border-gray-800"></div></div>
            <div class="relative flex justify-center text-xs uppercase"><span class="bg-[#1c252e] px-4 text-gray-500">Or continue with</span></div>
          </div>

          <div class="grid grid-cols-2 gap-4">
            <NuxtLink to="/Apple"  class="flex w-105 items-center justify-center gap-3 bg-white text-gray-900 py-4 rounded-xl hover:bg-gray-100 transition shadow-sm font-medium">
              <img src="https://www.svgrepo.com/show/355037/google.svg" class="w-5 h-5" alt="Google" />
              Google
             </NuxtLink>
            
          </div>

          <p class="mt-10 text-center text-gray-400 text-sm">
            Don't have an account?             
            <NuxtLink to="/Signup" href="#" class="text-teal-400 font-bold hover:underline">Sign up</NuxtLink>
          </p>
        </div>
      </div>
    </div>
  </div>
</template>