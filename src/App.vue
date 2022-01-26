<template>
  <div id="app">
    <title/>
  </div>
</template>

<script>
import title from './components/title.vue'

export default {
  name: 'App',
  components: {
    title
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
