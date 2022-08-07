<script setup lang="ts">
import BaseButton from '@/components/BaseButton.vue'
</script>

<template>
  <main>
    <h1>application</h1>
    <BaseButton>Component</BaseButton>
  </main>
</template>

<style lang="scss">
$red: #b86767;
main {
  background-color: $red;
  button {
    color: $green;
  }
}
</style>
