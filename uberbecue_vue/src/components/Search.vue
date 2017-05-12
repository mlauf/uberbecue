<template>
  <div class="Search">
    <h1>{{ msg }}</h1>

    <map
      :center="{lat:10, lng:10}"
      :map-type-id="terrain"
      :zoom="7"
    ></map>



  </div>
</template>

<script>
import {load, Map, Marker} from 'vue-google-maps'
load('YOUR_API_TOKEN', 'OPTIONAL VERSION NUMBER')
export default {
  name: 'search',
  data () {
    return {
      msg: 'Suche einen Grill in deiner Nähe',
      center: {lat: 10.0, lng: 10.0},
      markers: [{
        position: {lat: 10.0, lng: 10.0}
      }, {
        position: {lat: 11.0, lng: 11.0}
      }]
    }
  },
  methods: {
    myMap: function () {
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
