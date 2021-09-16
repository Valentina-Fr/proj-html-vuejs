<template>
  <div id="app">
    <Header :links="menuLinks"/>
    <Jumbo />
    <main>
      <Advisory />
      <Results />
      <Services />
    </main>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Jumbo from './components/Jumbo.vue'
import Advisory from './components/Advisory.vue'
import Results from './components/Results.vue'
import Services from './components/Services.vue'

export default {
  name: 'App',
  components: {
    Header,
    Jumbo,
    Advisory, 
    Results,
    Services
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
