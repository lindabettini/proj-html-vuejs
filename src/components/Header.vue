<template>
	<header>ciao</header>
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
	color: $main-color;
}
</style>
