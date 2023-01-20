<template>
  <NavBar />
  <HeroBanner />
  <main>
    <AboutSection />
    <TravelCarousel />
    <OurSupport />
    <TestimonialSection />
  </main>
</template>

<script>
import NavBar from './components/NavBar.vue'
import HeroBanner from './components/HeroBanner.vue'
import AboutSection from './components/AboutSection.vue'
import TravelCarousel from './components/TravelCarousel.vue'
import OurSupport from './components/OurSupport.vue'
import TestimonialSection from './components/TestimonialSection.vue'

export default {
  name: 'App',
  components: {
    NavBar, HeroBanner, AboutSection, TravelCarousel, OurSupport, TestimonialSection
  }
}
</script>

<style lang="scss">
@import './scss/main.scss';

</style>
