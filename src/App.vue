<script setup>
import { ref } from "vue";
const msg = ref("");
</script>

<template>
  <div class="login-container">
    <div class="login-header"></div>
    <div class="login-boy">
      <input v-model="msg" type="text" class="input-class" />
      <!-- <h1>{{ msg }}</h1> -->
    </div>
    <div class="lo"></div>
  </div>
</template>

<style scoped>
.login-container {
  background-color: white;
  max-width: 500px;
  width: 100%;
  padding: 1rem;
  border-radius: 1rem;
}
.input-class {
  max-width: 300px;
  width: 100%;
  height: 25px;
  background-color: grey;
  color: black;
  border-radius: 8px;
  padding: 12px 14px;
}
</style>
