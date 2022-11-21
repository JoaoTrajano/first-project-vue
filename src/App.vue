<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWord msg="Olá, mundo!"/>
  <TestFirstComponent />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HelloWord from './components/HelloWord.vue';
import TestFirstComponent from './components/MyFirstComponent.vue';

export default defineComponent({
  name: 'App',
  components: {
    HelloWord,
    TestFirstComponent
  }
});
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
