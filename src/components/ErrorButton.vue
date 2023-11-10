<template>
  <button type="button" @click="raiseError">Don't click this button!</button>
</template>

<script setup>
  const raiseError = function () {
    throw new Error("You clicked the forbidden button");
  };
</script>

<style lang="scss" scoped></style>
