<template>
  <NavBar />
  <HeroBanner />
  <main>
    <AboutSection />
  </main>
</template>

<script>
import NavBar from './components/NavBar.vue'
import HeroBanner from './components/HeroBanner.vue'
import AboutSection from './components/AboutSection.vue'

export default {
  name: 'App',
  components: {
    NavBar, HeroBanner, AboutSection
  }
}
</script>

<style lang="scss">
@import './scss/main.scss';

</style>
