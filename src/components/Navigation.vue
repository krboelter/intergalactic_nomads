<template>
	<nav>
		<router-link class="intergelactic-nomads" to="/">Intergelactic Nomads</router-link>
		<div class="nav-menu">
			<router-link to="/">Home</router-link>
		</div>
	</nav>
</template>

<script>
export default {
	name: "navigation"
}
</script>

<style>
nav {
	display: flex;
  flex-direction: row;
	justify-content: space-between;
  align-items: center;
  height: 60px;
  padding: 0 20px;
}

.intergelactic-nomads {
	text-decoration: none;
	color: white;
  font-size: 30px;
  font-weight: bold;
}

.nav-menu {
	display: flex;
}

.nav-menu a {
	text-decoration: none;
	color: white;
  padding: 15px 35px;
  border-radius: 6px;
  transition-duration: 500ms;
}

.nav-menu a:hover {
  box-shadow: 0 0 6px white;
}
</style>