<template>
	<footer>
		<div class="row">
			<div class="col-6"></div>
			<div class="col-2" v-for="(menu, index) in menus" :key="index">
				<h6>{{ menu.title }}</h6>
				<ul>
					<li v-for="(item, index) in menu.items" :key="index">{{ item }}</li>
				</ul>
			</div>
			<div class="col-2"></div>
			<div class="col-2"></div>
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
					items: ["uno", "due", "tre"],
				},
				{
					title: "Services",
					items: ["uno", "due", "tre"],
				},
			],
		};
	},
};
</script>

<style scoped lang="scss">
@import "@/scss/style.scss";
</style>
