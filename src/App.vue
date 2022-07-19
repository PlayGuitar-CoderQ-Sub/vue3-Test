<script setup lang="ts">
import { Test } from './components';
</script>

<template>
  <div class="App">
    <div>
      <a href="https://vitejs.dev" target="_blank">
        <img src="/vite.svg" class="logo" alt="Vite logo" />
      </a>
      <a href="https://vuejs.org/" target="_blank">
        <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
      </a>
      <a href="#" target="_blank">
        <img src="/ts.svg" class="logo ts" alt="Ts logo" />
      </a>
    </div>
    <h1>
      <span class="vite">Vite + </span>
      <span class="vue">Solid + </span>
      <span class="ts">Ts</span>
    </h1>
    <div class="card">
      <div class="title">练习黑板</div>
      <div class="card-wrapper">
        <Test />
      </div>
    </div>
  </div>
</template>

<style scoped>
@import "./App.css";
</style>
