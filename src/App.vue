<template>
  <div id="app">
    <!--Long title='Conversor de unidades'/--> 
    <masa title='Conversor de masa' />
  </div>
</template>

<script>

//import Long from './components/long.vue'
import masa from  './components/masa.vue'

export default {
  name: 'App',
  components: {
    //Long,
    masa

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

