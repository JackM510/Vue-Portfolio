<script setup lang="ts">
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
import { faVuejs, faTypescript, faTailwindCss } from '@fortawesome/free-brands-svg-icons'
</script>

<template>
    <div class="min-h-[70px] flex flex-col sm:flex-row items-center 
        bg-black text-white py-4 px-12">
        <div class="flex items-center gap-6">
            <FontAwesomeIcon :icon="faVuejs" class="icon"/>
            <FontAwesomeIcon :icon="faTypescript" class="icon" />
            <FontAwesomeIcon :icon="faTailwindCss" class="icon" />
        </div>
        <div class="ml-0 pt-4 sm:ml-auto sm:pt-0 lg:ml-0 lg:absolute lg:left-1/2 lg:-translate-x-1/2">
            <span>© 2026 Jack Marshall</span>
        </div>
    </div>
</template>