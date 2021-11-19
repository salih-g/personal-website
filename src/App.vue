<template>
	<div id="app">
		<Navbar title="Salih Gumus" />
		<section class="body">
			<Introduction text="Hello, I'm full-stach developer based in Turkey!" />
		</section>
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
#app {
	width: 736px;
	margin: 0 auto;
}
.body {
	width: 534px;
	margin: 0 auto;
	padding-top: 40px;
}
</style>
