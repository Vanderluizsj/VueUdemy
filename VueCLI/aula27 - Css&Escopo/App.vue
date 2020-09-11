<template>
  <div id="app">

    <h1>Bem vindo ao meu primeiro projeto!</h1>
    <Usuario/>

    <h2> Olá sou um subtitulo :) </h2>

    <h1 class="teste">Eu sou um h1</h1>

  </div>
</template>

<script>
import Usuario from './components/Usuario';

  export default{
    name: 'App',
    components:{
      Usuario
    },
    data(){
      return{
        nome:'Sujeito Programador'
      }
    },
  }
</script>

<style scoped>
  h1{
    color: brown;
  }
</style>