<template>
  <div class="Home">
    <AICard />
    <PlantCard />
    <NewPlantCard />
    <!-- 
    { #each PlantsArr as plant }
      <PlantCard plantName="{plant.plantName}"/>
    { /each }
    <NewPlantCard/>-->
  </div>
</template>

<script>
// @ is an alias to /src
import AICard from "@/components/Home/AICard.vue";
import PlantCard from "@/components/Home/PlantCard.vue";
import NewPlantCard from "@/components/Home/NewPlantCard.vue";

export default {
  name: "Home",
  components: {
    AICard,
    PlantCard,
    NewPlantCard
  }
};
</script>

<style lang="scss">
.Home {
  margin: 0 5%;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-top: 5%;
}
</style>
