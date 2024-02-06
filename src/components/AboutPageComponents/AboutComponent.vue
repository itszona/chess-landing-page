<script>
export default {
    name: "AboutComponent",
}
</script>

<template>
<div id="about">
    <div>
        <h1>About</h1>
    </div>
    <div class="content">
        <p class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum quidem 
            itaque ad vero maiores adipisci similique, labore accusamus minus 
            necessitatibus suscipit impedit voluptatibus cupiditate quisquam illo 
            aspernatur, incidunt nobis placeat!</p>
    </div>
</div>
</template>

<style scoped>

#about {
    margin: 0;
    padding: 60px 0px 20px 0px;
    width: 100vw;
    align-items: center;
    text-align: center;
    justify-content: center;
}

.content {
    margin-left: 10%;
    margin-right: 10%;
    align-items: center;
    text-align: center;
    justify-content: center;
}

h1 {
    text-align: center;
    font-family: "Garnett";
    font-size: 50px;
    font-style: normal;
    font-weight: 800;
    line-height: normal;
    margin-top: 20px;
    padding-bottom: 0px;
    color: #FFF;
}

p {
    text-align: center;
    font-family: "DM Mono";
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    margin-top: 10px;
    color: #FFF;
}


</style>