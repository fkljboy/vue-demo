<template>
  <div id="app">
    <button @click="jump">一键报障</button>
  </div>
</template>

<script>
export default {
  name: 'App',
  el:"#app",
  methods:{
    jump(){
      window.open('http://www.baidu.com')
    }
  }
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
