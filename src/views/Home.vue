<template>
  <div class="page-view-main">
    <p class="text-white">Explore the Park... on y(our) own terms!</p>
    <h1 class="text-8xl text-orange-500 header-title">Jurassic Park trail</h1>
    <p class="text-yellow-100 text-center w-1/2">
      Located in a secluded island off the cost of Costa Rica,surrounded by
      sandy shores filled with curious small green critters to the luscious
      forests guarded with windy roaring mountains and gaint roaming reptiles.
      Our organization is dedicated to providing those adventours folks such as
      yourself the true jurassic park...minus the missing limb or two!
    </p>
    <button class="mt-32 bg-orange-500 px-12 py-4 action-button">
      Your Adventure awaits
    </button>
  </div>

  <TourSelection />
  <div class="page-view">Section 3</div>
</template>
<script setup>
import { onMounted } from "vue"
import TourSelection from "../components/tour/TourSelectionView.vue"
onMounted(() => {
  console.log("home is mounted")
})
</script>
<style>
.action-button {
  outline: 0.1rem solid rgb(255, 166, 0);
  outline-offset: 1rem;
  -moz-outline-radius: 0rem;
}
.header-title {
  font-family: Jurassic Park;
  font-weight: 400;
}
.page-view-main {
  padding: 0vh 20vh;
  font-family: "Roboto", sans-serif;
  font-weight: 500;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  height: 95vh;
  background-color: rgb(23 24 23);
}
.page-view {
  padding: 0vh 20vh;

  height: 100vh;
  background-color: rgb(255 239 228);
}
</style>
