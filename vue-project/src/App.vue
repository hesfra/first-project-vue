<template>
  <h1>testing</h1>
  <primeiroComponente />
</template>

<script>
import primeiroComponente from './components/Primeirocomponente.vue'
export default {
name:'App',
components:{
  primeiroComponente
}
}
</script>

<style>
h1{
  font-size: 3.2rem;
}
</style>