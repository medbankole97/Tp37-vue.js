<template>
  <HelloWorld :name="name" :age="age"/>

  <input type="text" v-model="name">
  <input type="number" v-model="age">
</template>

<script setup>
import HelloWorld from '@/components/HelloWorld.vue';
import { ref } from 'vue';

const name = ref('NordCoders');
const age = ref(30);
</script>

<style scoped>
/* Votre style ici */
</style>
