<template>
  <NavBar />
  <HeroBanner />
  <main>
    <AboutSection />
    <TravelCarousel />
    <OurService />
    <TestimonialSection />
    <ContactUs />
  </main>
  <FooterNt />
</template>

<script>
import NavBar from './components/NavBar.vue'
import HeroBanner from './components/HeroBanner.vue'
import AboutSection from './components/AboutSection.vue'
import TravelCarousel from './components/TravelCarousel.vue'
import OurService from './components/OurService.vue'
import TestimonialSection from './components/TestimonialSection.vue'
import ContactUs from './components/ContactUs.vue'
import FooterNt from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    NavBar, HeroBanner, AboutSection, TravelCarousel, OurService, TestimonialSection, ContactUs, FooterNt
  }
}
</script>

<style lang="scss">
@import './scss/main.scss';

</style>
