<template>
  <div class="cHeader">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'cHeader',
  data () {
    return {
      msg: 'Checkers!'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
.cHeader {
  background-color: #ff4154;
  color: #f8f8ff;
  padding: 2px;
  text-align: center;

}
</style>
