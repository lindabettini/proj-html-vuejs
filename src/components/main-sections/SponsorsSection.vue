<template>
	<section id="sponsors-section" class="container text-center">
		<div class="h1 m-3">Some Brands We Work With</div>
		<div>Libero quae quaerat, tempora unde illum est.</div>
		<ul>
			<li>
				<a href="#"><img src="../../images/abstract.png" alt="" /></a>
			</li>
			<li>
				<a href="#"><img src="../../images/cglobal.png" alt="" /></a>
			</li>
			<li>
				<a href="#"><img src="../../images/next.png" alt="" /></a>
			</li>
			<li>
				<a href="#"><img src="../../images/hemisferio.png" alt="" /></a>
			</li>
			<li>
				<a href="#"><img src="../../images/spaces.png" alt="" /></a>
			</li>
			<li>
				<a href="#"><img src="../../images/digitalbox.png" alt="" /></a>
			</li>
		</ul>
		<div class="phonebook row">
			<div class="col-4 d-flex">
				<img src="../../images/marketing-expert-cta.png" alt="marketing-expert-cta" />
				<div>
					<div class="h6">Sandy Reiff</div>
					<div class="text-little">Marketing Consultant Expert</div>
				</div>
			</div>
			<div class="col-4"></div>
			<div class="col-4"></div>
		</div>
	</section>
</template>

<script>
export default {
	name: "SponsorsSection",
};
</script>

<style scoped lang="scss">
@import "@/scss/style.scss";
ul {
	list-style-type: none;
	margin: 30px 0;
	li {
		display: inline;
		a {
			padding: 20px;
			img {
				width: 150px;
			}
		}
	}
}

.phonebook {
	height: 50px;
	.col-4 {
		max-height: 100%;
	}
	img {
		max-height: 100%;
		width: auto;
		border-radius: 50%;
		margin-right: 10px;
	}
}

.text-little {
	font-size: 12px;
}
</style>
