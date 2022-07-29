<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
    <div class="sm:max-w-sm md:max-w-md lg:max-w-lg max-w-xs mx-auto mt-10">
        <h1 class="font-bold text-3xl mb-10">
            <RouterLink to="/">phpjsweekly.com</RouterLink>
        </h1>
        <RouterView />
    </div>
</template>


