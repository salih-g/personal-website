<template>
	<div id="app" class="container">
		<Navbar title="Salih Gumus" />
		<article class="article">
			<Introduction text="Hello, I'm full-stack developer based in Turkey!" />
		</article>
	</div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Introduction from './components/Introduction.vue';

export default {
	name: 'App',
	components: {
		Navbar,
		Introduction,
	},
};
</script>

<style scoped>
.container {
	margin: 0 auto;
	max-width: 768px;
}
.article {
	margin: 0 auto;
	padding-top: 40px;
}
</style>
