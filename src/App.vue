<script setup>
import Child from './components/Child.vue'
</script>

<template>
  <Child>
    <h2>Component</h2>
    <p>This is the first component</p>
    <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat, possimus.</span>
  </Child>

  <br>
  <br>

  <hr>

  <br>
  <br>

  <Child>
    <p>This is the second component</p>
  </Child>
</template>
