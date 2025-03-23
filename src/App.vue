<template>
    <Nav />
    <main>
    <RouterView/>
    </main>
</template>

<script setup>
import { RouterView } from 'vue-router';
import Nav from './components/Nav.vue'
</script>

<style scoped>

</style>