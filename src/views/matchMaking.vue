<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <button class="myButton"> hello </button>
  </div>
</template>

<script>
export default {
  name: 'matchMaking',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
.myButton {
  box-shadow: 1px 5px 4px 0px #8a2a21;
  background:linear-gradient(to bottom, #c62d1f 5%, #f24437 100%);
  background-color:#c62d1f;
  border-radius:25px;
  border:1px solid #d02718;
  display:inline-block;
  cursor:pointer;
  color:#ffffff;
  font-family:Arial;
  font-size:19px;
  padding:13px 31px;
  text-decoration:none;
  text-shadow:3px 6px 2px #810e05;
}
.myButton:hover {
  background:linear-gradient(to bottom, #f24437 5%, #c62d1f 100%);
  background-color:#f24437;
}
.myButton:active {
  position:relative;
  top:1px;
}
</style>

