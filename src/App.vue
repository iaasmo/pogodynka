<template>
  <!--<HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <WeatherView />
</template>

<script>
import WeatherView from './components/WeatherView.vue'

export default {
  name: 'WeatherView',
  components: {
    WeatherView,
    data(){
      return{
        weather: "sun",
      }
    }
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
