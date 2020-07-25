<template>
  <div id="app">
     <h2>21212121eeeea</h2>
     <h3>111111111<h3>
     <p v-html="msg"></p>
  </div>
</template>

<script>

export default {
  name: 'App',
  data(){
    return {
      msg:"<a href='http://www.baidu.com'></a>"
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
