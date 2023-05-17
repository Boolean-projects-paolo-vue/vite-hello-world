<script>
import MainVue from './components/MainVue.vue'
import AppHero from './components/AppHero.vue'

export default {
  components: {
    MainVue,
    AppHero,
  }
}
</script>

<template>
  <h1>La mia prima app con Vite</h1>

  <MainVue />
  <AppHero />
</template>

<style scoped></style>
