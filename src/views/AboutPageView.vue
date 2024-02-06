<script>
import AboutComponent from '@/components/AboutPageComponents/AboutComponent.vue';
import KeyContributorsComponent from '@/components/AboutPageComponents/KeyContributorsComponent.vue';
import LinkComponent from '@/components/AboutPageComponents/LinkComponent.vue';

export default {
  name: "AboutPageView",
  components: {
    AboutComponent,
    KeyContributorsComponent,
    LinkComponent,
  }
}
</script>

<template>
  <div class="container">
    <AboutComponent />
    <KeyContributorsComponent />
    <LinkComponent />
  </div>
</template>

<style scoped>

.container {
  background: #05010D;
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  top: -100px;
}
</style>
