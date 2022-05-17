<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">
import { RouterLink } from "vue-router";
</script>

<template>
  <nav
    class="navbar grid grid-cols-[1fr_auto] py-4 px-4 lg:px-8 text-sm leading-6 font-semibold border-b text-gray-700 dark:text-slate-200 border-gray-200 dark:border-gray-200/10"
  >
    <div class="flex space-x-8 place-self-center md:place-self-auto">
      <div class="pr-8 border-r border-gray-200 dark:border-gray-200/10">
        <RouterLink to="/">Home</RouterLink>
      </div>
      <div>
        <RouterLink to="/about">About</RouterLink>
      </div>
    </div>

    <div class="hidden md:block font-extrabold">
      <RouterLink to="/">ZENLESS.CLUB</RouterLink>
    </div>
  </nav>
</template>
