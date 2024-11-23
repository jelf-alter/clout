<template>
  <div class="container">
    <img src="../assets/title.png" />
    <carousel1 />
    <div class="w-50 p-3" style="background-color: #eee; margin:0 auto;">
      <Subscribe />
    </div>
  </div>
</template>

<script setup lang="ts">
import carousel1 from "../components/Carousel.vue";
import Subscribe from "../components/Subscription.vue";

</script>

<style>
.container {
  max-width: 2000px;
  
  background-color:#ffd8bd;
}
body {
  background-color:#bde4ff;
}
</style>