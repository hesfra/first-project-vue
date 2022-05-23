<template>
  <div>
    <h1>Another test</h1>
    <p>Meu nome é {{ name }}</p>
    <p v-show="showProfission">eu trabalho como: {{ profission }}</p>
    <button @click="show">{{ textButton }}</button>
  </div>
</template>

<script>
export default {
  name: "primeiroComponente",
  data() {
    return {
      name: "Christian",
      profission: "Estudante de Vue",
      showProfission: true,
      textButton: "Show profission",
    };
  },
  methods: {
    show() {
      this.showProfission = !this.showProfission;
      if (!this.showProfission) {
        this.textButton = "Show profission";
      } else {
        this.textButton = "Hide profission";
      }
    },
  },
};
</script>

<style>
</style>