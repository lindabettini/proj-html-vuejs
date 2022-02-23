<template>
	<section id="jumbotron">
		<div class="container">
			<div class="row">
				<div class="col-5">
					<h1>Unlock Your Online Growth Potential</h1>
					<p class="h4">Online marketing to secure customer retention, leads, and sales. We focus on the bigger picture.</p>
					<button class="white-btn">Our Services <font-awesome-icon icon="fa-solid fa-arrow-right" /></button>
				</div>
				<div class="col-7"><contact-us-form class="scale" /></div>
			</div>
		</div>
	</section>
</template>

<script>
import ContactUsForm from "./ContactUsForm.vue";
export default {
	name: "Jumbotron",
	components: { ContactUsForm },
};
</script>

<style scoped lang="scss">
@import "@/scss/style.scss";
#jumbotron {
	background-image: url(../images/marketing-intro.jpg);
	background-position: center;
	background-repeat: no-repeat;
	background-size: cover;
	height: 600px;
	margin: 0;
}

.col-5 {
	padding: 100px 0;
	color: white;
	h1 {
		font-size: 60px;
	}
	p {
		margin: 60px 0;
	}
	button {
		font-size: 18px;
	}
}
.col-7 {
	padding-top: 140px;
	.scale {
		transform: scale(0.8);
		// position: absolute;
		// bottom: -90px;
	}
}
</style>
