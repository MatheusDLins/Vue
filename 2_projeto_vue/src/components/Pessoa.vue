<template>
    <div>
        <h2>Está é a descrição da pessoa: {{ nome }} </h2>
        <Info />
        <Form />
    </div>
</template>

<script>
import Info from './Info.vue'
import Form from './Form'
export default {
    name: 'Pessoa',
    components: {
        Info,
        Form
    },
    data(){
        return {
            nome: 'Matheus'
        }
    }
}
</script>