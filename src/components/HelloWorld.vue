<template>
 <div>
    <v-app-bar
      color="deep-purple accent-4"
      dense
      dark
    >
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title>Page title</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-heart</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>

      <v-menu
        left
        bottom
      >
        <template v-slot:activator="{ on }">
          <v-btn icon v-on="on">
            <v-icon>mdi-dots-vertical</v-icon>
          </v-btn>
        </template>

        <v-list>
          <v-list-item
            v-for="n in 5"
            :key="n"
            @click="() => {}"
          >
            <v-list-item-title>Option {{ n }}</v-list-item-title>
          </v-list-item>
        </v-list>
      </v-menu>
    </v-app-bar>

    <section section="main">
      <div class="main__image"></div>
      <!-- <img class="main__image" src="" alt="Photo of Andrii Chemerys in front of Lake Como"> -->
    </section>


    <v-parallax
      dark
      src="@/assets/img/wjs_img2.jpg"
    >
      <v-row
        align="center"
        justify="center"
      >
        <v-col class="text-center" cols="12">
          <h1 class="display-1 font-weight-thin mb-4">Vuetify.js</h1>
          <h4 class="subheading">Build your application today!</h4>
        </v-col>
      </v-row>
    </v-parallax>
    


  </div>


</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({
    drawer: false,
  }),
};
</script>
<style>
.projects {
  /* max-width: 1500px; */
  padding: 0 4vw;
}

.main {
  padding: 20px;
}

.main__image {
  margin: 0 auto;

  border-radius: 50%;
  width: 300px;
  height: 300px;
  background-color: red;
  background-image: url("~@/assets/img/andrii_chemerys_photo_como.jpg");
  background-size: 200%;
  background-position: 35% 30%;

  /* z-index: 10; */
  /* object-fit: cover; */
}
</style>
