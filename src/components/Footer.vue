<template>
	<footer class="container">
		<div class="row">
			<div class="col-5">
				<div class="h2">Grow Your Online Business Strategically, and Improve Customer Retention.</div>
				<div class="social-icons">
					<a href="#"><font-awesome-icon icon="fa-brands fa-facebook-f" /></a>
					<a href="#"><font-awesome-icon icon="fa-brands fa-twitter" /></a>
					<a href="#"><font-awesome-icon icon="fa-brands fa-instagram" /></a>
					<a href="#"><font-awesome-icon icon="fa-brands fa-youtube" /></a>
					<a href="#"><font-awesome-icon icon="fa-brands fa-linkedin-in" /></a>
					<a href="#"><font-awesome-icon icon="fa-brands fa-tiktok" /></a>
				</div>
			</div>
			<nav class="col" v-for="(menu, index) in menus" :key="index">
				<h6 class="bold">{{ menu.title }}</h6>
				<ul>
					<li v-for="(item, index) in menu.items" :key="index">
						<a href="#">{{ item }}</a>
					</li>
				</ul>
			</nav>
		</div>
	</footer>
</template>

<script>
export default {
	name: "Footer",
	data() {
		return {
			menus: [
				{
					title: "Services",
					items: ["Marketing", "Plan", "Sales Development", "Digital Marketing", "Pricing", "Why Us", "Case Studies"],
				},
				{
					title: "Resources",
					items: ["Learning Center", "Video Tutorials", "Customers", "Blog"],
				},
				{
					title: "Company",
					items: ["Who We Are", "Contact Us", "Careers"],
				},
			],
		};
	},
};
</script>

<style scoped lang="scss">
@import "@/scss/style.scss";

.social-icons a {
	color: black;
	margin: 7px 10px 7px 0;
	padding: 7px 10px 7px 0;
	font-size: 25px;
}

ul {
	list-style-type: none;
	padding-left: 0;
	li {
		margin: 15px 0;
		&:hover {
			border-right: 2px solid $main-color;
		}
		a {
			width: 100%;
			padding: 10px 0;
			text-decoration: none;
			color: black;
			&:hover {
				color: $main-color;
			}
		}
	}
}

.bold {
	font-weight: bold;
}
</style>
