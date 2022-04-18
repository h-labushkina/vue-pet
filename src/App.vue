<template>
  <h1>Hello</h1>
  <Counter />
  <hr/>
  <Counter />
</template>

<script>
import Counter from "./Counter.vue";

export default {
  modules: 'App',
  components: {
    Counter
  }
}
</script>

<style scoped>

</style>