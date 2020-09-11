<template>
  <div id="app">
    <h1>Componente App :)</h1>

    <Usuario>
       <strong slot="titulo">Bem vindo!!!</strong>
       <p slot="user">Meu nome é: {{nome}}</p> 
       <h1 slot="fim">RODAPE PAGINA!</h1>
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