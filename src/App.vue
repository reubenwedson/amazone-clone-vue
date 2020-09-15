<template>
  <div id="app">
    <Header />
    <router-view />
  </div>
</template>

<script>
  import Header from "./components/navigation/Header";
  export default {
    components: {Header}
  }
</script>

<style>
  * {
    margin: 0;
  }

  #app {
    background-color: rgb(234, 237, 237);
    margin: 0;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen',
    'Ubuntu', 'Cantarell', 'Fira Sans', 'Droid Sans', 'Helvetica Neue',
    sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }
</style>