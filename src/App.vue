<script>
export default {
  data() {
    return {
      count: 0,
      hello: 'Hello World'
    }
  }
}
</script>

<template>
  <h1> {{ hello }}</h1>
  <h2> Click counter </h2>
  <button @click="count++"> You have clicked {{ count }} times</button>
  <button @click="count = 0"> Reset</button>
</template>

<style scoped>

</style>
