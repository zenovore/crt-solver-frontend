<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <Header/> -->
  <Form></Form>
</template>

<script>
// import Header from './components/Header.vue'
import Form from './components/Form.vue'

export default {
  name: 'App',
  components: {
    // Header
    Form
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
body{
  background-color:#eee;
}
</style>
