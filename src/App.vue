<template>
  <div id="app">
    <hello></hello>
  </div>
</template>

<script>
import Hello from './components/Hello';

export default {
  name: 'app',
  components: {
    Hello,
  },
};
</script>

<style>
html {
  height: 100%;
}
body {
  height: 100%;
  margin: 0;
  background:
    radial-gradient(circle at 50% 0,
         rgba(255,0,0,.5), rgba(0,255,0,0) 70.71%),
    radial-gradient(circle at 6.7% 75%,
         rgba(0,0,255,.5), rgba(0,0,255,0) 70.71%),
    radial-gradient(circle at 93.3% 75%,
         rgba(0,255,0,.5), rgba(255,0,0,0) 70.71%);
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100%;
}
</style>
