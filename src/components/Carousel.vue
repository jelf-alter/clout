<template>
  <MDBCarousel v-model="carousel1" :items="items1" fade />
</template>

<script setup lang="ts">
import { ref } from "vue";
import { MDBCarousel } from "mdb-vue-ui-kit";
import allowance from '../assets/allowance.png'
import whatbring from '../assets/whatbring.png'
import whatis from '../assets/whatis.png'

const items1 = [
  {
    src: whatbring,
  },
  {
    src: whatis,
  },
  {
    src: allowance,
  },
];

const carousel1 = ref(0);
</script>

<style>
img {
  width: 100%;
  height: 1100px;
}
</style>