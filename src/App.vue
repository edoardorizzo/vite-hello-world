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
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
