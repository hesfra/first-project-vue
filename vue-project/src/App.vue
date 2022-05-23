<template>
  <h1>testing</h1>
  <primeiroComponente />
  <inputText />
  <inputText />
  <inputButton />
  <info />
</template>

<script>
import primeiroComponente from './components/Primeirocomponente.vue'
import inputText from './components/inputs/inputText.vue'
import inputButton from './components/inputs/inputButton.vue'
import info from './components/info.vue'
export default {
name:'App',
components:{
    primeiroComponente,
    inputButton,
    inputText,
    info,
    
}
}
</script>

<style>
h1{
  font-size: 3.2rem;
}
</style>