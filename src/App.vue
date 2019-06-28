<template>
  <div>
    <NavBar/>
    <h2>App</h2>
  </div>
</template>

<script>
import NavBar from "./components/Navbar";

import "../node_modules/materialize-css/dist/css/materialize.min.css";
import "../node_modules/materialize-css/dist/js/materialize.min.js";

export default {
  name: "app",
  components: {
    NavBar
  }
};
</script>

<style scoped>
</style>
