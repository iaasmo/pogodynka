<template>
  <WeatherView />
</template>

<script>
import WeatherView from './components/WeatherView.vue'
export default {
  name: 'App',
  components: {
    WeatherView
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
  box-shadow: 0 0 5px black;
  padding: 1em;
  border-radius: 5px;
}
</style>