<template>
  <div id="app">
    <page-header></page-header>
    <page-body></page-body>
    <page-footer></page-footer>
  </div>
</template>

<script>
import pageHeader from "./components/PageHeader.vue"
import pageFooter from "./components/PageFooter.vue"
import pageBody from "./components/PageBody.vue"
export default {
  name: 'App',
  components: {
    pageHeader,
    pageFooter,
    pageBody
  }
}
</script>

<style>
a{
  text-decoration: none;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
