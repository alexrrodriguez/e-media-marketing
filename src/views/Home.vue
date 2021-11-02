<template>
  <div id="app">
    <HeroSection />
    <main id="main">
      <About />
    </main>
  </div>
</template>

<script>
import HeroSection from "../components/HeroSection.vue";
import About from "../components/About.vue";

export default {
  name: "app",
  components: {
    HeroSection,
    About,
  },
};
</script>
