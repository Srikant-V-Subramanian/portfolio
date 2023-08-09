<script>
import LandingPage from "./components/landingPage.vue";
import AboutMe from "./components/aboutMe.vue";
import footerComp from "./components/footerComp.vue";

export default {
  methods: {
    hello() {
      alert("Hello World!");
    },
  },
  components: { LandingPage, AboutMe, footerComp },
};
</script>

<template>
  <section class="landing-page">
    <LandingPage></LandingPage>
  </section>
  <section class="about-me">
    <AboutMe></AboutMe>
  </section>
  <footerComp></footerComp>
</template>
