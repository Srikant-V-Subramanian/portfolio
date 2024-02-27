<script>
import LandingPage from "./components/landingPage.vue";
import AboutMe from "./components/aboutMe.vue";
import footerComp from "./components/footerComp.vue";
import OpenGraph from "./components/OpenGraph.vue";
import Projects from "./components/projects.vue";
import "../src/scss/style.scss";

import * as bootstrap from "bootstrap";

export default {
  components: { LandingPage, AboutMe, footerComp, OpenGraph, Projects },
};
</script>

<template>
  <!-- This following line is optional. Only necessary if you use the option css3:false and you want to use other easing effects rather than "easeInOutCubic". -->
  <OpenGraph></OpenGraph>
  <div class="section">
    <section class="landing-page">
      <LandingPage></LandingPage>
    </section>
    <section class="about-me">
      <AboutMe></AboutMe>
    </section>
    <section class="my-projects">
      <Projects></Projects>
    </section>
    <footerComp></footerComp>
  </div>
</template>
