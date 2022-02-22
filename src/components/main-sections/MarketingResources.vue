<template>
	<section id="marketing-resources" class="container">
		<div class="row">
			<div class="col-6">
				<div class="h1">
					Marketing Resources: <br />
					Insider Advice on How to Increase Online Sales
				</div>
			</div>
			<div class="col-6 text-end align-self-end">
				<button class="mb-3 font-20">Explore All Resources</button>
			</div>
		</div>
		<!-- CARDS  -->
		<div class="row mt-7">
			<div class="col-4">
				<img class="img-fluid" src="../../images/blog-posts-6-1200x800.jpg" alt="" />
				<div class="h2">Marketing Tips And Tricks For Your Website</div>
			</div>
			<div class="col-4">
				<img class="img-fluid" src="../../images/blog-posts-5-1200x800.jpg" alt="" />
				<div class="h2">How to Write Stunning Blog Post Titles</div>
			</div>
			<div class="col-4">
				<img class="img-fluid" src="../../images/blog-posts-4-1200x800.jpg" alt="" />
				<div class="h2">Techniques to Reduce Facebook Ads Spend</div>
			</div>
		</div>
	</section>
</template>

<script>
export default {
	name: "MarketingResources",
};
</script>

<style scoped lang="scss">
@import "@/scss/style.scss";
.font-20 {
	font-size: 20px;
}

img {
	margin-bottom: 30px;
}

.mt-7 {
	margin-top: 70px;
}
</style>
