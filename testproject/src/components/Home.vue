<template>
  <div class="wrapper">
    <span>{{msg}}</span>
   </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" scoped>
.wrapper{
	text-align: center;
	margin-top:10px;
	color: blueviolet;
	font-size: 20px;
}
			
</style>
