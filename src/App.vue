<script>
import LandingPage from "./components/landingPage.vue";
import AboutMe from "./components/aboutMe.vue";
import footerComp from "./components/footerComp.vue";
import OpenGraph from "./components/OpenGraph.vue";

export default {
  methods: {
    hello() {
      alert("Hello World!");
    },
  },
  components: { LandingPage, AboutMe, footerComp, OpenGraph },
};
</script>

<template>
  <OpenGraph></OpenGraph>
  <section class="landing-page">
    <LandingPage></LandingPage>
  </section>
  <section class="about-me">
    <AboutMe></AboutMe>
  </section>
  <footerComp></footerComp>
</template>
