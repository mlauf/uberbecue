<template>
  <div class="hello">
    <ul>
      <li><a href="default.asp">Home</a></li>
      <li><a href="news.asp">Neuigkeiten</a></li>
      <li><a href="contact.asp">Kontakt</a></li>
      <li><a href="about.asp">Mein Profil</a></li>
    </ul>
    <img id="logo" src="../assets/loggo.png" >
    <br>
    <h1 align="center">{{ msg }}</h1>

<p><a href="#/test">Test</a></p>
    
    <h2 align="center">Grillparty und keinen Grill? Dann miete ganz einfach einen!</h2>

    <button type="button" class="btn btn-primary"><a href="#/search">Jetzt einen Grill suchen</a></button>
    <button type="button" class="btn btn-primary"><a href="#/create">Einen Grill verleihen</a></button>

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

button {
  background-color: #333;
  border:0;
  margin-top: 500px;
  padding: 12px 60px;
  font-size: 18px;
  width: 300px;
}
button:hover {
  background-color: #92252d;

}
#barbecue {
  width: 100%;
}
#logo {
  float: right;
  height:250px;
  margin-right: 50px;
  margin-top: -130px;
}
a:hover {
  color: white;
  text-decoration: none;
}
h1, h2 {
  font-weight: normal;
  color: white;

}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;

}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change the link color to #111 (black) on hover */
li a:hover {
  background-color: #111;
}

a {
  color: white;

}
div.hello{
  background-image: url(../assets/bannerrr.jpg);
  height: 800px;
  align: center;
}
</style>
