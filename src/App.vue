<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
     <button>Explore More</button>

    <HomeComponent />
  </div>
</template>

<script>
import HomeComponent from './components/HomeComponent.vue'

export default {
  name: 'App',
  components: { 
    HomeComponent, 
    
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
button{
    font-size: 16px;
    background: blue;
    border-radius: 25px;
    color: black;
    padding: 20px;
}
</style>
