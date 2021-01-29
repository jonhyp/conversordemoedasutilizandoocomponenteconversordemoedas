<template>
  <div id="app">
    <h1>Conversor de Moedass</h1>
    <div class="linha">
      <Conversor moedaA="USD" moedaB="BRL"/>
      <Conversor moedaA="BRL" moedaB="USD"/>
    </div>
  </div>
</template>

<script>
import Conversor from "componenteconversor/Conversor.vue"

export default {
  name: 'app',
  components: {
    Conversor
  }
}
</script>

<style>
#app {
  max-width: 900px;
  margin: auto;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.linha{
  display: flex;
  justify-content: space-around;
  margin-top: 40px;
}
</style>
