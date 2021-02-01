<template>
  <div id="app">
    <section id="content">
      <Header />
      <HelloWorld />
      <Apropo/>
      <Noservice/>
      <Article />
      <Footer/>
    </section>
  </div>

</template>

<script>
import Header from './components/Header.vue'
import HelloWorld from './components/HelloWorld.vue'
import Footer from './components/Footer.vue'
import Article from "@/components/Article"
  import Apropo from "@/components/Apropo"
    import Noservice from "@/components/Noservice";
export default {
  name: 'App',
  components: {
    Header ,
    HelloWorld,
    Apropo,
    Noservice,
    Article,
    Footer


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
