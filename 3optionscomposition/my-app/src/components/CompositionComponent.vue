<template>
  <button @click="showName">Show Composition</button>
  <h2>{{ name }}</h2>
</template>

<script setup>
const name = 'Composition Component'

const showName = () => {
  console.log(name)
}
</script>

<style scoped></style>
