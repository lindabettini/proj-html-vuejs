<template>
	<header class="container">
		<div class="row justify-content-center align-items-center">
			<nav class="col-12 d-flex justify-content-center align-items-center">
				<ul class="d-flex justify-content-center align-items-center">
					<li>
						<a href="#"><img src="../images/avada-marketing-logo.png" alt="" /></a>
					</li>
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
	</header>
</template>

<script>
export default {
	name: "Header",
};
</script>

<style scoped lang="scss">
@import "@/scss/style.scss";
header {
	height: 80px;
	.row {
		height: 100%;
		nav {
			height: 100%;
			ul {
				height: 100%;
				display: inline-flex;
				list-style-type: none;
				li a {
					color: black;
					text-decoration: none;
					padding: 15px;
					font-weight: bold;
				}
			}
		}
	}
}
</style>
