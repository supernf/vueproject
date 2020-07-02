<template>
  <div id="app">
<!--    <img src="./assets/logo.png">-->
<!--    <router-view/>-->
    <Login></Login>
    <VueDrag></VueDrag>
    <Card></Card>
  </div>
</template>

<script>
  import Login from './components/Login';
  import VueDrag from "./components/VueDrag";
  import Card from "./components/Card";

  export default {
    name: 'App',
    components: {
      'Login': Login,
      'VueDrag':VueDrag,
      'Card':Card
    },
    data() {
      return {}
    }
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
