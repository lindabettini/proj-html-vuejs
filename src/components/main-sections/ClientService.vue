<template>
	<section id="client-service" class="container">
		<!-- "Optimizing Growth Potential"  -->
		<div id="growth-potential" class="row align-items-center">
			<div class="col-6 p-3">
				<div class="h1">We Boost Our Clients’ Bottom Line by Optimizing Their Growth Potential.</div>
				<p>Quisque aliquet, libero consequat elementum convallis, erat risus imperdiet pellentesque sem neque eget.</p>
				<button>Why Work With Us</button>
			</div>
			<div class="col-6"><img class="img-fluid" src="../../images/we-boost-our-clients-1200x1098.jpg" alt="" /></div>
		</div>
		<!-- Why work with us resons  -->
		<div id="why-us" class="row align-items-center">
			<div class="col-6 p-r-5">
				<div class="m-b-4">
					<div class="h2">We Build Relationships</div>
					<p class="font-20">Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.</p>
				</div>
				<div>
					<div class="h2">Proprietary Processes</div>
					<p class="font-20">Facere nihil voluptates tempora culpa quisquam, assumenda ipsum, quaerat nulla facilis quia ex repudiandae molestiae.</p>
				</div>
			</div>
			<div class="col-6">
				<div class="row mb-3 align-items-center">
					<div class="col-4 text-end">
						<img src="../../images/accountability.png" alt="" />
					</div>
					<div class="col-8">
						<h5 class="bold">Accountability</h5>
						<p class="font-20">Curabitur ac leo nunc vestibulum</p>
					</div>
				</div>
				<!-- LIST RIGHT SIDE -->
				<div class="row mb-3 align-items-center">
					<div class="col-4 text-end">
						<img src="../../images/transparency.png" alt="" />
					</div>
					<div class="col-8">
						<h5 class="bold">Transparency</h5>
						<p class="font-20">Curabitur ac leo nunc vestibulum</p>
					</div>
				</div>
				<div class="row mb-3 align-items-center">
					<div class="col-4 text-end">
						<img src="../../images/investment.png" alt="" />
					</div>
					<div class="col-8 align-self-start">
						<h5 class="bold">Investment</h5>
						<p class="font-20">Curabitur ac leo nunc vestibulum</p>
					</div>
				</div>
			</div>
		</div>
		<!-- AWARDS  -->
		<div id="awards">
			<div class="row justify-content-center">
				<div class="col-12"><div class="h2 text-center">Awards</div></div>
			</div>
			<div class="row justify-content-center">
				<div class="col-3 text-center">
					<img class="filter-blue" src="../../images/award-a-200x191.png" alt="award logo" />
					<p>Winner Seo Master MAGT Smart Start Award 2017</p>
				</div>
				<div class="col-3 text-center">
					<img src="../../images/award-b-200x191.png" alt="award logo" />
					<p>Top Social Media Agencies Next Partner 2018</p>
				</div>
				<div class="col-3 text-center">
					<img class="filter-red" src="../../images/award-c-200x191.png" alt="award logo" />
					<p>10 Fastest Growing Abstract Solution Providers 2019</p>
				</div>
				<div class="col-3 text-center">
					<img src="../../images/award-d-200x191.png" alt="award logo" />
					<p>National Excellence Agencie Award Winner 2020</p>
				</div>
			</div>
		</div>
		<!-- CLIENT QUOTE  -->
		<div id="client-quote" class="row align-items-center">
			<div class="col-6"><img class="img-fluid rounded" src="../../images/large-testimonial-1200x1166.jpg" alt="" /></div>
			<div class="col-6">
				<div class="h2 mb-3">
					“The team at Avada Marketing Consultant is fabulous. They helped us unlock our potential online and offline. We have experienced year on year growth due to their progressive approach.”
				</div>
				<div class="h4 mb-3">Kate Schadler</div>
				<p>Marketing Consultant – Abstract</p>
			</div>
		</div>
	</section>
</template>

<script>
export default {
	name: "ClientService",
};
</script>

<style scoped lang="scss">
@import "@/scss/style.scss";

// Utils

.font-20 {
	font-size: 20px;
}

.bold {
	font-weight: bold;
}

.m-b-4 {
	margin-bottom: 40px;
}
.p-r-5 {
	padding-right: 50px;
}

#growth-potential {
	margin-bottom: 70px;
	p {
		margin: 40px 0;
		font-size: 24px;
	}
}

#awards {
	margin: 60px 0;
	p {
		font-size: 20px;
	}
	img {
		max-width: 130px;
		height: auto;
		margin-top: 50px;
	}
	img.filter-blue {
		filter: brightness(0) saturate(100%) invert(38%) sepia(40%) saturate(5711%) hue-rotate(189deg) brightness(97%) contrast(103%);
	}
	img.filter-red {
		filter: brightness(0) saturate(100%) invert(50%) sepia(23%) saturate(5437%) hue-rotate(327deg) brightness(111%) contrast(99%);
	}
}

#client-quote .col-6 {
	padding: 60px;
}
</style>
