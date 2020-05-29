<template>
  <v-footer dark padless>
    <v-card flat tile class="indigo lighten-1 white--text text-center footer">
      <v-card-text>
        <v-btn v-for="icon in icons" :key="icon" class="mx-4 white--text" icon>
          <a class="mx-4 white--text footer__link" :href="icon.url" :target="icon.target"><v-icon size="24px">{{ icon.name }}</v-icon></a>
        </v-btn>
      </v-card-text>

      <v-card-text class="white--text pt-0 text">
        <span>Designed and built by Andrii Chemerys with Vue.js and Vuetify.</span><br />
        <a target="_blank" href="https://icons8.com/icons/set/npm">NPM</a>, <a target="_blank"
          href="https://icons8.com/icons/set/vue-js">Vue Js</a> and other icons by <a target="_blank"
          href="https://icons8.com">Icons8</a>
      </v-card-text>

      <v-divider></v-divider>

      <v-card-text class="white--text">
        {{ new Date().getFullYear() }} <strong></strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<script>
export default {
  data: () => ({
    // icons: ["mdi-github", "mdi-linkedin", "mdi-facebook", "mdi-instagram"],
    icons: [
      {
        name: "mdi-github",
        url: "https://github.com/AndriiChemerys",
        target: "_blank",
      },
      {
        name: "mdi-linkedin",
        url: "https://www.linkedin.com/in/andrii-chemerys-b95074151/",
        target: "_blank",
      },
      {
        name: "mdi-facebook",
        url: "https://www.facebook.com/andrii.chemerys/",
        target: "_blank",
      },
      {
        name: "mdi-instagram",
        url: "https://www.instagram.com/andrii_chemerys/",
        target: "_blank",
      },
    ],
  }),
};
</script>

<style>
</style>