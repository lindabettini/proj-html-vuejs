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
	background-image: url(../images/marketing-intro.jpg);
	background-position: center;
	background-repeat: no-repeat;
	background-size: contain;
	height: 400px;
}
</style>
