<template>

<!-- Para intalar vuex usamremos npm add vuex@next --save en la linea-->
  <img alt="Vue logo" src="./assets/logo.png">
 
  <h1>hpña</h1>
  <div>

      <cnt></cnt>
  </div>
  
</template>

<script>
import cnt from './components/cnt.vue'



export default {
  components: { cnt },
  
  name: 'App',
 
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

