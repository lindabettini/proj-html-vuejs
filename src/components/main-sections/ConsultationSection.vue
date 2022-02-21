<template>
	<section id="Consultation-section" class="container">
		<!-- BUSINESS GROWTH  -->
		<div class="row justify-content-center align-items-center">
			<div class="col-6">
				<img src="../../images/analist1.png" alt="" />
			</div>
			<div class="col-6 p-100">
				<div>
					<img src="" alt="" />
					<h5>Business Growth</h5>
				</div>
				<div class="h1">Increase brand Awarness</div>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor placerat luctus. Nullam sit amet ante sed orci convallis gravida et at massa.</p>
				<button>Get A Consultation</button>
			</div>
		</div>
		<!-- INVESTORS IN PEOPLE  -->
		<div class="row justify-content-center align-items-center">
			<div class="col-6 p-100">
				<h5>Investors In People</h5>
				<div class="h1">In-House Sales Training</div>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor placerat luctus. Nullam sit amet ante sed orci convallis gravida et at massa.</p>
				<button>Get A Consultation</button>
			</div>
			<div class="col-6">
				<img src="../../images/analist2.png" alt="" />
			</div>
		</div>
		<!-- SOCIAL MEDIA ANALIST  -->
		<div class="row justify-content-center align-items-center">
			<div class="col-6">
				<img src="../../images/analist3.png" alt="" />
			</div>
			<div class="col-6 p-100">
				<div>
					<img src="" alt="" />
					<h5>Social Media Analysis</h5>
				</div>
				<div class="h1">Harness Your Social Proof</div>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor placerat luctus. Nullam sit amet ante sed orci convallis gravida et at massa.</p>
				<button>Get A Consultation</button>
			</div>
		</div>
	</section>
</template>

<script>
export default {
	name: "ConsultationSection",
};
</script>

<style scoped lang="scss">
@import "@/scss/style.scss";
button {
	background-color: $main-color;
	border-radius: 10px;
	color: white;
	border: 1px solid $main-color;
	padding: 10px 30px;
}

.col-6 {
	margin: 20px 0;
}

.col-6.p-100 {
	padding: 0 100px;
	p {
		font-size: 20px;
	}
}

img {
	max-width: 100%;
}
</style>
