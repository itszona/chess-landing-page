<template>
<div class="container">
  <div id="navbar">
  <div class="nav">
    <div class="nav-grid">
      <div class="grid-item1">
        <router-link to="/"
          ><img alt="BoTHS Logo" src="@/assets/images/LandingPage/BoTHS-logo.png"
        /></router-link>
      </div>
      <div class="grid-item2">
        <div class="grid-2">
          <div class="grid-2-item1">
            <p class="un"><a href="#preview">Preview</a></p>
          </div>
          <div class="grid-2-item2">
            <p class="un">
              <a href="#collections">Collections</a>
            </p>
          </div>
          <div class="grid-2-item3">
            <p class="un">
              <a href="https://boths.gitbook.io/blitz-of-the-hidden-soldiers-wiki">Tutorial</a>
            </p>
          </div>  
        </div>  
      </div>
      <div class="grid-item3">
        <div class="btn">
          <div class="game-text">
            <p><router-link to="play-game"><a>Play Game</a></router-link></p>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
</div>  
</template>

<script>
export default {
  name: "NavbarComponent",
};
</script>

<style scoped>

.container {
  height: 20px;
}
.nav {
  margin: 0 auto;
  margin-left: 10%;
  margin-right: 10%;
  border: solid white 1px;
  border-radius: 30px;
  align-items: center;
  justify-items: center;
}

.nav-grid {
  display: grid;
  align-items: center;
  justify-items: center;
  margin: 0 auto;
  padding: 10px 5px 10px 5px;
}

.grid-2 {
  display: grid;
  align-items: center;
  justify-items: center;
  margin: 0 auto;
  column-gap: 100px;
}

.grid-item1 {
  grid-column-start: 1;
  grid-column-end: 1;
  grid-row-start: 1;
  grid-row-end: 1;
}

.grid-item1 img {
  background-size: contain;
}

.grid-item2 {
  grid-column-start: 2;
  grid-column-end: 2;
  grid-row-start: 1;
  grid-row-end: 1;
  margin-left: 80px;
}

.grid-2-item1 {
  grid-column-start: 1;
  grid-column-end: 1;
  grid-row-start: 1;
  grid-row-end: 1;
  padding: 0px;
  margin: 0;
}

.grid-2-item2 {
  grid-column-start: 2;
  grid-column-end: 2;
  grid-row-start: 1;
  grid-row-end: 1;
  padding: 0px;
  margin: 0;
}

.grid-2-item3 {
  grid-column-start: 3;
  grid-column-end: 3;
  grid-row-start: 1;
  grid-row-end: 1;
  padding: 0px;
  margin: 0;
}

.grid-item3 {
  grid-column-start: 3;
  grid-column-end: 3;
  grid-row-start: 1;
  grid-row-end: 1;
  margin-left: 20px;
  align-items: center;
}


.game-text {
  border-radius: 20px;
  background: linear-gradient(94deg,#9017ef 0.64%,#700d6a 53.38%,#680b11 95.45%);
  border: 0.5px solid #fff;
  align-items: center;
  text-align: center;
  margin-top: 10px;
  margin-bottom: 10px;
}
.game-text p {
  padding-left: 40px;
  padding-right: 40px;
  font-size: 24px;
  color: #fff;
  text-align: center;
  font-family: "DM Mono";
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  align-items: center;
}

.btn {
  padding: 0px;
  align-items: center;

}

a {
  color: white;
  text-decoration: none;
}

.un {
  display: inline-block;
  padding-bottom: 2px;
  background-image: linear-gradient(#fff 0 0);
  background-position: 0 100%;
  background-size: 0% 2px;
  background-repeat: no-repeat;
  transition: background-size 0.3s, background-position 0s 0.3s;
  color: #fff;
  text-align: center;
  font-family: "DM Mono";
  font-size: 22px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}

.un:hover {
  background-position: 100% 100%;
  background-size: 100% 2px;
}
</style>
