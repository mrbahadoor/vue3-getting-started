<script setup>
import { ref } from 'vue'
const msg = ref('Hello world!')
</script>

<template>
  <h1>{{ msg }}</h1>
  <input v-model="msg"/>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
