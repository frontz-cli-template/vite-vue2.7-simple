<template>
  <div id="app">
    <main>
      <a href="#" @click="add">{{num}}</a>
      <RouterView />
    </main>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'
const num = ref<number>(1)

const add = () => {
  num.value++
}
</script>