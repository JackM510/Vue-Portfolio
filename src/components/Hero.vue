<script setup lang="ts">
    import hero from "../assets/hero.jpg";
    import { faBriefcase, faLocationDot } from "@fortawesome/free-solid-svg-icons";
</script>

<template>
    <div class="h-[calc(100vh-50px)] md:py-8">
        <div 
            class="w-full md:w-4/5 xl:w-3/4
                flex flex-col md:flex-row md:mx-auto 
                border rounded-3xl border-gray-700 md:p-2"
        >
            <div class="w-1/2 flex flex-col basis-1/2 justify-center order-2 md:order-1 text-white text-left p-8">
                <h1 class="uppercase">Jack Marshall</h1>
                <div class="flex mb-8">
                    <div class="flex-1 text-xl">
                        <FontAwesomeIcon :icon="faBriefcase" class="text-blue-400 mr-2"/> 
                        <span>Web Developer</span>
                    </div>
                    <div class="flex-1 text-xl">
                        <FontAwesomeIcon :icon="faLocationDot" class="text-red-400 mr-2"/> 
                        <span>Northern Rivers, NSW</span>
                    </div>
                </div>
                <hr class="text-gray-700"><br>
                
                
                
                <p class="text-2xl font-bold">Welcome to my personal website!</p>
                
            </div>
            <div class="basis-1/2 relative aspect-[1/1] order-1 md:order-2">
                <div class="absolute inset-0 bg-black/20"></div>
                <img :src="hero" class="w-full h-full object-cover md:rounded-r-3xl" alt="A picture of Jack Marshall" />
            </div>
        </div>
    </div>
</template>