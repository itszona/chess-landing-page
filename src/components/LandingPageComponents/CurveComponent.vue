<script>
export default {
    name: "CurveComponent",
};
</script>

<template>
<div id="curve">
    <div class="curve-1"></div>
    <div class="curve-2"></div>
    <div class="curve-3"></div>
</div>
</template>

<style scoped>

#curve {
    margin: 0 auto;
    align-items: center;
    justify-content: center;
    position: absolute;
    top: 1200px;
    width: 100vw;
}
.curve-1 {
    position: absolute;
    top: 0px;
    background-color: #05010D;
    border-radius: 150% 150% 0 0;
    background: linear-gradient(90deg, #05010D, #9017EF, #05010D);
    padding-bottom: 400px;
    z-index: 1;
    height: 100px;
    width: 90%;
    margin-left: 5%;
    margin-right: 5%;
    align-items: center;
    justify-items: center;
}

.curve-2 {
    position: absolute;
    top: 5px;
    background-color: #05010D;
    border-radius: 180% 180% 0 0;
    background: linear-gradient(90deg, #060110, 05010D, #060110);
    padding-bottom: 400px;
    z-index: 2;
    height: 100px;
    width: 92%;
    margin-left: 4%;
    margin-right: 4%;
    align-items: center;
    justify-items: center;
}
.curve-3 {
    position: absolute;
    top: 50px;
    background-color: #05010D;
    border-radius: 100% 100% 0 0;
    padding-bottom: 180px;
    z-index: 3;
    height: 200px;
    width: 95%;
}



</style>

