<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="My Project created using Vue.Js"/>
    <TestData message="Developed by Feisal Mombo"/>
    <Message comment="Please, In order to complete this projects must follow this guide because to become geek in Vue.js"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TestData from './components/TestData.vue'
import Message from './components/Message.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    TestData,
    Message
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
</style>
