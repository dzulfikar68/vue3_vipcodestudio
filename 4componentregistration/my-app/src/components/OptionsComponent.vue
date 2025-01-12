<template>
    <h1>{{ name }}</h1>
    <button @click="showName">Show Name</button>
</template>

<script>
export default {
    data() {
        return {
            name: 'Pipi Erma',
        }
    },
    methods: {
        showName() {
            console.log(this.name)
        }
    },
}
</script>

<style></style>
