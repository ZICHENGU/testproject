<template>
  <div id="app">
  	<div class="app_wrapper">
  		<img src="./assets/logo.png">
    	<h1>Hello VUE</h1>
  	</div>
    
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="less">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;/*抗锯齿*/
  -moz-osx-font-smoothing: grayscale;
  .app_wrapper{
  		text-align: center;
  	  margin-top:60px ;
  	 h1{
	  	color: goldenrod;
	  	font-size: 30px;
  }
  }
 
}
</style>
