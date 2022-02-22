<template>
	<main>
		<consultation-section />
		<sponsors-section />
		<client-service />
		<marketing-resources />
		<contact-us />
	</main>
</template>

<script>
import ConsultationSection from "./main-sections/ConsultationSection.vue";
import SponsorsSection from "./main-sections/SponsorsSection.vue";
import ClientService from "./main-sections/ClientService.vue";
import MarketingResources from "./main-sections/MarketingResources.vue";
import ContactUs from "./main-sections/ContactUs.vue";

export default {
	name: "Main",
	components: { ConsultationSection, SponsorsSection, ClientService, MarketingResources, ContactUs },
};
</script>

<style scoped lang="scss">
@import "@/scss/style.scss";
section {
	margin-bottom: 60px;
	margin-top: 30px;
}
</style>
