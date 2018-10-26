<template>
  <div id="app">
    <div class="nav bar">
      <div class="logo home">
        logo aqui
      </div>
      <div class="links">
        <router-link to="/">
          Intro
        </router-link>
        <router-link to="/about">
          Sobre
        </router-link>
        <router-link to="/jobs">
          Trabalhos
        </router-link>
      </div>
      <router-link to="/contact">
        Contato
      </router-link>
    </div>
    <router-view/>
    <div class="footer">Footer aqui!</div>
  </div>
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
</style>
