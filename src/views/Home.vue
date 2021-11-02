<template>
  <div id="app">
    <HeroSection />
    <main id="main">
      <About />
      <Counts />
      <Video />
      <Clients />
    </main>
  </div>
</template>

<script>
import HeroSection from "../components/HeroSection.vue";
import About from "../components/About.vue";
import Counts from "../components/Counts.vue";
import Video from "../components/Video.vue";
import Clients from "../components/Clients.vue";

export default {
  name: "app",
  components: {
    HeroSection,
    About,
    Counts,
    Video,
    Clients,
  },
};
</script>
