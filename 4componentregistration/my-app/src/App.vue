<script setup>
import Button from './components/Button.vue'
import CompositionComponent from './components/CompositionComponent.vue'
import OptionsComponent from './components/OptionsComponent.vue'
// defineOptions({
//   name: 'MainButton',
// })
const name = 'Yaqub Hammam'
</script>

<template>
  <h1>Hello Vue 3!</h1>
  <p>Dzulfikar Fauzi</p>
  <p>{{ name }}</p>
  <OptionsComponent />
  <CompositionComponent />
  <Button></Button>
  <Button></Button>
  <Button></Button>
</template>

<style scoped></style>
