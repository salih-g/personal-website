<template>
	<div class="introduction">
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
.introduction {
	background-color: #323234;
	padding: 5px;
	width: 70%;

	border-radius: 10px;
	font-size: 14px;
}
</style>
