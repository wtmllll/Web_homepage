<template>
  
  <H_ComponentVue/>
  <Function_appVue/>
</template>

<script>

import H_ComponentVue from './components/H_Component.vue'
import Function_appVue from './components/Function_app.vue'

export default {
  name: 'App',
  components: {
    Function_appVue,
    H_ComponentVue,
   
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
</style>
