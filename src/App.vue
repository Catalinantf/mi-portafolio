<template>
  <div id="app">
    <h1 class="p-5 header">Catalina Tapia</h1>
    <div id="nav">
      <router-link to="/">Inicio</router-link> |
      <router-link to="/about">Acerca de</router-link>
    </div>
    <router-view />
    <Footer />
  </div>
</template>
<script>
import Footer from "@/components/footer.vue";

export default {
  name: "App",
  components: {
    Footer,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #332b44;

  background-color: #ebece2;
}
.header {
  background-color: white;
}

#nav {
  padding: 30px;
}
h1 {
  color: #3d2b44;
}
#nav a {
  font-weight: bold;
  color: #3d2b44;
}

#nav a.router-link-exact-active {
  color: #c8c896;
}
</style>
