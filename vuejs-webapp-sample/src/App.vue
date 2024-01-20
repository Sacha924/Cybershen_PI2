<script setup lang="ts">
const message = 'Hello World';
</script>

<template>
  <router-view></router-view>
  <h1>{{ message }}</h1>
  <h2>{{ message }}</h2>
</template>
