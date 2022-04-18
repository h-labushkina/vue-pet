<template>
  <button v-on:click="handleClick(btnValue-1)">-</button>
  <input v-model="btnValue"/>
  <button v-on:click="handleClick(btnValue+1)">+</button>
</template>

<script>
export default {
  name: "Counter",
  methods: {
    handleClick(value) {
      this.btnValue = value
    }
  },
  data() {
    return {
      btnValue: 1
    }
  }
}
</script>

<style scoped>

</style>