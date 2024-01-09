<script setup>
import {ref} from 'vue'
const msg = ref('')
</script>

<template>
  <div>
    <input v-model="msg" type="text"/>
    <h1>{{ msg }}</h1>
  </div>
</template>

<style scoped>

</style>
