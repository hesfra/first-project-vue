<template>
  <h1>testing</h1>
  <primeiroComponente />
  <info />
  <Form />
</template>

<script>
import primeiroComponente from './components/Primeirocomponente.vue'
import Form from './components/form.vue'
import info from './components/info.vue'


export default {
  name: 'App',
  components: {
    primeiroComponente,
    Form,
    info,

  }
}
</script>

<style>
h1 {
  font-size: 3.2rem;
}
</style>