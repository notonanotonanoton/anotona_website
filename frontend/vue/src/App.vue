<script setup lang="ts">
/*import HelloWorld from './components/HelloWorld.vue'*/
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img alt="anotona logo" class="logo" src="./assets/logo.svg" />
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
header {
  display: block;
  width: 20%;
}

.logo {
  max-width: 100%;
}
</style>
