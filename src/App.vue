<template>
  <div id="app">
     <h2>2121212</h2>
     <h3>44444<h3>
     <h4>aaaaaaaa</h4>
         <h5>master</h5>
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
