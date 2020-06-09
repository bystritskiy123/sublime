<template>
  <div id="app">
    <Header />
    <Aboutass />
    <Card />
  </div>
</template>

<script>
  import Header from './components/Header.vue'
  import Aboutass from './components/Aboutass.vue'
  import Card from './components/Card.vue'

  export default {
    name: 'App',
    components: {
      Header,
      Aboutass,
      Card
    }
  }
</script>

<style lang="scss">

</style>