<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <h1>Ciao ragazzi!</h1>
    <HelloVue />
  </div>
</template>

<script>
import HelloVue from '@/components/HelloVue.vue'

export default {
  name: 'App',
  components: {
    HelloVue
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
