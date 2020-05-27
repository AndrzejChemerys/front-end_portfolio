<template>
  <v-app>
    <v-content>
      <HelloWorld/>
      <Timeline/>
      <Projects/>
      <Footer/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import Timeline from "./components/Timeline";
import Projects from "./components/Projects";
import Footer from "./components/Footer";

export default {
  name: "App",

  components: {
    HelloWorld,
    Timeline,
    Projects,
    Footer,
  },

  data: () => ({
    //
  }),
};
</script>
