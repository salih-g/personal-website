<template>
	<div class="main">
		<h3 class="work">Work</h3>
		<p class="prag">
			I'm currently working as a Full Stack developer and the way we work 
			<ul>
				<li>Continuous Integration with Gitlab</li>
				<li>High-quality product supported with ATDD/TDD, integration tests, unit tests, CDC tests</li>
				<li>Highly scalable microservice architecture</li>
				<li>Restful API with Golang</li>
				<li>Database migrations for services</li>
				<li>Micro Frontend architecture by Vue</li>
				<li>Pair Programming</li>
				<li>Agile work model</li>
			</ul>  
		</p>
	</div>
</template>

<script>
export default {
	name: 'Work',
	props: {},
};
</script>

<style scoped>
.main {
	margin-top: 50px;
}
.work {
	border-bottom: 5px solid #525252;
	width: 60px;
}
</style>
