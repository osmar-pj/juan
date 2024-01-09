<script setup>
import { ref } from "vue";
const msg = ref("");
</script>

<template>
  <div>
    <input v-model="msg" type="text" class="input-class" />
    <h1>{{ msg }}</h1>
  </div>
</template>

<style scoped>
.input-class {
  max-width: 300px;
  width: 100%;
  height: 45px;
  background-color: grey;
  color: black;
  border-radius: 5px;
  padding: 12px 14px;

}
</style>
