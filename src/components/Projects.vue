<template>
    <div>
        <v-container id="projects" fluid class="projects" justify="center">
            <v-row>
                <v-col>
                    <h2 class="projects__title">Projekty</h2>
                    <h3 class="projects__subtitle"></h3>
                </v-col>
            </v-row>

            <v-row justify="center" class="projects__row">
                <v-col cols="12" md="" lg="4">
                    <Project1/>
                </v-col>

                <v-col cols="12" md="" lg="4">
                    <Project6/>
                </v-col>

                <v-col cols="12" md="" lg="4">
                    <Project8/>
                </v-col>
            </v-row>

            <v-row justify="center" class="projects__row">
                <v-col cols="12" md="" lg="4">
                    <Project7/>
                </v-col>

                <v-col cols="12" md="" lg="4">
                    <Project5/>
                </v-col>            
            </v-row>

            <v-row justify="center" class="projects__row">
                <v-col cols="12" md="" lg="4">
                    <Project2/>
                </v-col>

                <v-col cols="12" md="" lg="4">
                    <Project3/>
                </v-col>

                <v-col cols="12" md="" lg="4">
                    <Project4/>
                </v-col>
            </v-row>

        </v-container>
    </div>
</template>

<script>
import Project1 from "./projects/Project1";
import Project2 from "./projects/Project2";
import Project3 from "./projects/Project3";
import Project4 from "./projects/Project4";
import Project5 from "./projects/Project5";
import Project6 from "./projects/Project6";
import Project7 from "./projects/Project7";
import Project8 from "./projects/Project8";

export default {
  name: "Projects",

  components: {
    Project1,
    Project2,
    Project3,
    Project4,
    Project5,
    Project6,
    Project7,
    Project8,
  },
};
</script>

<style>
</style>