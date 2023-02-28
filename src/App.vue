<!-- Descrizione:
Create un nuovo progetto utilizzando Vite e Vue 3 e definite i componenti necessari per strutturare il layout come da screenshot allegato.
Quando la struttura a macroblocchi è pronta, popolate le voci di menu dinamicamente usando i data del componente.
Per oggi diamo priorità alla struttura: quando è tutto bello solido, passiamo al Sass! -->

<script>
import AppHeader from './components/AppHeader.vue'
import AppContent from './components/AppContent.vue';
import AppOption from './components/AppOption.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    AppHeader,
    AppContent,
    AppOption,
    AppFooter,
  }
}
</script>

<template>
  <AppHeader />
  <AppContent />
  <AppOption />
  <AppFooter />
</template>

<style lang="scss">
@use "../src/scss/general.scss"
</style>

