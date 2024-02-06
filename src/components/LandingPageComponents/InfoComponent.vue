<script>
export default {
  name: "InfoComponent",
};
</script>

<template>
<div id="info">
    <h1>BLITZ OF THE HIDDEN<br>SOLDIERS</h1>
    <p>Lorem ipsum dolor sit amet consectetur. Aliquet gravida augue sit sit a mauris. Tincidunt tristique etiam vitae auctor sagittis.</p>
</div>
</template>

<style scoped>

#info {
    margin-top: 280px;
    display: flex;
    flex-direction: column;
    margin-left: 20%;
    margin-right: 20%;
    z-index: 1;
}

h1 {
  text-align: center;
  font-family: "Garnett";
  font-size: 60px;
  font-style: normal;
  font-weight: 800;
  line-height: normal;
  margin-top: 20px;
  padding-bottom: 0px;
}

p {
  text-align: center;
  font-family: "DM Mono";
  font-size: 24px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  margin-top: 10px;
}
</style>