<template>
	<div class="main">
		<h3 class="title">I ♥</h3>
		<p>
			{{ hobys }}
		</p>
	</div>
</template>

<script>
export default {
	name: 'Love',
	props: {
		hobys: String,
	},
};
</script>

<style scoped>
.main {
	margin-top: 50px;
}
.title {
	border-bottom: 5px solid #525252;
	width: 35px;
}
</style>
