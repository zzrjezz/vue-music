
<template>
  <div id="app">
  <my-header></my-header>
  <my-header></my-header>
  <my-header></my-header>
    <div id="nav">
      <router-link to="/">Home</router-link> 
      <router-link to="/about">推荐音乐</router-link>
      <router-link to="/my">热歌榜</router-link>
      <router-link to="/my-element">搜索</router-link>

    </div>
    <router-view/>
     name:{{name}}   show:{{show}} 
  </div>
</template>

<script>
import myHeader from '@/views/my-header'
export default {
  name:"header",
  components: {
myHeader
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
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  margin-left: 1em;
}

#nav a.router-link-exact-active {
  color: #D43C33;
}
</style>
