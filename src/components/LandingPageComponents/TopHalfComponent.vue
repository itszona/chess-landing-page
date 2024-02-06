<script>
import NavbarComponent from './NavbarComponent.vue';
import InfoComponent from './InfoComponent.vue';
import CurveComponent from './CurveComponent.vue';
import FirstGradientComponent from './FirstGradientComponent.vue';

export default {
  name: "TopHalfComponent",
  components: {
    NavbarComponent,
    InfoComponent,
    CurveComponent,
    FirstGradientComponent,    
  }
}
</script>

<template>
<div id="top-half">
  <div class="bg-1">
    <NavbarComponent />  
    <div class="flex-container">
      <InfoComponent />      
    </div>
    <CurveComponent />
  </div>
  <FirstGradientComponent />
</div>
</template>

<style scoped>

#top-half {
  background: #05010D;
  padding-top: 100px;
  width: 100vw;
}

.bg-1 {
  height: 1440px;
  background-image: url(@/assets/images/LandingPage/view-chess-pieces-with-dramatic-mystical-background.png);
  background-size: cover;
  margin: 0;
}

.flex-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: white;
}

</style>
