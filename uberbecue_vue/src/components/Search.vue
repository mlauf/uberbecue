<template>
  <div class="search">
    <h1>{{ msg }}</h1>

    <iframe
      width="600"
      height="450"
      frameborder="0" style="border:0"
      src="https://www.google.com/maps/embed/v1/place?key=AIzaSyAlnE5uigVpDUkIlBcLVd9glDW67JYdktc
        &q=Space+Needle,Seattle+WA" allowfullscreen>
    </iframe>


  </div>
</template>

<script>
export default {
  name: 'search',
  data () {
    return {
      msg: 'Suche einen Grill in deiner Nähe'
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
