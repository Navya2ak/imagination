<template>
  <div id="app">
    <DropdownComponent />
    <InputComponent />
    <ImageHolderComponent />
  </div>
</template>

<script>
import DropdownComponent from "./components/DropdownComponent.vue";
import InputComponent from "./components/InputComponent.vue";
import ImageHolderComponent from "./components/ImageHolderComponent.vue";

export default {
  name: 'App',
  components: {
    DropdownComponent,
    InputComponent,
    ImageHolderComponent
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
  position: relative;
  min-height: 100vh;
}
</style>
