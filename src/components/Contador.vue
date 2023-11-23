<template>
  <h1>Contador</h1>
  <h2>{{ count }}</h2>
  <button @click="count = count+1">Click me</button>
</template>

<script lang="ts" setup>
import { ref, type Ref } from 'vue';
let count:Ref<number>  =  ref(0);

</script>

<style>

</style>