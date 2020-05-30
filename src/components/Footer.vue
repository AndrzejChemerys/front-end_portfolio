<template>
  <v-footer dark padless>
    <v-card flat tile class="blue-grey darken-1 white--text text-center footer">
      <v-card-text>
        <v-btn v-for="icon in icons" :key="icon" class="mx-4 white--text" icon>
          <a class="mx-4 white--text footer__link" :href="icon.url" :target="icon.target">
            <v-icon size="24px">{{ icon.name }}</v-icon>
          </a>
        </v-btn>
      </v-card-text>

      <v-card-text class="white--text pt-0 text footer__icons-text">
        <span class="footer__signature">Designed and built with &#9825; by Andrii Chemerys, using Vue.js and Vuetify.</span><br />
        <a class="footer__icons-text white--text" target="_blank" href="https://icons8.com/icons/set/npm">NPM</a>, <a
          class="footer__icons-text white--text" target="_blank" href="https://icons8.com/icons/set/vue-js">Vue Js</a>
        and other icons by <a class="footer__icons-text white--text" target="_blank"
          href="https://icons8.com">Icons8</a><br/>
      </v-card-text>

      <v-divider class="footer__divider"></v-divider>

      <v-card-text class="white--text">
        <span class="footer__rights">Wszelkie prawa zastrzeżone / All rigths reserved</span>  <br/>
        <span>&copy; {{ new Date().getFullYear() }} </span> 
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<script>
export default {
  data: () => ({
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