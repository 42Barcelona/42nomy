<script setup lang="ts">
import { ref } from 'vue'

const count = ref(0)
</script>

<template>
  <h1> Welcome to 42Nomy ! 🧑‍💻</h1>
  <h2><a href="https://api.intra.42.fr/oauth/authorize?client_id=92b46273dae2b5c203e2ec40b0a8c70decad9963f8aa5cc1ca85ffd3961202b2&redirect_uri=https%3A%2F%2Fgoogle.com&response_type=code
"> Login to continue</a> 🚀</h2>
</template>

<style scoped>
a {
  color: #42b983;
}

label {
  margin: 0 0.5em;
  font-weight: bold;
}

code {
  background-color: #eee;
  padding: 2px 4px;
  border-radius: 4px;
  color: #304455;
}
</style>
