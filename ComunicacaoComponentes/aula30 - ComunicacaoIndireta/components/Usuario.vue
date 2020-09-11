<template>
    <div id="usuario">

        <h2>Olá PROP: {{nome}} </h2>
        <button @click="curso">NOME CURSO</button>

    </div>
</template>

<script>
export default {
    name: 'Usuario',
    props: {
       nome:{
           type: String,
           required: false
       }
    },
    methods:{
        curso(){
            this.nome = 'Aprendendo Portugues';
            this.$emit('nomeCurso', this.nome);
        }
    }
}
</script>

<style scoped>
    h2{
        color: red;
    }
</style>