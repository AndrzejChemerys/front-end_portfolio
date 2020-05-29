<template>
  <div>
    <v-app-bar color="transparent" dense fixed collapse-on-scroll>
      <v-app-bar-nav-icon>
        x
      </v-app-bar-nav-icon>

      <v-toolbar-title>Andrii Chemerys - Front-End Portfolio</v-toolbar-title>

      <v-spacer></v-spacer>

      <!-- <v-btn icon>
        <v-icon>mdi-heart</v-icon>
      </v-btn> -->

      <!-- <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn> -->

      <v-menu left bottom>
        <template v-slot:activator="{ on }">
          <v-btn icon v-on="on">
            <v-icon>mdi-dots-vertical</v-icon>
          </v-btn>
        </template>

        <v-list>
          <!-- <v-list-item v-for="n in menuItems" :key="n.itemId" @click="goToPage(n.itemId)" :href="n.itemId">
            <v-list-item-title>{{ n.itemId }}</v-list-item-title>
          </v-list-item> -->
          <v-list-item href="#about">
            About Me
          </v-list-item>
          <v-list-item href="#projects">
            Projects
          </v-list-item>
          <v-list-item href="#skills">
            Skills
          </v-list-item>
          <v-list-item href="#timeline">
            Learning Roadmap
          </v-list-item>
        </v-list>
      </v-menu>
    </v-app-bar>

  </div>


</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({
    drawer: false,
    // menuItems: ["asd", "asd", "qwe", "qwe"],
    // menuItems: [
    //   { itemId: "Home" },
    //   { itemId: "Projects" },
    //   { itemId: "Skills" },
    // ],
  }),
  // methods: {
  //   goToPage(page) {
  //     alert(page);
  //   },
  // },
};
</script>
<style>
.projects {
  /* max-width: 1500px; */
  padding: 0 4vw;
}
</style>