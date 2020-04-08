<template>
  <div id="app">
    <HelloWorld v-model="msg"/>
    <div>Hello {{msg.salutation}} {{msg.name}}</div>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld
  },
  data() {
    return {
      msg: {
        salutation: "Mr",
        name: "Josh"
      }
    };
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
}
</style>
