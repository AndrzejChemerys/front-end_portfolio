<template>

  <v-row class="about" justify="center" align="center">
    
    <v-col class="" justify="center" align="center">

      <!-- <section class="about"> -->
      <div class="about__image"></div>
      <!-- <img class="main__image" src="" alt="Photo of Andrii Chemerys in front of Lake Como"> -->
      <h1 class="about__title">Andrii Chemerys</h1>
      <h2 class="about__subtitle">Junior Front-End Developer</h2>
      <!-- </section> -->
    </v-col>
  </v-row>

</template>

<script>
export default {};
</script>

<style>
/* Gradient effect */

.about {
  height: 100vh;
  background: linear-gradient(
        45deg,
        rgba(255, 175, 189, 0.5),
        rgba(100, 216, 243, 0.5),
        rgba(234, 236, 198, 0.5),
        rgba(245, 146, 176, 0.5),
        rgba(52, 219, 216, 0.5)
          /* rgba(255, 175, 189, 0.7),
        rgba(100, 216, 243, 0.7),
        rgba(234, 236, 198, 0.7),
        rgba(245, 146, 176, 0.7),
        rgba(52, 219, 216, 0.7) */
      )
      0 0 / 1000% no-repeat,
    /* url(https://picsum.photos/g/2000/1200?image=443) 0 0 / cover no-repeat; */
      url("~@/assets/img/bg/mountain1.jpg") 0 0 / cover no-repeat;
  -webkit-animation: gradientAnimation 40s ease infinite;
  animation: gradientAnimation 40s ease infinite;
}
@-webkit-keyframes gradientAnimation {
  0% {
    background-position: 0% 30%, 0 0;
  }
  50% {
    background-position: 100% 70%, 0 0;
  }
  100% {
    background-position: 0% 30%, 0 0;
  }
}
@keyframes gradientAnimation {
  0% {
    background-position: 0% 30%, 0 0;
  }
  50% {
    background-position: 100% 70%, 0 0;
  }
  100% {
    background-position: 0% 30%, 0 0;
  }
}
</style>