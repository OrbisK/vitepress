<template>
  <div class="custom-block github-alert" :class="type"><p class="custom-block-title"><slot /></p></div>
</template>

<script setup lang="ts">
defineProps(["type"])
</script>