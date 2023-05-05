<template>
  <div id="app">
    <router-link to="/">Home</router-link>,
    <router-link to="/vmodel">/Vmodel</router-link>,
    <router-link to="/von">/V-On</router-link>,
    <router-link to="/vbind">/V-Bind</router-link>,
    <router-link to="/prop">/Prop</router-link>, <br /><br />
    <router-view />
  </div>
</template>

<script>
export default {
  name: "app",
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
