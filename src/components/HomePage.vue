<script setup>
import NavBar from "./Navbar.vue";
import Banner from "./Banner.vue";

</script>

<template>
  <header class="w-full h-screen relative bg-indigo-600 border-0">
    <NavBar />
    <Banner />
    <img
      src="/icons/wave.svg"
      class="absolute bottom-0 z-10 paisagem-tablet:inline-block hidden"
      alt="ondas-cinzentas-svg"
    />
  </header>
</template>

<style scoped></style>
