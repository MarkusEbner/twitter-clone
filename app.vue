<template>
  <!-- dark is a class that depends on ref darkMode -->
  <div :class="{'dark': darkMode }">
   <h1 class="text-red-500 dark:text-dim-500">Twitter clone </h1>
  </div>
</template>
<script setup>
const darkMode = ref(true)
</script>
