<script setup>
import NavBar from './Navbar.vue'
import Banner from './Banner.vue'
</script>

<template>
    <header class="w-full h-screen relative bg-indigo-600">
        <NavBar/>
        <Banner/>
        <img src="/wave.svg" class="absolute bottom-0 z-10" alt="">
    </header>
</template>

<style scoped>

</style>