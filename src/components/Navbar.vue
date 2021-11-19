<template>
	<nav class="navbar">
		<h3 class="title">
			<a href="/" class="link">{{ title }} </a>
		</h3>
	</nav>
</template>

<script>
export default {
	name: 'Navbar',
	props: {
		title: String,
	},
};
</script>

<style scoped>
.navbar {
	height: 56px;
	margin: 0 auto;
}
.title {
	font-weight: bold;
	font-size: 18px;
}
</style>
