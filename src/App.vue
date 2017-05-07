<template>
  <div id="app">    
    <cHeader></cHeader>
    <cGridview></cGridview>
    <cFooter></cFooter>
  </div>
</template>

<script>
import cHeader from './components/header'
import cGridview from './components/gridview'
import cFooter from './components/footer'

export default {
  name: 'app',
  components: {
    cHeader, cGridview, cFooter
  }
}
</script>

<style>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: Tahoma, Helvetica, sans-serif;
  font-size: 1.2em;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
