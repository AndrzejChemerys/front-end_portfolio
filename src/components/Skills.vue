<template>
    <v-parallax dark src="@/assets/img/wjs_img2.jpg" class="skills-parallax-image">
        <v-row align="center" justify="center" class="skills-section">
            <v-col class="text-center" cols="12">
                <h1 class="display-1 font-weight-thin mb-4">My skills:</h1>
                <h4 class="subheading">Build your application today!</h4>
                <v-row>
                    <v-col class="skills">
                        <img class="skills__image" src="@/assets/icons/icons8/icons8-html-5-100.png" alt="">
                        <p class="skills__text mb-1">HTML5</p>
                        <div class="skills__bar-wrapper">
                            <div class="skills__progress-bar">
                                <span class="skills__progress-bar-fill" style="width: 80%;"></span>
                            </div>
                        </div>
                    </v-col>
                    <v-col>
                        <img class="skills__image" src="@/assets/icons/icons8/icons8-css3-100.png" alt="">
                        <p class="skills__text mb-1">CSS3</p>
                        <div class="skills__bar-wrapper">
                            <div class="skills__progress-bar">
                                <span class="skills__progress-bar-fill" style="width: 80%;"></span>
                            </div>
                        </div>
                    </v-col>
                    <v-col>
                        <img class="skills__image" src="@/assets/icons/icons8/icons8-javascript-100.png" alt="">
                        <p class="skills__text mb-1">JavaScript</p>
                        <div class="skills__bar-wrapper">
                            <div class="skills__progress-bar">
                                <span class="skills__progress-bar-fill" style="width: 75%;"></span>
                            </div>
                        </div>
                    </v-col>
                    <v-col>
                        <img class="skills__image" src="@/assets/icons/icons8/icons8-sass-100.png" alt="">
                        <p class="skills__text mb-1">SASS</p>
                        <div class="skills__bar-wrapper">
                            <div class="skills__progress-bar">
                                <span class="skills__progress-bar-fill" style="width: 80%;"></span>
                            </div>
                        </div>
                    </v-col>
                    <v-col>
                        <img class="skills__image" src="@/assets/icons/icons8/icons8-git-100.png" alt="">
                        <p class="skills__text mb-1">Git</p>
                        <div class="skills__bar-wrapper">
                            <div class="skills__progress-bar">
                                <span class="skills__progress-bar-fill" style="width: 40%;"></span>
                            </div>
                        </div>
                    </v-col>
                    <v-col>
                        <img class="skills__image" src="@/assets/icons/icons8/icons8-npm-100.png" alt="">
                        <p class="skills__text mb-1">npm</p>
                        <div class="skills__bar-wrapper">
                            <div class="skills__progress-bar">
                                <span class="skills__progress-bar-fill" style="width: 40%;"></span>
                            </div>
                        </div>
                    </v-col>
                    <v-col>
                        <img class="skills__image" src="@/assets/icons/icons8/icons8-webpack-100.png" alt="">
                        <p class="skills__text mb-1">webpack</p>
                        <div class="skills__bar-wrapper">
                            <div class="skills__progress-bar">
                                <span class="skills__progress-bar-fill" style="width: 30%;"></span>
                            </div>
                        </div>
                    </v-col>
                    <!-- <v-col>
                        <img src="@/assets/icons/icons8/icons8-nodejs-100.png" alt="">
                    </v-col> -->
                    <!-- <v-col>
                        <img src="@/assets/icons/icons8/icons8-jquery-100-2.png" alt="">
                    </v-col>                 -->
                </v-row>

                <v-row justify="center">
                    <v-col cols="2">
                        <img class="skills__image" src="@/assets/icons/icons8/icons8-vue-js-100.png" alt="">
                        <p class="skills__text mb-1">Vue.js</p>
                        <div class="skills__bar-wrapper">
                            <div class="skills__progress-bar">
                                <span class="skills__progress-bar-fill" style="width: 30%;"></span>
                            </div>
                        </div>
                    </v-col>
                    <v-col cols="2">
                        <img class="skills__image skills__img--vuetify" src="@/assets/icons/icons8/vuetify_.png" alt="">
                        <p class="skills__text mb-1">Vuetify</p>
                        <div class="skills__bar-wrapper">
                            <div class="skills__progress-bar">
                                <span class="skills__progress-bar-fill" style="width: 30%;"></span>
                            </div>
                        </div>
                    </v-col>
                    <v-col cols="2">
                        <img class="skills__image" src="@/assets/icons/icons8/icons8-firebase-100.png" alt="">
                        <p class="skills__text mb-1">Firebase</p>
                        <div class="skills__bar-wrapper">
                            <div class="skills__progress-bar">
                                <span class="skills__progress-bar-fill" style="width: 30%;"></span>
                            </div>
                        </div>
                    </v-col>
                </v-row>

                <v-row justify="center">
                    <v-col cols="2">
                        <img class="skills__image" src="@/assets/icons/icons8/icons8-adobe-photoshop-100.png" alt="">
                        <p class="skills__text mb-1">Adobe Photoshop</p>
                        <div class="skills__bar-wrapper">
                            <div class="skills__progress-bar">
                                <span class="skills__progress-bar-fill" style="width: 75%;"></span>
                            </div>
                        </div>
                    </v-col>
                    <v-col cols="2">
                        <img class="skills__image" src="@/assets/icons/icons8/icons8-adobe-xd-100.png" alt="">
                        <p class="skills__text mb-1">Adobe XD</p>
                        <div class="skills__bar-wrapper">
                            <div class="skills__progress-bar">
                                <span class="skills__progress-bar-fill" style="width: 50%;"></span>
                            </div>
                        </div>
                    </v-col>
                    <v-col cols="2">
                        <img class="skills__image" src="@/assets/icons/icons8/icons8-adobe-indesign-100.png" alt="">
                        <p class="skills__text mb-1">Adobe InDesign</p>
                        <div class="skills__bar-wrapper">
                            <div class="skills__progress-bar">
                                <span class="skills__progress-bar-fill" style="width: 50%;"></span>
                            </div>
                        </div>
                    </v-col>
                    <v-col cols="2">
                        <img class="skills__image skills__img--vscode" src="@/assets/icons/icons8/vscode_.png" alt="">
                        <p class="skills__text mb-1">Visual Studio Code</p>
                        <div class="skills__bar-wrapper">
                            <div class="skills__progress-bar">
                                <span class="skills__progress-bar-fill" style="width: 80%;"></span>
                            </div>
                        </div>
                    </v-col>
                </v-row>

            </v-col>
        </v-row>
    </v-parallax>
</template>

<script>
export default {};
</script>

<style>
.skills-parallax-image {
  /* background-image: linear-gradient(rgba(0, 0, 0, 0.5),
                       rgba(0, 0, 0, 0.5)), url("url_of_image"); */
}

.skills-section {
  padding: 0 10vw;
}

.skills__image {
  width: 60px;
}

/* .skills__img--vscode {
  width: 100px;
} */

/* .skills__img--vuetify {
  width: 100px;
} */

.skills__text {
  margin-bottom: 5px;
}

.skills__bar-wrapper {
  width: 80px;
  margin: 0 auto;
}

.skills__progress-bar {
  width: 100%;
  background-color: #e0e0e0;
  padding: 2px;
  border-radius: 2px;
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.2);
}

.skills__progress-bar-fill {
  display: block;
  height: 8px;
  background-color: #737475;
  border-radius: 2px;

  transition: 500ms ease-in-out;
}
</style>