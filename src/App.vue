<template>
  <div id="app">
    <Title header="Order Pizza"/>
    <Container />
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Container from './components/Container.vue'

export default {
  name: 'App',
  components: {
    Title,Container
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
