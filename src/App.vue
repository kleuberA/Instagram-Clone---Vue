<template>
  <div id="app">
    <pagina-home></pagina-home>
  </div>
</template>

<script>
import Home from './views/Home.vue';
export default {
  name: 'app',
  components:{
    'pagina-home': Home
  },
  data () {
    return {
    }
  }
}
</script>

<style></style>
