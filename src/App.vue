<template>
  <div id="app">
    <p><a class="btn_a" href="#">aaa</a></p>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
  text-decoration: none;
}

.btn_a {
	width: 60px;
	height: 38px;
	background: #FFF;
	border: 1px solid #2a82a3;
	border-radius: 70px;
	-moz-border-radius: 70px;
	-webkit-border-radius: 70px;
	color: #2a82a3;
	padding: 42px 20px 20px;
	display: block;
	text-align: center;
	font-weight: bold;
	font-size: 120%;
	transition: background-color 0.5s ease-in;
	-webkit-transition: background-color 0.5s ease-in;
}
.btn_a:hover {
	background: #2a82a3;
	color: #FFF;
	border: 1px solid #FFF;
}
</style>
