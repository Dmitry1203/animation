<template>
  <div id="app">
    <opros/>
  </div>
</template>

<script>
  import Opros from './components/Opros.vue'
  export default {
    name: 'app',
    components: {
      Opros
    }
  }
</script>

<style>
  @import './../node_modules/animate.css/animate.min.css';
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>