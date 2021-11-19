<template>
	<div class="title">
		<p class="text">{{ text }}</p>
	</div>
</template>

<script>
export default {
	name: 'Navbar',
	props: {
		text: String,
	},
};
</script>

<style scoped>
.article {
}
</style>
