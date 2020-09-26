<template>
  <WorldTour />
</template>

<script>
import WorldTour from './components/worldTour.vue'
/**
 * the links is not recieving any data
 *  why?
 */
export default {
  name: 'App',
  components: {
    WorldTour,
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
