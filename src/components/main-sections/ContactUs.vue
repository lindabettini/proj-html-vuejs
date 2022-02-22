<template>
	<section id="contact-us">
		<div class="container">
			<div class="ror">
				<div class="col-6">
					<div class="h1 m-tb-4">Let’s Make Things Happen</div>
					<div class="h3 m-tb-4 bold">Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.</div>
					<hr width="100px" color="white" />
					<div class="h4 m-tb-4 italic">
						“The team at Avada Marketing Consultant is fabulous. They helped us unlock our potential online and offline. We have experienced year on year growth due to their progressive approach.”
					</div>
					<div class="h6 m-tb-4">
						George Anderson <br />
						Digitalbox CEO
					</div>
				</div>
				<div class="col-6"></div>
			</div>
		</div>
	</section>
</template>

<script>
export default {
	name: "ContactUs",
};
</script>

<style scoped lang="scss">
@import "@/scss/style.scss";

#contact-us {
	background-color: black;
	color: white;
	padding: 60px 0;
}

.m-tb-4 {
	margin-top: 40px;
	margin-bottom: 40px;
}

.bold {
	font-weight: bold;
}

.italic {
	font-style: italic;
}
</style>
