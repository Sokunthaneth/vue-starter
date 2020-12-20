<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ToDo />
  </div>
</template>

<script>
import ToDo from './todo/ToDo';

export default {
  name: 'HelloWorld',
  components: {
    ToDo,
  },
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
</style>
