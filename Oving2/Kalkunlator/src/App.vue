<script>
import { RouterLink, RouterView } from "vue-router";

import Calculator from "./components/Calculator.vue";

export default {
  name: "app",
  components: {
    Calculator
  }
}
</script>

<template>
  <div id="app">
    <Calculator />
  </div>
  <RouterView />
</template>

<style scoped>

</style>
