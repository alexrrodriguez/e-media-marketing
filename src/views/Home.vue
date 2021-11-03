<template>
  <div id="app">
    <HeroSection />
    <main id="main">
      <About />
      <Counts />
      <Video />
      <Clients />
      <Testimonials />
      <Services />
      <Cta />
      <Portfolio />
    </main>
  </div>
</template>

<script>
import HeroSection from "../components/HeroSection.vue";
import About from "../components/About.vue";
import Counts from "../components/Counts.vue";
import Video from "../components/Video.vue";
import Clients from "../components/Clients.vue";
import Testimonials from "../components/Testimonials.vue";
import Services from "../components/Services.vue";
import Cta from "../components/Cta.vue";
import Portfolio from "../components/portfolio.vue";

export default {
  name: "app",
  components: {
    HeroSection,
    About,
    Counts,
    Video,
    Clients,
    Testimonials,
    Services,
    Cta,
    Portfolio,
  },
};
</script>
