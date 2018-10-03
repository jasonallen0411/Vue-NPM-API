<template>
<body>
  <div id="app">
    <router-link to = "/">Home</router-link>
    <router-link to = "/CNFacts">Chuck Norris Facts</router-link>
    <router-view/>
    <img src="http://www.smosh.com/wp-content/uploads/legacy.images/smosh-pit/022011/chuck-norris-super-kick.gif">
  </div>
</body>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

body{
  background-color: #333635;
}
a{
  color: white;
}
</style>
