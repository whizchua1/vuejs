<template>
  <div id="app">
    <menu/>
    <router-view/>
  </div>
</template>

<script>
import menu from './components/menu.vue';

export default {
  name: 'App',
  components: {
    menu,
  }
}
</script>

<style>
  * {
    box-sizing: border-box;
    font-family: Arial;
  }

  #page-wrap {
    margin: auto;
    max-width: 800px;
    min-height: 100vh;
  }

  button {
    background-color: black;
    border: none;
    border-radius: 8px;
    color: white;
    cursor: pointer;
    font-size: 16px;
    font-weight: bold;
    outline: 0;
    padding: 16px;
  }
</style>
