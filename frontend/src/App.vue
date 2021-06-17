<template>
  <div id="nav">
    <router-link to="/">Home</router-link>
    <router-link to="/portfolio">Portfolio</router-link>
  </div>
  <router-view/>
</template>
<style>
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
}



#nav {
  list-style-type: none;
  margin: 0;
  padding: 0;
  width:100%;
  overflow: hidden;
  background-color: #202020;
}
#nav a{
  display: inline-block;
  color: white;
  text-align: center;
  padding: 14px 10px;
  text-decoration: none;
  font-size:20px;
}


#nav a.router-link-exact-active {
  color: #FFDF6C;
}
#nav a:hover {
  background-color: #3F3F3F;
}
</style>
