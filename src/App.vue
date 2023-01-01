<template>
  <div id="app">
     <Content_Header/>
   
  </div>
</template>

<script>
import Content_Header from './components/Content_Header.vue'

export default {
  name: 'App',
  components: {
    Content_Header
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
