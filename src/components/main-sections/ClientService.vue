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
</style>
