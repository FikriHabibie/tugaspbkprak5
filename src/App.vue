<template>
  <div id="app">
    <div class="app-container">
      <TodoList />
    </div>
  </div>
</template>

<script setup>
import TodoList from './components/TodoList.vue'
</script>

<style>
body {
  font-family: 'Segoe UI', Tahoma, sans-serif;
  margin: 0;
  padding: 0;
  background: linear-gradient(to bottom, #007bff, #66b2ff); /* Biru gradasi */
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: start;
}

.app-container {
  background-color: #ffffff;
  width: 100%;
  max-width: 700px;
  margin: 3rem auto;
  padding: 2rem;
  border-radius: 16px;
  box-shadow: 0 12px 32px rgba(0, 123, 255, 0.25);
  border-top: 8px solid #007bff;
  transition: transform 0.2s ease;
}

.app-container:hover {
  transform: scale(1.01);
}
</style>