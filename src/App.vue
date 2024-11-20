<script setup lang="ts">
import Card from "./components/Card.vue"
</script>

<template>

  <header>
    <h1>Anketa.hr</h1>
  </header>

  <div class="divider">
      &nbsp;
  </div>

  <main>
    <div class="background"></div>
    <div class="background-2"></div>
    <Card></Card>
  </main>

</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
