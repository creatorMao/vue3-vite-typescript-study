<script setup lang="ts">
import { Ref, ref } from 'vue'
const count = ref(0)
const add = function () {
  count.value++
}
</script>

<template>
  <h1>{{ count }}</h1>
  <button @click="add">加1</button>
</template>

<style scoped></style>
