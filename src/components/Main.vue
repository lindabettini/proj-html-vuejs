<template>
	<main>
		<Consultation-section />
	</main>
</template>

<script>
import ConsultationSection from "./main-sections/ConsultationSection.vue";
export default {
	name: "Main",
	components: { ConsultationSection },
};
</script>

<style scoped lang="scss">
@import "@/scss/style.scss";
</style>
