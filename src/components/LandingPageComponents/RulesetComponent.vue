<script>
export default {
  name: "RulesetComponent",
}
</script>

<template>
<div id="ruleset">
    <h1>RULESET OF THE GAME</h1>
    <div class="rules">
      <div class="btn-container">
        <p><a href="">SETUP THE CHESS BOARD</a></p>
      </div>
      <div class="btn-container">
        <p><a href="">LEARN TO MOVE THE PIECES</a></p>
      </div>
      <div class="btn-container">
        <p><a href="">SPECIAL RULES</a></p>
      </div>
      <div class="btn-container">
        <p><a href="">HOW TO WIN</a></p>
      </div>
      <div class="btn-container">
        <p><a href="">STUDY THE BASIC STRATEGIES</a></p>
      </div>
    </div>
</div>
</template>

<style scoped>

h1 {
  text-align: center;
  font-family: "Garnett";
  font-size: 48px;
  font-style: normal;
  font-weight: 800;
  line-height: normal;
  color: white;
}

#ruleset {
  margin-top: 200px;
  padding-bottom: 100px;
  background: #05010D;
}

.rules {
  margin-left: 30%;
  margin-right: 30%;
}

.btn-container p {
  background: rgba(5, 1, 13, 1);
  padding: 30px 4px 30px 4px;
  border-radius: 30px;
  margin: 2px 2px 2px 2px;
  text-align: center;
}

.btn-container {
  background: linear-gradient(180deg, #9017EF 2%, #CF0512 98%);
  width: 100%;
  padding: 0.2px;
  border-radius: 30px;
  margin-bottom: 10px;
}

#ruleset a {
  padding-top: 40px;
  padding-bottom: 40px;
  color: #FFF;
  text-align: center;
  font-family: "Garnett";
  font-size: 24px;
  font-style: normal;
  font-weight: 800;
  line-height: normal;
  text-decoration: none;
}

</style>