<template>
  <div class="jobs">
    <h1>{{ msg }}</h1>
    <h2>Alguns dos meus trabalhos.</h2>
  </div>
</template>

<script>
export default {
  name: 'Jobs',
  data () {
    return {
      msg: 'Desenhos, apps e afins!'
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
