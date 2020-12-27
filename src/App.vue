<template>
  <div id="app">
    <h1>Hello new learning</h1>
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>

    <p>Bienvenue sur notre page d'<HomeLink></HomeLink></p>

    <nav>
      <NavLink url="/" text="Accueil" />
      <NavLink url="/about" text="À propos" />
      <NavLink url="/contact" text="Contact" />
    </nav>

  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'
import HomeLink from "@/components/HomeLink";
import NavLink from "@/components/NavLink";

export default {
  name: 'App',
  components: {
    HelloWorld,
    HomeLink,
    NavLink
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
