<template>
  <div>
    <h1>Titre h1</h1>
    <p>Hello {{ msg }}</p>
    <p>Seulement  {{ fullTeext }}</p>
  </div>
</template>
<script>
export default {
  data() {
    return {
    msg:'test',
      hello: "hello",
      word:"word",
      fullText:"Hello Word"
    };
  },
  computed: {
    fullTeext() {
      return this.hello + ' ' + this.word;
    }
  }
};
</script>
<style>
</style>