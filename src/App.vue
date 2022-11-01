<template>
  <div id="app">
    <MeteorShower/>
  </div>
</template>

<script>
import MeteorShower from '@/components/MeteorShower'

export default {
  name: 'App',
  components: {
    MeteorShower
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
