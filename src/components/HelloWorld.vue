<template>
  <div class="hello">
    <h1>{{ header }}</h1>
    <div class="container">

    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    header: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
  color: blue;
}
</style>
