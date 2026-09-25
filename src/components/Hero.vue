<script setup lang="ts">
    import hero from "../assets/hero.jpg";
</script>

<template>
    <div class="flex h-[calc(100vh-50px)] p-12">
        <div 
            class="flex justify-between mx-auto border rounded-2xl border-gray-700">
            <div class="w-1/2 flex flex-col justify-center text-white text-left p-8">
                <h1>Jack Marshall</h1>
                <h2>Web Developer</h2>
                <h2>Northern Rivers, NSW</h2>
            </div>
            <div class="w-1/2 aspect-[1/1]">
                <img :src="hero" class="w-full h-full object-cover rounded-r-lg" alt="A picture of Jack Marshall" />
            </div>
        </div>
    </div>
</template>