<template>
    <v-footer
    dark
    padless
  >
    <v-card
      flat
      tile
      class="indigo lighten-1 white--text text-center footer"
    >
      <v-card-text>
        <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-4 white--text"
          icon
        >
          <v-icon size="24px">{{ icon }}</v-icon>
        </v-btn>
      </v-card-text>

      <v-card-text class="white--text pt-0">
        <span>Designed and built by Andrii Chemerys with Vue.js and Vuetify.</span><br/>
        <a target="_blank" href="https://icons8.com/icons/set/npm">NPM</a>, <a target="_blank" href="https://icons8.com/icons/set/vue-js">Vue Js</a> and other icons by <a target="_blank" href="https://icons8.com">Icons8</a>
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
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
};
</script>

<style>
.footer {
  width: 100%;
}
</style>
