<template>
  <div id="app">
    <div class="banner">
      <img src="@/assets/logo.png" width="25px" class="logo">
      <h3>Vue Mortgage Calculator</h3>
    </div>
    <!-- Your calculator component(s) should go here -->
    <p>
      The code for your calculator application should go here.
      Please come get one of us if you need help getting started!
    </p>
  </div>
</template>

<script>
export default {
  name: "app"
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  font-weight: 100;
  font-size: 14px;
}

body {
  margin: 0;
}

h3 {
  display: inline-block;
  text-align: center;
}

.banner {
  background-color: lightgray;
  text-align: center;
  margin-bottom: 25px;
}

.logo {
  display: inline-block;
  margin-bottom: -8px;
  margin-right: 5px;
}

p {
  width: 75%;
  margin: 0 auto;
  padding: 10px;
}
</style>
