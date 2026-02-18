<template>
    <div class="w-full banner">
        <div class="container pt-10 pb-10 flex flex-col items-center gap-10">
            <h2 class="text-7xl font-black text-center mt-15">Find the job made for you.</h2>
            <p class=" text-center font-black">We make it easy to find what's next. <br> Browse over 100,000 jobs — from top companies to fast-growing startups. </p>
           <div class="flex gap-2 items-center ">
                <NuxtLink to="/create your profile" class="w-[200px] text-center text-[#000] hover:text-[#fff] border-2 border-primary bg-primary hover:bg-accent hover:border-accent rounded-full px-4 py-2 transition-all duration-300 ease-in-out mr-5">Create your profile</NuxtLink>
                <NuxtLink to="/browse jobs" class="w-[200px] text-center border-2 border-primary text-primary rounded-full px-4 py-2 hover:border-accent hover:bg-accent hover:text-[#fff] transition-all duration-300 ease-in-out">Browse jobs</NuxtLink>
            </div>
        </div>
    </div>
    <div class="w-full bg-highlight  banner">
        <div class="container pt-20 pb-10 flex flex-row items-center gap-35 justify-center">
            
            <div class=" flex flex-col items-center gap-5">
                <h3 class="text-8xl text-primary font-black font-bold">8M+</h3>
                <p class="text-2xl font-black text-center">Matches Made</p>
            </div>
            <div class="ml-10 flex flex-col  items-center gap-5">
                <h3 class="text-8xl text-center text-primary font-black font-bold">150K+</h3>
                <p class="text-2xl font-black font-black text-center">Tech Jobs</p>
            </div>
            <div class="flex flex-col items-center gap-5">
                <h3 class="text-8xl text-primary font-black font-bold">10M+</h3>
                <p class="text-2xl font-black text-center">Startup Ready Candidates</p>
            </div>
        </div>
        <div class="w-200 h-0.5 bg-primary items-center justify-center mx-auto mt-20 "></div>
        <div class="container pt-20 pb-10 flex flex-row items-center gap-35 justify-center">
             <div class=" flex flex-col items-center gap-5">
                <p class=" font-black text-center">Startups who used our platform</p>
            </div>
        </div>
    </div>
     <div class="w-full banner">
        <div class="container  pb-10 flex flex-row items-center gap-35 justify-center">
            <div class="p-15">
                <img src="/assets/images/job seeker.webp" alt="World of Talent">
            </div>
            <div class="w-300">
                <h2 class="text-5xl font-black mb-10">Brand yourself for new opportunities</h2>
                <p class="text-1xl font-black ">Create a profile that highlights your unique skills and preferences, then apply to jobs with just one click</p>
                <div class="flex gap-2 items-center ">
                    <NuxtLink
                        to="/click"
                        class="w-[100px] h-[60px] flex items-center justify-center
                                border-4 border-primary bg-primary
                                hover:bg-accent hover:border-accent
                                rounded-full transition-all duration-300 ease-in-out mr-5"
                        >
                        <img
                            src="/assets/images/click.png"
                            alt="click"
                            class="w-10 h-10 object-contain"
                        >
                    </NuxtLink>
                   <div class="mt-10">
                            <h2 class="text-2xl font-black mt-5 text-primary">One click apply</h2>
                            <p class="mt-2">Say goodbye to cover letters - your profile is all you need. One click to apply then you're done.</p>
                        </div>
                </div>
                 <div class="flex gap-2 items-center ">
                    <NuxtLink
                        to="/click"
                        class="w-[100px] h-[60px] flex items-center justify-center
                                border-4 border-primary bg-primary
                                hover:bg-accent hover:border-accent
                                rounded-full transition-all duration-300 ease-in-out mr-5"
                        >
                        <img
                            src="/assets/images/click1.png"
                            alt="click"
                            class="w-10 h-10 object-contain"
                        >
                    </NuxtLink>
                        <div class="mt-10 pt-15">
                            <h2 class="text-2xl font-black mt-5 text-primary">Set your preferences</h2>
                            <p class="mt-2 mb-10">Streamline the interview process by setting your expectations (salary, industry, culture, etc.) upfront.</p>
                            <NuxtLink to="/discover" class="m-5 text-2xl font-semibold text-primary flex items-center gap-2 group">Create your profile<Icon name="mi:arrow-right" class="transition-transform duration-300 group-hover:translate-x-2"/></NuxtLink>
                        </div>
                </div>
            </div>
        </div>
    </div>
    <div class="w-full h-0.5 bg-primary items-center justify-center mx-auto mt-20 "></div>
    <div class="w-full banner "></div>
        <div class="w-full">
        <div class="container grid grid-cols-2 items-center gap-4">
        <div class="flex flex-col gap-4">
            <h2 class="font-black text-6xl">Find work that works for you</h2>
            <p>A personalized and private job search, with all the info you care about, all upfront</p>
            <div class="flex  items-center ">
                    <NuxtLink
                        to="/click"
                        class="w-[50px] h-[50px] flex items-center justify-center
                                border-4 border-primary bg-primary
                                hover:bg-accent hover:border-accent
                                rounded-full transition-all duration-300 ease-in-out mr-5">
                        <img
                            src="/assets/images/click.png"
                            alt="click"
                            class="w-8 h-8 object-contain">
                    </NuxtLink>
                    <div class="mt-6">
                            <h2 class="text-2xl font-black mt-5 text-primary">Stay in the know</h2>
                            <span class="mt-2">No guessing games. View salary and stock options before you apply.</span>
                    </div>
            </div>
            <div class="flex  items-center ">
                    <NuxtLink
                        to="/click"
                        class="w-[50px] h-[50px] flex items-center justify-center
                                border-4 border-primary bg-primary
                                hover:bg-accent hover:border-accent
                                rounded-full transition-all duration-300 ease-in-out mr-5">
                        <img
                            src="/assets/images/click2.png"
                            alt="click"
                            class="w-8 h-8 object-contain">
                    </NuxtLink>
                    <div class="mt-6">
                            <h2 class="text-2xl font-black mt-5 text-primary">Personalized search</h2>
                            <span class="mt-2">Personalized filters make it quick and easy to find the jobs you care about</span>
                    </div>
            </div>
            <div class="flex  items-center ">
                    <NuxtLink
                        to="/click"
                        class="w-[50px] h-[50px] flex items-center justify-center
                                border-4 border-primary bg-primary
                                hover:bg-accent hover:border-accent
                                rounded-full transition-all duration-300 ease-in-out mr-5">
                        <img
                            src="/assets/images/click3.png"
                            alt="click"
                            class="w-8 h-8 object-contain">
                    </NuxtLink>
                    <div class="mt-6">
                            <h2 class="text-2xl font-black mt-5 text-primary">Unique roles, exciting teams</h2>
                            <span class="mt-2">Discover unique jobs with future-defining teams</span>
                    </div>
            </div>
            <NuxtLink to="/discover" class="m-15 text-2xl font-semibold text-primary flex items-center gap-2 group">Browes Jobs<Icon name="mi:arrow-right" class="transition-transform duration-300 group-hover:translate-x-2"/></NuxtLink>
        </div>
        <div class=" p-15">
            <img src="/assets/images/job seeker1.webp" alt="World of Talent">
        </div>
        </div>
    </div>
    <div class="w-full h-0.5 bg-primary items-center justify-center mx-auto mt-20 "></div>
     <div class="w-full banner "></div>
        <div class="w-full">
        <div class="container grid grid-cols-2 items-center gap-4">
             <div class=" p-15">
            <img src="/assets/images/job seeker2.webp" alt="World of Talent">
        </div>
        <div class="flex flex-col gap-4">
            <h2 class="font-black text-5xl">FLet the opportunities come to you</h2>
            <div class="flex  items-center ">
                    <NuxtLink
                        to="/click"
                        class="w-[50px] h-[50px] flex items-center justify-center
                                border-4 border-primary bg-primary
                                hover:bg-accent hover:border-accent
                                rounded-full transition-all duration-300 ease-in-out mr-5">
                        <img
                            src="/assets/images/click4.png"
                            alt="click"
                            class="w-8 h-8 object-contain">
                    </NuxtLink>
                    <div class="mt-6">
                            <h2 class="text-2xl font-black mt-5 text-primary">Connect with founders</h2>
                            <span class="mt-2">Let founders pitch you directly on their opportunity. </span>
                    </div>
            </div>
            <div class="flex  items-center ">
                    <NuxtLink
                        to="/click"
                        class="w-[50px] h-[50px] flex items-center justify-center
                                border-4 border-primary bg-primary
                                hover:bg-accent hover:border-accent
                                rounded-full transition-all duration-300 ease-in-out mr-5">
                        <img
                            src="/assets/images/click5.png"
                            alt="click"
                            class="w-8 h-8 object-contain">
                    </NuxtLink>
                    <div class="mt-6">
                            <h2 class="text-2xl font-black mt-5 text-primary">Get featured</h2>
                            <span class="mt-2">Feature your profile even further and make 3x more connections</span>
                    </div>
            </div>
            <NuxtLink to="/discover" class="m-15 text-2xl font-semibold text-primary flex items-center gap-2 group">Get Started<Icon name="mi:arrow-right" class="transition-transform duration-300 group-hover:translate-x-2"/></NuxtLink>
        </div>
       
        </div>
    </div>
    

</template>
