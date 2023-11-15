<script setup>
import { ref } from 'vue';
import TheWelcome from '../components/TheWelcome.vue'
const counter = ref(0);


</script>

<template>
  <main>
    <!-- <TheWelcome /> -->
    <h1>{{  counter }}</h1>
    <button @click="counter++">+</button>
    <button @click="counter--">-</button>
  </main>
</template>
