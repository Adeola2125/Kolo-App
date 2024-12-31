<script setup lang="ts">
import Snackbar from './components/Snackbar.vue';
</script>

<template>
  <VLocaleProvider>
    <RouterView />
    <Snackbar></Snackbar>
  </VLocaleProvider>
</template>

<style>
a:hover {
  text-decoration: none !important;
}
</style>
