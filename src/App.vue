<script>
  import Accordion from './components/Accordion.vue'
  export default {
    components: {
      Accordion
    }
  }
</script>

<template>
  <div class="container">
    <h1 class="h1">Hello World</h1>
    <div>This is the first commit after adapting the ulu</div>
    <Accordion />
  </div>
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
