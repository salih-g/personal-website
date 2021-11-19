<template>
	<div class="introduction">
		<p class="text">{{ text }}</p>
	</div>
</template>

<script>
export default {
	name: 'Introduction',
	props: {
		text: String,
	},
};
</script>

<style scoped>
.introduction {
	background-color: #323234;
	padding: 5px;
	max-width: 500px;
	margin: 0 auto;
	border-radius: 10px;

	font-weight: 500;
	font-size: 14px;
	text-align: center;
}
</style>
