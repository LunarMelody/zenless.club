<script setup lang="ts">
import { RouterView } from "vue-router";

import Footer from "@/components/Footer.vue";
import Navbar from "@/components/Navbar.vue";
</script>

<template>
  <div class="app">
    <Navbar />
    <RouterView />
    <Footer />
  </div>
</template>
