<template>
  <div>
      <p>Tecnologias que utilizo:</p>
      <ul>
         <li  v-for="(technology, index) in frontTech" v-bind:key="index">{{technology}}</li>
      </ul>
  </div>
</template>

<script>
export default {
    name:'info',
    data(){
        return{
            frontTech: ['Html','Css', 'JavaScript', 'Vue.js']
        }

    }

}
</script>

<style>

</style>