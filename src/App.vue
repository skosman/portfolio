<script setup>
import { RouterLink, RouterView } from "vue-router";
import NavBar from "./components/NavBar.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <NavBar></NavBar>
  <RouterView />
  <Footer></Footer>
</template>

<style scoped></style>
