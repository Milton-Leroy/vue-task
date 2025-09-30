<script setup>
import Child from './components/Child.vue'

let data = [
  { id: 1, name: 'John' },
  { id: 2, name: 'Jane' },
  { id: 3, name: 'Doe' }
]
</script>

<template>
  <Child>
    <h2>Component</h2>
    <p>This is the first component</p>
    <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat, possimus.</span>
  </Child>

  <br>
  <br>


  <p v-for="number in 10">
    {{ number }}. This is a number
  </p>

  <hr>

  <br>
  <br>

  <Child>
    <p>This is the second component</p>
  </Child>
</template>
