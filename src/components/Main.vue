<template>
	<main>
		<Consultation-section />
		<Sponsors-section />
	</main>
</template>

<script>
import ConsultationSection from "./main-sections/ConsultationSection.vue";
import SponsorsSection from "./main-sections/SponsorsSection.vue";
export default {
	name: "Main",
	components: { ConsultationSection, SponsorsSection },
};
</script>

<style scoped lang="scss">
@import "@/scss/style.scss";
</style>
