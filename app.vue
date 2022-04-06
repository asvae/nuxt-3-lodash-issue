<template>
  <div>
    <button @click="count++">{{ count }}</button>
  </div>
</template>

<script setup>
import { ref } from 'vue'
import sortBy from 'lodash/sortBy'

console.log(sortBy)

const count = ref(0)
</script>
