<template>
  <div id="app">
    <Header />
    <Jumbo />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Jumbo from './components/Jumbo.vue'

export default {
  name: 'App',
  components: {
    Header,
    Jumbo,
  }
}
</script>

<style lang="scss">
@import "scss/style.scss";
</style>
