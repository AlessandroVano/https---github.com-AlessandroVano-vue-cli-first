<template>
  <div id="app">

  <Title />
  <Hero />

 

  </div>
</template>

<script>
// la chiocciola sarebbe da src in giù
import Title from '@/components/Title.vue';
import Hero from '@/components/Hero.vue';

export default {
  name: 'App',
  components: {
    Title,
    Hero,
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
