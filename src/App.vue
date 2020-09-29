<template>
  <div id="app">
    <Counter></Counter>
    <message>Hello There</message>
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to my Vue.js App"/>
    <h1>Here's more! TBD</h1>
    <Example />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import message from './components/message.vue';
import Counter from './components/Counter.vue';
import Example from './components/Example.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    message,
    Counter,
    Example
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
