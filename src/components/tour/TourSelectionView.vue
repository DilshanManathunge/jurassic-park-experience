<template>
  <div class="page-view grid grid-cols-5">
    <div class="flex flex-col items-center pt-20 col-span-2">
      <h1 class="text-8xl text-lime-950 font-black text-center">
        <span style="font-size: 8rem">04</span><br />
        <span style="font-family: : 'Roboto', sans-serif;"
          >UNIQUE<br />
          TOURS</span
        >
      </h1>
      <p class="mt-5 font-medium">
        After careful consideration our team of experts have curated 4 unique
        top of the line adventures to entice our clientel.We have some of the
        top of the line security along with the tour to make sure you dont get
        eaten
      </p>
      <div>
        <TourCard />
        <TourCard /> <TourCard /> <TourCard />
      </div>
    </div>
    <div
      class="flex flex-col justify-center items-center col-span-3 px-10 py-10"
    >
      <img src="../../assets/isla_nublar.jpg" style="height: 75vh" />
    </div>
  </div>
</template>
<script setup>
import TourCard from "./tourCard/TourCard.vue"
</script>
