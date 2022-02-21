<template>
	<header>
		<div class="container">
			<div class="row">
				<nav class="col-12">
					<ul>
						<li><a href="#">Home</a></li>
						<li><a href="#">Services</a></li>
						<li><a href="#">Why Us</a></li>
						<li><a href="#">Case Studies</a></li>
						<li><a href="#">About</a></li>
						<li><a href="#">Blog</a></li>
						<li><a href="#">(555) 802-1234</a></li>
						<li><a href="#">Free Quote</a></li>
					</ul>
				</nav>
			</div>
		</div>
	</header>
</template>

<script>
export default {
	name: "Header",
	props: {
		msg: String,
	},
};
</script>

<style scoped lang="scss">
@import "@/scss/style.scss";
header {
	height: 80px;
	ul {
		display: inline-flex;
		list-style-type: none;
		li a {
			color: black;
			text-decoration: none;
			padding: 15px;
		}
	}
}
</style>
