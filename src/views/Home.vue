<template>
  <div class="container">
    <h1>Vite + VUE2.7</h1>
    <h2>
      Vite ⚡ - Vue2 - TS - VueRouter - Vuex - Axios - Sass / Starter Template
    </h2>
    <h4>{{ count }}</h4>
    <button @click="add">Count++</button>
  </div>
</template>
<script lang="ts">
import Vue from "vue";
export default Vue.extend({
  data() {
    return {
      count: 0,
    };
  },
  methods: {
    add() {
      this.count++;
    },
  },
});
</script>
<style lang="scss" scoped>
.container {
  text-align: center;
}
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
