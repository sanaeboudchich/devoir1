<template>
  <div id="app">
    <section id="content">
      <Header />
      <HelloWorld />
      <Apropo/>
      <br>
      <Noservice/>
      <br>
      <Article />

      <blog/>
      <br>
      <Logo/>
      <Footer/>
      <Arrow/>
    </section>
  </div>

</template>

<script>
import Header from './components/Header.vue'
import HelloWorld from './components/HelloWorld.vue'
import Footer from './components/Footer.vue'
import Article from "@/components/Article"
  import Apropo from "@/components/Apropo"
    import Noservice from "@/components/Noservice"
      import Logo from "@/components/Logo"
        import Blog from "@/components/Blog"
          import Arrow from "@/components/Arrow";
export default {
  name: 'App',
  components: {
    Header ,
    HelloWorld,
    Apropo,
    Noservice,
    Article,
    Blog,
    Logo,
    Footer,
    Arrow


  }
}
</script>

<style>
#app {
  font-family: 'Ubuntu', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
