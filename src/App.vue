<template>
  <MenuComponent></MenuComponent>
  <Section></Section>
  <Footer></Footer>
</template>

<script>
import MenuComponent from './components/MenuComponent.vue'
import Footer from './components/Footer.vue';
import Section from './components/Section.vue'

export default {
  name: 'App',
  components: {
    MenuComponent, 
    Footer,
    Section
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
}
</style>
