<template>
  <div id="app">

    <h1>Bem vindo ao meu primeiro projeto!</h1>
    <button @click="entrar">Entrar</button>

    <Usuario :nome="nome" />

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
        nome:'Matheus Teste'
      }
    },
    methods:{
      entrar(){
        this.nome = 'Curso Vue JS';
      }
    }
  }
</script>

<style scped>

</style>