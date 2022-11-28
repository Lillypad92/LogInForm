<script setup>
import LogIn from './components/LogIn.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <main>
    <LogIn />
    <TheWelcome />
    
  </main>
</template>

<style>
body {
  background-color: black;
}
@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }
}
</style>



