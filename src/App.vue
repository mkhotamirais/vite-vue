<script setup>
import Header from "./components/home/Header.vue";
import Footer from "./components/home/Footer.vue";
</script>

<template>
  <div class="min-h-screen flex flex-col">
    <Header />
    <main class="grow container">
      <router-view />
    </main>
    <Footer />
  </div>
</template>