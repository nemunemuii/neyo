<script setup>
import { ref } from "vue";

// TODO
// * Design, Color
</script>

<template>
  <div class="flex items-center gap-1.5">
    <div class="w-3 h-3 circle-red rounded-lg"></div>
    <div class="w-3 h-3 circle-yellow rounded-lg"></div>
    <div class="w-3 h-3 circle-green rounded-lg"></div>
  </div>
</template>

<style scoped>
.circle-red {
  background-color: #fe5f57;
}

.circle-yellow {
  background-color: #febc2e;
}

.circle-green {
  background-color: #28c841;
}
</style>
