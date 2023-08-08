<script>
import LandingPage from './components/landingPage.vue';
import AboutMe from './components/aboutMe.vue'

export default {
    methods: {
        hello() {
            alert("Hello World!");
        }
    },
    components: { LandingPage, AboutMe }
}
</script>

<template>
  <section class="landing-page">
    <LandingPage></LandingPage>
  </section>
  <section class="about-me">
    <AboutMe></AboutMe>
  </section>
</template>

