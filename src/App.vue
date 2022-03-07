<template>
  <div id="app">
    <title_first/>
    <hero_jumbo/>
  </div>
</template>

<script>
import title_first from './components/title_first.vue'
import hero_jumbo from './components/hero_jumbo.vue'

  export default {
	components: {
      title_first,
      hero_jumbo,
    }	
  };
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
