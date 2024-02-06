<template>
<div>
    <TopHalfComponent />
    <BottomHalfComponent />
    <FooterComponent />
</div>
</template>
    
<script>
    
import TopHalfComponent from "@/components/LandingPageComponents/TopHalfComponent.vue";
import BottomHalfComponent from "@/components/LandingPageComponents/BottomHalfComponent.vue";
import FooterComponent from "@/components/LandingPageComponents/FooterComponent.vue";

export default {
    name: "LandingPageView",
    components: {
        TopHalfComponent,
        BottomHalfComponent,
        FooterComponent,
    }
}
    
</script>
    
<style scoped>
div {
    margin: 0;
    padding: 0;
}
</style>



