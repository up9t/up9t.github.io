<script setup lang="ts">
import { ref } from 'vue'

const counter = ref(0)
</script>

<template>
  <h1 ref="reesc">You did it!</h1>
  <p>You clicked the button {{ counter }} times</p>
  <button @click="() => counter++">Presss me!</button>
</template>

<style scoped></style>
