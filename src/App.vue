<script>
  import Accordion from './components/Accordion.vue'
  import Header from './components/Header.vue'
  export default {
    components: {
      Accordion,
      Header,
    }
  }
</script>

<template>
  <Header />
  <div class="container">
    <h1 class="h1">Hello World</h1>
    <Accordion />
    <Accordion />
    <Accordion />
    <Accordion />
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
