<script setup></script>

<template>
<div id="ft">
  <div class="footer">
    <div>
      <img alt="BoTHS Logo" src="@/assets/images/LandingPage/BoTHS-2-logo.png" />
    </div>
    <div class="footer-content">
      <p><a href="">X.COM</a></p>
      <p><a href="">DISCORD</a></p>
      <p><a href="">GITHUB</a></p>
    </div>
    <div class="footer-content">
      <p><router-link to="/play-game"><a>PLAY GAME</a></router-link></p>
      <p><router-link to="/about"><a>ABOUT</a></router-link></p>
      <p><a href="">FAQ</a></p>
    </div>
  </div>
</div>
</template>

<style scoped>

#ft {
  border-top: solid 0.5px #CF0512;
  background: #05010D;
  width: 100vw;
}

h1 {
  text-align: center;
  font-family: "Garnett";
  font-size: 48px;
  font-style: normal;
  font-weight: 800;
  line-height: normal;
}

.footer-content a {
  color: white;
  text-decoration: none;
  text-align: center;
  font-family: "DM Mono";
  font-size: 24px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}
.footer {
  display: flex;
  flex-direction: row;
  padding: 120px 140px 120px 120px;
  color: white;
  margin-top: 100px; 
}

.footer div {
  margin-left: 100px;
  height: 100%;
}

.footer img {
  margin-left: 10px;
} 

</style>