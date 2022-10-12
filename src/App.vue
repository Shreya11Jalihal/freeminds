<template>
  <div>
    <HeaderComponent/>
    <Section1Component/>
    <FooterComponent/>
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import FooterComponent from './components/FooterComponent.vue'
import Section1Component from './components/Section1Component.vue'
export default {
  name: 'App',
  components: {
    HeaderComponent,
    FooterComponent,
    Section1Component
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
