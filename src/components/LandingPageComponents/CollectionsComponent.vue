<script>
export default {
  name: "CollectionsComponent",
};
</script>

<template>
  <div id="collections">
    <h1>Collections</h1>
    <div class="grid-container">
      <div class="grid-item1"><img alt="royal" src="@/assets/images/LandingPage/royal.png" /></div>
      <div class="grid-item2"><img alt="royal" src="@/assets/images/LandingPage/black.png" /></div>
      <div class="grid-item3"><img alt="royal" src="@/assets/images/LandingPage/gold.png" /></div>
      <div class="grid-item4"><img alt="royal" src="@/assets/images/LandingPage/royal-2.png" /></div>
      <div class="grid-item5"><img alt="royal" src="@/assets/images/LandingPage/regular.png" /></div>
      <div class="grid-item6"><img alt="royal" src="@/assets/images/LandingPage/gold-2.png" /></div>
    </div>
    <button class="collection-btn">
      <p>SEE MORE</p>
    </button>
  </div>
</template>

<style scoped>

body {
  background: #05010D;
  height: 100vh;
  width: 100vw;
}

#collections {
  margin-top: 60px;
  margin-bottom: 60px;
  color: white;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  z-index: 1;
}


h1 {
  text-align: center;
  font-family: "Garnett";
  font-size: 48px;
  font-style: normal;
  font-weight: 800;
  line-height: normal;
}

p {
  text-align: center;
  font-family: "DM Mono";
  font-size: 24px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}

button {
  align-items: center;
  justify-content: center;
  text-align: center;
}
.collection-btn {
  width: 121px;
  height: 39px;
  border-radius: 8px;
  background: linear-gradient(94deg, #9017EF 0.64%, #700D6A 53.38%, #680B11 95.45%);
  border: 0.5px solid #FFF;
  color: white;
  margin-top: 20px;
}
.collection-btn p {
  font-size: 16px;
  align-items: center;
  text-align: center;
  margin: auto;
}
.grid-container {
  display: grid;
  column-gap: 60px;
  row-gap: 40px;
  padding-top: 60px;
  padding-bottom: 60px;
}

.grid-item1 {
  grid-column-start: 1;
  grid-column-end: 1;
  grid-row-start: 1;
  grid-row-end: 1;
}

.grid-item2 {
  grid-column-start: 2;
  grid-column-end: 2;
  grid-row-start: 1;
  grid-row-end: 1;
}

.grid-item3 {
  grid-column-start: 3;
  grid-column-end: 3;
  grid-row-start: 1;
  grid-row-end: 1;
}

.grid-item4 {
  grid-column-start: 1;
  grid-column-end: 1;
  grid-row-start: 2;
  grid-row-end: 2;
}

.grid-item5 {
  grid-column-start: 2;
  grid-column-end: 2;
  grid-row-start: 2;
  grid-row-end: 2;
}

.grid-item6 {
  grid-column-start: 3;
  grid-column-end: 3;
  grid-row-start: 2;
  grid-row-end: 2;
}

</style>