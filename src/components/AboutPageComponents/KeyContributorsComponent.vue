<script>
export default {
    name: "ContributorsComponent"
}
</script>

<template>
<div id="key-contributors">
    <div>
        <h1>Key Contributors</h1>
    </div>
    <div class="grid-container">
        
        <div class="grid-item1">
            <div class="content">
                <img />
                <div class="text">
                    <p class="large-text">John Doe</p>
                    <p class="small-text">Project Manager</p>
                </div>
            </div>
        </div>
        
        <div class="grid-item2">
            <div class="content">
                <img />
                <div class="text">
                    <p class="large-text">Emmanuel Katchy</p>
                    <p class="small-text">Software Developer</p>
                </div>    
            </div>
        </div>

        <div class="grid-item3">
            <div class="content">
                <img />
                <div class="text">
                    <p class="large-text">David Katchy</p>
                    <p class="small-text">Software Developer</p>
                </div>    
            </div>
        </div>

        <div class="grid-item4">
            <div class="content">
                <img />
                <div class="text">
                    <p class="large-text">John Doe</p>
                    <p class="small-text">Designer</p>
                </div>    
            </div>
        </div>        
    
    </div>

</div>

</template>

<style scoped>

#key-contributors {
    margin: 0;
    padding: 20px 0px 20px 0px;
    width: 100vw;
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

.text {
    margin-top: 10px;
}

.large-text {
  text-align: center;
  font-family: "DM Mono";
  font-size: 20px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  color: #FFF;
  padding-bottom: 0px;
  margin-bottom: 0;
  letter-spacing: 4px;
}

.small-text {
  text-align: center;
  font-family: "DM Mono";
  font-size: 18px;
  font-style: italic;
  font-weight: 400;
  line-height: normal;
  color: #FFF;
  margin-top: 0px;
  padding-top: 0px;
}

.grid-container {
    display: grid;
    margin: 0 auto;
    column-gap: 100px;
    width: 80vw;
}

.grid-item1 {
    grid-column-start: 1;
    grid-column-end: 1;
    grid-row-start: 1;
    grid-row-end: 1;
    margin: 0;
    border-radius: 12px;
    border: 0.5 solid #FFF;
}

.grid-item2 {
    grid-column-start: 2;
    grid-column-end: 2;
    grid-row-start: 1;
    grid-row-end: 1;
    margin: 0;
    border-radius: 12px;
    border: 0.5 solid #FFF;
}

.grid-item3 {
    grid-column-start: 3;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 1;
    margin: 0;
    border-radius: 12px;
    border: 0.5 solid #FFF;
}

.grid-item4 {
    grid-column-start: 4;
    grid-column-end: 4;
    grid-row-start: 1;
    grid-row-end: 1;
    margin: 0;
    border-radius: 12px;
    border: 0.5 solid #FFF;
}

.content {
    display: flex;
    flex-direction: column;
}

</style>