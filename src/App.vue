<template>
	<div id="app" class="container-fluid">
		<Header />
		<Jumbotron />
		<Main />
		<Footer />
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
@import "@/scss/style.scss";
#app {
	font-family: $main-font;
	h1 {
		font-size: 50px;
		font-weight: bold;
	}
	.h1 {
		font-size: 50px;
		font-weight: bold;
	}
	h2 {
		font-weight: bold;
	}
	.h2 {
		font-weight: bold;
	}

	button {
		background-color: $main-color;
		color: white;
		border-radius: 10px;
		border: 1px solid $main-color;
		padding: 10px 30px;
		&:hover {
			background-color: rgb(206, 81, 14);
		}
	}

	button.light-btn {
		color: $main-color;
		font-weight: bold;
		background-color: $pink;
		border-radius: 10px;
		border: 1px solid $pink;
		padding: 10px 30px;
		&:hover {
			background-color: $main-color;
			color: white;
			border: 1px solid $main-color;
		}
	}

	button.white-btn {
		background-color: white;
		border: 2px solid black;
		color: black;
		&:hover {
			background-color: transparent;
			color: white;
			border: 2px solid white;
		}
	}
}
</style>
