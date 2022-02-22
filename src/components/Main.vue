<template>
	<main>
		<consultation-section />
		<sponsors-section />
		<client-service />
	</main>
</template>

<script>
import ConsultationSection from "./main-sections/ConsultationSection.vue";
import SponsorsSection from "./main-sections/SponsorsSection.vue";
import ClientService from "./main-sections/ClientService.vue";

export default {
	name: "Main",
	components: { ConsultationSection, SponsorsSection, ClientService },
};
</script>

<style scoped lang="scss">
@import "@/scss/style.scss";
section {
	margin-bottom: 60px;
	margin-top: 30px;
}
</style>
