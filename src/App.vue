<template>
	<!-- <div id="nav">
		<router-link to="/">Home</router-link> |
		<router-link to="/about">About</router-link>
	</div>
	<router-view/> -->
	<main>
		<h1>Vroom! Vroom!</h1>
		<h2>Aww, stoer hoor Nanko</h2>
		<h2>Ga je lekker spelen op je motorfietsje?</h2>
	</main>
</template>

<style lang="scss">
html, body {
	padding: 0;
	margin: 0;
	border: 0;
	background: black;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
//   color: #2c3e50;
	margin: 0;
	color: white;
	-webkit-text-stroke-width: 1px;
	-webkit-text-stroke-color: black;
	background: url('./assets/pp.jpeg');
	height: 100vh;
	width: 100vw;
	h1 {
		display: inline-block;
		padding: 3rem 0 0 0;
		font-size: 5vw;
	}
	h2 {
		font-size: 4vw;
	}
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
