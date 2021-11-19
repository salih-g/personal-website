<template>
	<div class="main">
		<h3 class="title">Bio</h3>
		<div class="bio">
			<div class="born">
				<h4>1995</h4>
				<p>Born in Adana Turkey</p>
			</div>
			<br />
			<div class="school">
				<h4>1995</h4>
				<p></p>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: 'Bio',
	props: {},
};
</script>

<style scoped>
.main {
	margin-top: 50px;
}
.title {
	border-bottom: 5px solid #525252;
	width: 30px;
}
.born h4 {
	font-size: 20px;
}
</style>
