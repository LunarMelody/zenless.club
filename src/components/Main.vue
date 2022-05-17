<!-- eslint-disable vue/multi-word-component-names -->

<script setup lang="ts">
interface Props {
  verticalCenter?: boolean;
}

defineProps<Props>();
</script>

<template>
  <main class="main p-4 lg:p-8 grid" :class="verticalCenter ? 'place-content-center' : ''">
    <div id="content">
      <slot></slot>
    </div>
  </main>
</template>
