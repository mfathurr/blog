<script>
import Header from "./components/layouts/Header.vue";
import MainContent from "./components/MainContent.vue";

export default {
  components: {
    Header,
    MainContent
  }
}
</script>

<template>
  <Header></Header>
  <MainContent></MainContent>
  <h1 class="text-3xl font-bold underline text-lime-400">
    Hello world!
  </h1>
</template>

<style scoped>

</style>
