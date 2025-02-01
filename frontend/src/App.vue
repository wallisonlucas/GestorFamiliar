
<template>
  <div>
    <Apresentacao />
  </div>
  
</template>

<script>
  import Apresentacao from './components/Apresentacao.vue';
  import Login from './components/Login.vue';

  export default {
    name: 'App',
    components: {
      Apresentacao,
      Login
    }
  }      
</script>
