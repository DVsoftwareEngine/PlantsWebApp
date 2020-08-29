<template>
  <div class="Home">
    <!-- <AICard/>
    { #each PlantsArr as plant }
      <PlantCard plantName="{plant.plantName}"/>
    { /each }
    <NewPlantCard/> -->
  </div>
</template>

<script>
  // @ is an alias to /src
  // import HelloWorld from "@/components/HelloWorld.vue";

  export default {
    name: "Home",
    components: {
      // HelloWorld
    }
  };
</script>

<style lang="scss">
  .Home {
    margin: 0 auto;
    height: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-top: 5%;
	}
</style>
