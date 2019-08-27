<template>
  <div id="app">
    <img src="./assets/logo.png">
    <h1>site:{{site}}</h1>
    <h1>url:{{url}}</h1>
    <h1>{{details()}}</h1>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
  // var vm = new Vue({
  //   el:'#app',
  //   data:{
  //     site:"教程",
  //     url:"www.runoob.com",
  //     alexa:"10000"
  //   },
  //   methods:{
  //     details:function () {
  //       return this.site+"-xxxxxxx-bbbbbb-ddddddd"
  //     }
  //   }
  // })
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
