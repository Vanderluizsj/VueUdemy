<template>
  <div id="app">
    <h1>Fazer Cadastro</h1>

    <div>
      <form>
        <label>Nome </label>
        <input type="text" v-model="user.nome" /><br/>

        <label>Email </label>
        <input type="email" v-model="user.email" /><br/>

        <label>Qtd Funcionarios </label>
        <input type="number" v-model="user.qtdFunc" /><br/>        


      </form>
    </div>

    <hr/>

    <div class="item">
      <h2>Usuario Cadastrado</h2>

      <label>Nome: {{user.nome}}</label><br/>
      <label>Email: {{user.email}}</label><br/>
      <label>Qtd Funcionarios: {{user.qtdFunc}}</label><br/>
    </div>

  </div>
</template>

<script>
export default {
  name: 'App',
  data(){
    return{
      // nome: '',
      // email: '',
      // qtdFunc: 0
      user:{
        nome: '',
        email: '',
        qtdFunc: 0
      }
    }
  }
}
</script>

<style scoped>

</style>