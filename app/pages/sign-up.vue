<template>
  <div class="min-h-screen w-full flex flex-col md:flex-row font-sans text-gray-900">
    
    <div class="w-full md:w-2/5 flex flex-col justify-center px-8 md:px-16 lg:px-24 py-12 bg-white">
      <div class="max-w-md w-full mx-auto md:ml-0">
        <div class="mb-12">
          <h1 class="text-2xl font-black tracking-tight">wellfound<span class="text-red-500">:</span></h1>
        </div>

        <h2 class="text-4xl font-bold mb-2">Login</h2>
        <p class="text-gray-600 mb-8 font-medium">Find the job made for you!</p>

        <button class="w-full flex items-center justify-center gap-3 border border-gray-300 rounded-md py-3 px-4 hover:bg-gray-50 transition-colors mb-6">
          <img src="https://www.gstatic.com/firebasejs/ui/2.0.0/images/auth/google.svg" class="w-5 h-5" alt="Google">
          <span class="font-semibold text-gray-700">Log in with Google</span>
        </button>

        <div class="relative flex items-center mb-6">
          <div class="flex-grow border-t border-gray-200"></div>
          <span class="flex-shrink mx-4 text-gray-400 text-xs uppercase tracking-widest font-semibold">or Login with Email</span>
          <div class="flex-grow border-t border-gray-200"></div>
        </div>

        <form @submit.prevent="handleLogin" class="space-y-4">
          <div>
            <input 
              type="email" 
              placeholder="Email" 
              class="w-full border border-gray-300 rounded-md px-4 py-3 focus:outline-none focus:ring-2 focus:ring-black focus:border-transparent transition-all"
            />
          </div>
          <div>
            <input 
              type="password" 
              placeholder="Password" 
              class="w-full border border-gray-300 rounded-md px-4 py-3 focus:outline-none focus:ring-2 focus:ring-black focus:border-transparent transition-all"
            />
          </div>
          
          <div class="text-right">
            <a href="#" class="text-sm font-semibold text-gray-600 underline decoration-gray-400 underline-offset-4 hover:text-black">Forgot password?</a>
          </div>

          <button type="submit" class="w-full bg-black text-white font-bold py-4 rounded-md hover:bg-gray-800 transition-colors mt-4">
            Log in
          </button>
        </form>

        <p class="mt-8 text-center md:text-left text-gray-600 font-medium">
          Not registered? 
          <a href="#" class="text-black font-bold underline decoration-black underline-offset-4">Create an Account</a>
        </p>
      </div>
    </div>

    <div class="hidden md:flex w-full md:w-3/5 bg-accent relative overflow-hidden items-center justify-center p-12">
     <div class="bg-accent"></div>
    </div>

  </div>
</template>

<script setup>
const handleLogin = () => {
  console.log('Login attempt...');
};
</script>