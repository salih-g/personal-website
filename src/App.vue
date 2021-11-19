<template>
	<div id="app" class="container">
		<Navbar title="Salih Gumus" />
		<article class="article">
			<Introduction text="Hello, I'm full-stack developer based in Turkey!" />
			<Title
				title="Salih Gumus"
				definition="Technologist (Full-Stack Developer)"
			/>
			<Work />
			<Bio />
		</article>
	</div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Introduction from './components/Introduction.vue';
import Title from './components/Title.vue';
import Work from './components/Work.vue';
import Bio from './components/Bio.vue';

export default {
	name: 'App',
	components: {
		Navbar,
		Introduction,
		Title,
		Work,
		Bio,
	},
};
</script>

<style scoped>
.container {
	margin: 0 auto;
	max-width: 768px;
	margin-top: 50px;
}
.article {
	margin: 0 auto;
	padding-top: 40px;
	max-width: 500px;
}
</style>
