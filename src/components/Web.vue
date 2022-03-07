<template>
	<div class="main">
		<h3 class="title">On the Web</h3>
		<span>
			<a
				href="https://github.com/salih-g/"
				target="_blank"
				class="link hover"
			>
				<i class="fab fa-github"></i> @salih-g
			</a>
		</span>
		<span>
			<a
				href="https://gitlab.com/salih-g/"
				target="_blank"
				class="link hover"
			>
				<i class="fab fa-gitlab"></i> @salih-g
			</a>
		</span>
		<span>
			<a
				href="https://twitter.com/sudanmerinosu/"
				target="_blank"
				class="link hover"
			>
				<i class="fab fa-twitter"></i> @sudanmerinosu
			</a>
		</span>
		<span>
			<a
				href="https://www.instagram.com/sudanmerinosu/"
				target="_blank"
				class="link hover"
			>
				<i class="fab fa-instagram"></i> @sudanmerinosu
			</a>
		</span>
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
.main span {
	display: block;
	margin-bottom: 20px;
	color: lightpink;
	font-weight: 600;
}
.title {
	border-bottom: 5px solid #525252;
	width: 120px;
}
.hover {
	padding: 10px;
	border-radius: 5px;
}
.hover:hover {
	background-color: rgba(255, 182, 193, 0.39);
}
</style>
