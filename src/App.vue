<script setup lang="ts">
import AppHeader from './components/AppHeader.vue';
import TodoList from './components/TodoList.vue';
</script>

<template>
  <AppHeader />
  <TodoList />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  font-size: 1.2rem;
  min-height: 100vh;
  background-color: #f0f0f0;
}
</style>
