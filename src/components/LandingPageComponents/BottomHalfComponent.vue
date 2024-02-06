<script>
import PreviewComponent from "./PreviewComponent.vue";
import CollectionsComponent from "./CollectionsComponent.vue";
import RulesetComponent from "./RulesetComponent.vue";
import SecondGradientComponent from "./SecondGradientComponent.vue";

export default {
    name: "BottomHalfComponent",
    components: {
        PreviewComponent,
        CollectionsComponent,
        RulesetComponent,
        SecondGradientComponent,
    }
};
</script>

<template>
<div id="bottom-half">
    <div class="flex-container">    
      <PreviewComponent />
      <CollectionsComponent />
    </div>
    <RulesetComponent />
    <SecondGradientComponent />
</div>
</template>

<style scoped>

#bottom-half {
  background: #05010D;
  width: 100vw;
}

.flex-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin: 0 auto;
  color: white;
  position: relative;
  z-index: 3;
  top: -100px;
}

</style>