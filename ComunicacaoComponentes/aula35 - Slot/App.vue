<template>
  <div id="app">
    <h1>Componente App :)</h1>

    <Usuario>
       <strong>Bem vindo!!!</strong>
       <p>Meu nome é: {{nome}}</p> 
    </Usuario>

  </div>
</template>

<script>
import Usuario from './components/Usuario';

export default {
  name: 'App',
  components:{
    Usuario,
  },
  data(){
    return{
      nome: 'Sujeito Programador'
    }
  }
}
</script>

<style scoped>
  p{
    color: blue!important;
  }
</style>