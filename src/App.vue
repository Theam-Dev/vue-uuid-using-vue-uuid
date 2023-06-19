<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <div class="uuid-panel">
    <h3 class="uuid">{{ v1 }}</h3>
     <h3 class="uuid">{{ v2 }}</h3>
  </div>
</template>

<script>
import { uuid } from 'vue-uuid';
export default {
  name: 'App',
  data () {
      return {
        v1: uuid.v1()
      };
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
