<template>
	<div id="app">
		<Header />
		<Main />
		<Footer />
		<Jumbotron />
	</div>
</template>

<script>
import Header from "./components/Header.vue";
import Jumbotron from "./components/Jumbotron.vue";
import Main from "./components/Main";
import Footer from "./components/Footer.vue";

export default {
	name: "App",
	components: { Header, Jumbotron, Main, Footer },
};
</script>

<style lang="scss">
@import "@/scss/_vars.scss";
#app {
	font-family: $main-font;
}
</style>
