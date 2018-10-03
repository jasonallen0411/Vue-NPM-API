<template>
<body>
  <div id="CNFacts">
  <h1 id="appTitle">Chuck Norris Facts</h1>

  <div class="input-group mb-3">
  <input id="searchInput" type="text" class="form-control" aria-label="Recipient's username" aria-describedby="basic-addon2">
  <div class="input-group-append">
  <button id="factBtn" type="button">Get Facts!</button>
  </div>
</div>

<ul>
  <li id="factList" ><h2></h2></li>
</ul>

</div>
</body>

</template>

<script>
export default {
  name: 'CNFacts',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
  color: white;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}


a {
  color: #42b983;
}

#factBtn{
  background-color: #20A600;
  color: white;
}
</style>
