<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Grillparty un keinen Grill? Dann miete ganz einfach einen!</h2>
      <img src="../assets/logo.png">

<p><a href="#/search">Jetzt einen Grill suchen</a></p>
<p><a href="#/create">Einen Grill verleihen</a></p>

  </div>


</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Uberbecue'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
</style>
