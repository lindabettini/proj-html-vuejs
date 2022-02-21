<template>
	<section class="jumbotron"></section>
</template>

<script>
export default {
	name: "Jumbotron",
};
</script>

<style scoped lang="scss">
@import "@/scss/style.scss";
.jumbotron {
	background-image: url(../images/jumb-bg.webp);
	background-position: center;
	background-repeat: no-repeat;
	background-size: cover;
	height: 500px;
}
</style>
