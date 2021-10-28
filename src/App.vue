<template>
  <div id="app">
    <Navbar />
    <HeroSection />
    <!-- <div id="nav">
      <router-link to="/">Home</router-link>
      |
      <router-link to="/about">About</router-link>
    </div> -->
    <router-view />
  </div>
</template>

<style></style>

<script>
import Navbar from "./components/Navbar.vue";
import HeroSection from "./components/HeroSection.vue";

export default {
  name: "app",
  components: {
    Navbar,
    HeroSection,
  },
};
</script>
