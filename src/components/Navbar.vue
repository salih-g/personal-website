<template>
	<nav class="navbar">
		<span class="title">
			<a href="/" class="link">{{ title }} </a>
		</span>
		<a
			href="https://github.com/sudanmerinosu/"
			target="_blank"
			class="link hover"
		>
			Works
		</a>
		<a
			href="https://github.com/sudanmerinosu/personal-website"
			target="_blank"
			class="link hover"
			><i class="fab fa-github"></i> Source
		</a>
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
	margin-top: -30px;
}
.navbar a {
	margin-right: 40px;
}
.title {
	font-weight: bold;
	font-size: 18px;
	margin-right: 10px;
}
.hover:hover {
	text-decoration: underline;
}
</style>
