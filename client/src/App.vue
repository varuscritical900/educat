<script setup lang="ts">
import { RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue';
import Product from './components/Products.vue';
import Features from './components/Features.vue';
import Carousel from './components/Carousel.vue';
import Partners from './components/Partners.vue';
// import Owner from './components/Owner.vue';

</script>

<template>
  <div id="app">
    <NavBar />
    <RouterView />
    <Product/>
    <Carousel/>
    <Features/>
    <Partners/>
    <!-- <Owner/> -->
  </div>
</template>
