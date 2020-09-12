<script>
export default {};
</script>

<template>
  <div class="PlantCard">
    <div class="PlantCard-name">
      <h3>plantName</h3>
      <p>Yep, plantName</p>
    </div>
    <div class="PlantCard-logo">
      <img src="/img/CactusLogo.png" alt="{plantName}">
    </div>
  </div>
</template>

<style>
.PlantCard {
  background-color: white;
  width: 80%;
  border-radius: 30px;
  padding: 2% 4%;
  margin-bottom: 2.5%;
  display: flex;
}
.PlantCard-name {
  flex-grow: 10;
}
.PlantCard-logo {
  width: 100px;
}
.PlantCard-logo img {
  height: 100px;
}
</style>
