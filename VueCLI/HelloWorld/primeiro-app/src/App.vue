<template>
  <div id="app">
    <h1>Bem vindo!</h1>
    <button @click="entrar">Entrar</button>
    <Usuario :nome="nome"/>



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
    methods:{
      entrar(){
        this.nome='Curso VueJS';
      }
    }
  }
</script>

<style scoped>
  
</style>