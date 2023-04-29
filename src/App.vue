<script setup>
import { createApp } from 'vue'
import about from './components/about.vue'
import chat from './components/chat.vue'

createApp(about).mount('#about')
createApp(chat).mount('#chat')
</script>

<template>
  <div class="wrapper">
    <div>
      <about />
    </div>
    <div>
      <chat />
    </div>
    <div class="footer">Copyright 2023. All Right Reserverd</div>
  </div>
</template>

<style>
.wrapper {
  max-width: 1000px;
  min-height: 500px;
  height: auto;
  margin-top: 10px;
  padding: 20px;
  background-color: #05020f;
  border-radius: 20px;
  text-align: center;
}
.footer {
    color: white;
    text-align: center;
}
</style>