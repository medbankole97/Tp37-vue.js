
<template>
  <h1> Hello World!</h1>
  <p>{{props.name}} {{props.age}}</p>
  
</template>

<script setup>
const props = defineProps(['name', 'age']);

</script>
