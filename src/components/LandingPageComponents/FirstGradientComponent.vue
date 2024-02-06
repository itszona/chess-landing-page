<script>
export default {
  name: "FirstGradientComponent",
};
</script>

<template>
<div class="grad-1"></div>
</template>

<style scoped>

.grad-1 {
  position: absolute;
  z-index: 1;
  height: 700px;
  width: 80vw;
  background: linear-gradient(90deg, #05010D, #9017EF, #05010D);
  opacity: 0.02;
  top: 300px;
  border-radius: 100% 100% 0 0;
  margin: 0 auto;
  margin-left: 10%;
  margin-right: 10%;
}

</style>