<template>
	<div class="main">
		<h3 class="title">{{ title }}</h3>
		<p class="definition">{{ definition }}</p>
	</div>
</template>

<script>
export default {
	name: 'Title',
	props: {
		title: String,
		definition: String,
	},
};
</script>

<style scoped>
.main {
	margin: 0 auto;
	line-height: 2px;
}
.title {
	font-weight: 600;
	font-size: 24px;
	margin-top: 50px;
}
</style>
