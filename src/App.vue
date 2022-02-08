<template>
  <div id="app">
    <Header />
    <Main />
    <Footer />
    <Credits />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";
import Credits from "./components/Credits.vue";

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer,
    Credits,
  }
}
</script>

<style lang="scss">
*{
  margin: 0 auto;
  padding: 0;
  box-sizing: border-box;
}
body{
  font-family: 'PT Sans Narrow', sans-serif;
}
</style>
