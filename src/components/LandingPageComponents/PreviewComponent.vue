<script>
export default {
  name: "PreviewComponent",
};
</script>

<template>
<div id="preview">  
    <div class="preview-content">
      <h1>Preview</h1>
      <p>Lorem ipsum dolor sit amet consectetur. Eros nibh egestas quam dolor nulla vitae ipsum ut. Arcu ullamcorper netus proin arcu amet. 
A turpis sit eu felis volutpat pharetra egestas vitae. Cursus volutpat in quis morbi. Euismod id at facilisi venenatis. 
Morbi lobortis ut sed egestas morbi turpis volutpat lobortis ligula. 
Tincidunt ultricies cursus faucibus augue sed faucibus nibh eget.
</p>   
      <p>Ornare leo elementum viverra justo diam. Turpis quam augue massa dolor. Libero nibh enim nisl vulputate tincidunt faucibus egestas. Blandit ut nulla amet tempus egestas sit. Cras vestibulum pulvinar et cras.</p>
    </div>
</div>
</template>

<style scoped>

#preview {
  margin-top: 0px;
  padding: 0px;
  background: #05010D;
}

.preview-content {
  display: flex;
  flex-direction: column;
  margin-left: 15%;
  margin-right: 15%;
}

h1 {
  text-align: center;
  font-family: "Garnett";
  font-size: 48px;
  font-style: normal;
  font-weight: 800;
  line-height: normal;
  color: white;
}

p {
  text-align: center;
  font-family: "DM Mono";
  font-size: 24px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  color: white;
  margin-top: 20px;
}

</style>