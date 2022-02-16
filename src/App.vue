<script setup>
import CTabs from "~/components/tabs/tabs.vue";
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
// import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
    <c-tabs>
      <c-tab-item value="123" c="123">a</c-tab-item>
      <c-tab-item label="item">b</c-tab-item>
      <c-tab-item label="item">c</c-tab-item>
      <c-tab-item label="item">d</c-tab-item>
      <c-tab-item label="item">e</c-tab-item>
      <c-tab-item label="item">f</c-tab-item>
      <c-tab-item label="item">g</c-tab-item>
    </c-tabs>
  <!-- <CTabs></CTabs> -->
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <!-- <HelloWorld msg="Hello Vue 3 + Vite" /> -->
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
