<template>
<div>
  <PrimeiroComponente />
  <P>O dado de app é: {{ testando }}</P>
  <LifeCycle />
  <Pessoa />
</div>
</template>

<script>
import PrimeiroComponente from './components/PrimeiroComponente.vue'
import LifeCycle from './components/LifeCycle.vue'
import Pessoa from './components/Pessoa.vue'


export default {
  name: 'App',
  components:{
    PrimeiroComponente,
    LifeCycle,
    Pessoa
  },
        data() {
            return{
                testando: "teste"
            }
        }
}
</script>