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
  color: inherit;
  text-decoration: none;
  list-style-type: none;
}

body
{
  background-color: black;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  // color: #2c3e50;
  color: white;
}

// ----- PRESET --------------------------------------------------------------- //
.contenitore65
{
  width: 65vw;
  margin: 0 auto;
}

.margin-y-30
{
  margin: 30px 0;
}

.padding-y-30
{
  padding: 30px 0;
}

.padding-y-40
{
  padding: 40px 0;
}

.text-left
{
  text-align: left;
}

// ----- FLEX --------------------------------------------------------------- //
.flex-mode
{
  display: flex;
}

.f-align-center
{
  align-items: center;
}

.f-justify-between
{
  justify-content: space-between
}

.f-justify-around
{
  justify-content: space-around
}
</style>
