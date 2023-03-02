<template>
  <!-- <NavbarVue :title="title"/>
  <router-view/> -->
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <SiteFooter/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import SiteFooter from './components/SiteFooter.vue'
// import NavbarVue from './components/NavbarVue.vue'


export default {
  name: 'App',
  components: {
    // NavbarVue,
    HelloWorld,
    SiteFooter
},
  data() {
    return {
      title: 'My App'
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
