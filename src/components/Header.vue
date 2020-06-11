<template>
  <div>
    <v-app-bar color="transparent" dense fixed collapse-on-scroll>
      <v-app-bar-nav-icon>
        <a href="#about">
          <img src="@/assets/img/logo_andrii_chemerys.png" class="page-logo" alt="">
        </a>
      </v-app-bar-nav-icon>

      <v-toolbar-title>Andrii Chemerys - Front-End Portfolio</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-menu left bottom>
        <template v-slot:activator="{ on }">
          <v-btn icon v-on="on">
            <v-icon>mdi-dots-vertical</v-icon>
          </v-btn>
        </template>

        <v-list>
          <v-list-item href="#about">
            Hej!
          </v-list-item>
          <v-list-item href="#projects">
            Projekty
          </v-list-item>
          <v-list-item href="#skills">
            Umiejętności
          </v-list-item>
          <v-list-item href="#aboutme">
            O mnie
          </v-list-item>
          <v-list-item href="#timeline">
            Ścieżka rozwoju
          </v-list-item>
        </v-list>
      </v-menu>
    </v-app-bar>

  </div>


</template>

<script>
export default {
  name: "Header",

  data: () => ({
    drawer: false,
  }),
};
</script>
<style>
</style>