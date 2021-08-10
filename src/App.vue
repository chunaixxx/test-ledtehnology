<template>
	<main class="main"></main>

	<aside class="aside"></aside>
</template>

<script>
export default {
	name: 'App'
}
</script>

<style lang="scss">
* {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}

#app {
	min-height: 100vh;
	display: grid;
	grid-template-columns: 1fr 300px;
	padding: 30px;
}
</style>
