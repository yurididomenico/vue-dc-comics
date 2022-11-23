<!-- 

Descrizione:
  -Create un nuovo progetto utilizzando Vue CLI.
  -Definite i componenti necessari per strutturare il layout.
  -Popolate le voci di menu dinamicamente usando i data del componente.
  -Quando è tutto bello solido, passiamo al Sass!

  Bonus:
  Creare un componente aggiuntivo per gestire la fascia azzurra con le icone.

 -->

<template>
  <div id="app">
    <HeaderComponent/>
    <MainComponent/>
    <FooterComponent/>
  </div>
</template>

<script>
import HeaderComponent from './components/Header/HeaderComponent.vue';
import MainComponent from './components/Main/MainComponent.vue';
import FooterComponent from './components/Footer/FooterComponent.vue';

export default {
  name: 'App',
  components: 
  {
    HeaderComponent,
    MainComponent,
    FooterComponent
  }
}
</script>

<style lang="scss">
*
{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

body
{
  background-color: black;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  // color: #2c3e50;
  color: white;
}
</style>
