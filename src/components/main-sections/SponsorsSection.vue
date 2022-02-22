<template>
	<section id="sponsors-section" class="container text-center">
		<!-- SPONSORS LOGOS  -->
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
		<!-- PHONEBOOK  -->
		<div class="phonebook row justify-content-center align-items-center">
			<div class="col-4 d-flex">
				<img src="../../images/marketing-expert-cta.png" alt="marketing-expert-cta" />
				<div>
					<div class="h6">Sandy Reiff</div>
					<div class="text-little">Marketing Consultant Expert</div>
				</div>
			</div>
			<div class="col-4"><div class="h4">Drive Leads and Sales with Avada</div></div>
			<div class="col-4 text-end">
				<button class="light-btn">(555) 802-1567</button>
			</div>
		</div>
		<!-- LEADING ORGANISATION  -->
		<div id="leading-oganisation">
			<div class="row">
				<div class="col-12"><h2 class="m-3">Trusted by Leading Organisation</h2></div>
			</div>
			<div class="row">
				<div class="col-4 p-3">
					<img src="../../images/case-studies-1-1200x1349.jpg" alt="" />
					<p class="h3">How Spaces attracted five million visitors by improving the content</p>
					<div class="xl">200%</div>
					<p>Higher revenue from digital</p>
				</div>
				<div class="col-4 p-3">
					<img src="../../images/case-studies-4-1200x1349.jpg" alt="" />
					<p class="h3">Creativity helped Hemisferio to increase their brand reach vertically</p>
					<div class="xl">10X</div>
					<p>Sales increase with the same ad spend</p>
				</div>
				<div class="col-4 p-3">
					<img src="../../images/case-studies-6-1200x1349.jpg" alt="" />
					<p class="h3">How DigitalBox used AI-powered data insight to boost sales</p>
					<div class="xl">3-year</div>
					<p>Partnership with Avada Consultant</p>
				</div>
			</div>
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
	margin: 0 50px;
	height: 70px;
	-webkit-box-shadow: -1px 1px 18px 9px rgba(0, 0, 0, 0.85);
	box-shadow: -1px 1px 18px 9px rgba(0, 0, 0, 0.356);
	border-radius: 15px;
	.col-4 {
		max-height: 100%;
	}
	.h6 {
		margin-top: 10px;
		margin-bottom: 0;
	}
	img {
		height: 60px;
		width: 60px;
		border-radius: 50%;
		margin: 5px 15px;
	}
}

.text-little {
	font-size: 12px;
}

.xl {
	font-size: 50px;
	font-weight: bold;
}

#leading-oganisation {
	margin: 45px 0;
	img {
		max-width: 100%;
		margin-bottom: 10px;
	}
	.col-4 {
		text-align: start;
	}
}
</style>
