<template>
    <div class="w-full banner">
        <div class="container pt-10 pb-10 flex flex-col items-center gap-10">
            <h2 class="text-7xl font-black text-center">Find the job made for you.</h2>
            <p class=" text-center font-black">We make it easy to find what's next. <br> Browse over 100,000 jobs — from top companies to fast-growing startups. </p>
           <div class="flex gap-2 items-center">
                <NuxtLink to="/sign-up" class="text-[#000] hover:text-[#fff] border-2 border-primary bg-primary hover:bg-accent hover:border-accent rounded-full px-4 py-2 transition-all duration-300 ease-in-out">Create your profile</NuxtLink>
                <NuxtLink to="/login" class=" border-2 border-primary text-primary rounded-full px-4 py-2 hover:border-accent hover:bg-accent hover:text-[#fff] transition-all duration-300 ease-in-out">Browse jobs</NuxtLink>
            </div>
        </div>
    </div>
</template>
