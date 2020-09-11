<template>
  <div id="usuario">
    <h2>Esté é o componente usuario</h2>

    <slot name="titulo">
    </slot>

    <slot name="user"></slot>

    <slot name="fim"></slot>



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