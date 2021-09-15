<template>
  <div id="app">
    <Header :links="menuLinks"/>
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
  },
  data(){
    return {
      menuLinks: [
        {
          text: 'Home',
          url: '#'
        },
        {
          text: 'About',
          url: '#'
        },
        {
          text: 'Services',
          url: '#'
        },
        {
          text: 'Team',
          url: '#'
        },
        {
          text: 'Blog',
          url: '#'
        },
      ]
    }
  }
}
</script>

<style lang="scss">
@import "scss/style.scss";
</style>
