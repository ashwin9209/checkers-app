<template>
  <div class="cGridview">
    <table id="checkers-board">
    	<tr v-for="eachRow in size">
    		<td v-for="eachColumn in size">
    			<div id="blackbox" v-if="eachRow%2==eachColumn%2"></div>
    			<div id="whitebox" v-else></div>
    		</td>
    	</tr>
    </table>
  </div>
</template>

<script>
export default {
  name: 'cGridview',
  data () {
    return {
      msg: 'Grid',
      size: 8
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.cGridview {
	margin: 30px;
}

table {
	position: relative;
	margin: 0 auto;
	border: 1px solid black;
}

tr {
	border: 1px solid black;
}

td {
	border: 1px solid black;
	padding: 0px;
}

div#blackbox {
	padding: 30px;
	background-color: #888;
}

div#whitebox {
	padding: 30px;
	background-color: #eee;
}


</style>
