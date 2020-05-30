<template>
    <v-parallax id="skills" dark src="@/assets/img/wjs_img2-dark2.jpg" class="skills-parallax-image">
        <v-row align="center" justify="center" class="skills-section">
            <v-col class="text-center" cols="12">
                <h3 class="skills-section__title">Umiejętności, technologie i narzędzia:</h3>
                <h4 class="skills-section__subtitle"></h4>
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
                        <p class="skills__text mb-1">Photoshop</p>
                        <div class="skills__bar-wrapper">
                            <div class="skills__progress-bar">
                                <span class="skills__progress-bar-fill" style="width: 75%;"></span>
                            </div>
                        </div>
                    </v-col>
                    <v-col cols="2">
                        <img class="skills__image" src="@/assets/icons/icons8/icons8-adobe-xd-100.png" alt="">
                        <p class="skills__text mb-1">XD</p>
                        <div class="skills__bar-wrapper">
                            <div class="skills__progress-bar">
                                <span class="skills__progress-bar-fill" style="width: 50%;"></span>
                            </div>
                        </div>
                    </v-col>
                    <v-col cols="2">
                        <img class="skills__image" src="@/assets/icons/icons8/icons8-adobe-indesign-100.png" alt="">
                        <p class="skills__text mb-1">InDesign</p>
                        <div class="skills__bar-wrapper">
                            <div class="skills__progress-bar">
                                <span class="skills__progress-bar-fill" style="width: 50%;"></span>
                            </div>
                        </div>
                    </v-col>
                    <v-col cols="2">
                        <img class="skills__image skills__img--vscode" src="@/assets/icons/icons8/vscode_.png" alt="">
                        <p class="skills__text mb-1">VS Code</p>
                        <div class="skills__bar-wrapper">
                            <div class="skills__progress-bar">
                                <span class="skills__progress-bar-fill" style="width: 70%;"></span>
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
</style>