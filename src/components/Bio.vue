<template>
	<div class="main">
		<h3 class="title">Bio</h3>
		<div class="bio">
			<div class="born">
				<span class="span">1995</span>
				Born in Adana Turkey.
			</div>
			<br />
			<div class="school">
				<span class="span">2018</span>
				I'm currently studying Computer Engineering in Duzce University
			</div>
			<br />
			<div class="work">
				<span class="span">Dec 2021</span>
				I started to work at Modanisa as a Full-Stack developer
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

.span {
	font-size: 20px;
	display: inline-block;
	margin-right: 10px;
}
</style>
