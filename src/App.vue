<template>
  <NavBar />
  <HeroBanner />
  <main>
    <AboutSection />
    <TravelCarousel />
  </main>
</template>

<script>
import NavBar from './components/NavBar.vue'
import HeroBanner from './components/HeroBanner.vue'
import AboutSection from './components/AboutSection.vue'
import TravelCarousel from './components/TravelCarousel.vue'

export default {
  name: 'App',
  components: {
    NavBar, HeroBanner, AboutSection, TravelCarousel
  }
}
</script>

<style lang="scss">
@import './scss/main.scss';

</style>
