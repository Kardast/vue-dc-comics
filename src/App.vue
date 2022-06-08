<template>
  <div id="app">
    <header>
      <NavBar/>
    </header>

    <main>
      <ContentPart/>
      <BluePart/>
    </main>

    <footer>
      <FooterPart/>
      <FooterLowPart/>
    </footer>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import ContentPart from './components/ContentPart.vue'
import BluePart from './components/BluePart.vue'
import FooterPart from './components/FooterPart.vue'
import FooterLowPart from './components/FooterLowPart.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    ContentPart,
    BluePart,
    FooterPart,
    FooterLowPart
}
}
</script>

<style lang="scss">
// Regole generali
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
