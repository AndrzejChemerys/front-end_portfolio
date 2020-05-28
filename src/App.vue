<template>
  <v-app>
    <v-content>
      <Header/>
      <About/>
      <Skills/>
      <Projects/>
      <Timeline/>
      
      <Footer/>
    </v-content>
  </v-app>
</template>

<script>
import Header from "./components/Header";
import About from "./components/About";
import Skills from "./components/Skills";
import Timeline from "./components/Timeline";
import Projects from "./components/Projects";
import Footer from "./components/Footer";

export default {
  name: "App",

  components: {
    Header,
    About,
    Skills,
    Timeline,
    Projects,
    Footer,
  },

  data: () => ({
    //
  }),
};
</script>

<style>
</style>

