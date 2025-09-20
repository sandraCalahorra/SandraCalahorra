<template>
  <div id="app">
    <h1>¡Mi aplicación Vue 3 en Laravel!</h1>
    <example-component></example-component>
  </div>
</template>

<script>
import ExampleComponent from './components/ExampleComponent.vue';

export default {
  name: 'App',
  components: {
    ExampleComponent
  }
};
</script>

<style>
#app {
  font-family: Arial, sans-serif;
  background-color: #fafafa;
  padding: 20px;
}
h1 {
  color: #333;
}
</style>
