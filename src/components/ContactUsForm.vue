<template>
	<div class="contact-us-form">
		<img src="../images/marketing-consultant-expert.jpg" alt="" />

		<div class="h3">Richard Madsen</div>
		<div class="h4 text-muted">Marketing Consultant Expert</div>
		<div>
			<a href="#"><font-awesome-icon icon="fa-solid fa-phone" /> (555) 802-1234</a>
		</div>
		<input type="text" placeholder="Your Name**" />
		<input type="text" placeholder="Your Surame**" />
		<input type="text" placeholder="Your Phone Number**" />
		<button>Get A Callback</button>
		<div class="text-muted">By submitting my data I agree to be contacted</div>
	</div>
</template>

<script>
export default {
	name: "ContactUsForm",
};
</script>

<style scoped lang="scss">
@import "@/scss/style.scss";
.contact-us-form {
	padding: 30px;
	border-radius: 20px;
	background-color: white;
	color: black;
	text-align: center;
	width: 500px;
	img {
		width: 80px;
		height: 80px;
		border-radius: 50%;
	}
	a {
		color: $main-color;
		text-decoration: none;
	}
	input {
		padding: 15px 20px;
		width: 100%;
		margin: 10px 0;
		border-radius: 10px;
		border: 1px solid grey;
	}
	button {
		padding: 15px 20px;
		width: 100%;
	}
}
</style>
