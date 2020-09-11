<template>
  <div id="usuario">
    <h2>Esté é o componente usuario</h2>

    <slot> <!-- O slot esta recebendo o conteudo dentro de usuario no app-->
    </slot>

  </div>
</template>

<script>
export default {
  name: 'Usuario',
  props: ['nome']
}
</script>

<style scoped>
    p{
       color: brown; 
    }
</style>