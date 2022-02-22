<template>
	<section id="jumbotron"></section>
</template>

<script>
export default {
	name: "Jumbotron",
};
</script>

<style scoped lang="scss">
@import "@/scss/style.scss";
#jumbotron {
	background-image: url(../images/marketing-intro.jpg);
	background-position: center;
	background-repeat: no-repeat;
	background-size: cover;
	height: 500px;
	margin: 0;
}
</style>
