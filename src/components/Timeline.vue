<template>
    <div>
        <v-row>
            <v-col>
                <section id="about" class="about">
                <img class="about__img" src="img/andrii_chemerys_photo.jpg" alt="">
                
                <div class="about__timeline timeline">
                    <div class="timeline__body">
                        <h2 class="timeline__page-name timeline__text-to-align">Portfolio</h2>
                        <h1 class="timeline__name timeline__text-to-align">Andrii Chemerys</h1>
                        <h2 class="timeline__profession timeline__text-to-align">Architekt</h2>
                        <h2 class="timeline__section timeline__text-to-align">Doświadczenie zawodowe</h2>
                        <div class="timeline__item">
                            <p class="timeline__time">10.2019-obecnie</p>
                            <div class="timeline__content">
                                <h3 class="timeline__title">Architekt w Portyk Architekci Sp. z o.o. Sp.k. w Warszawie</h3>
                                <p class="timeline__paragraph">Opracowywanie projektu budowlanego i projektu wykonawczego dla budynku mieszkalnego przy ul.  Winorośli w Warszawie.</p>
                            </div>
                        </div>     
                        <div class="timeline__item">3                            <p class="timeline__time">03.2019-10.2019</p>
                            <div class="timeline__content">
                                <h3 class="timeline__title">Asystent Architekta w Płaskowicki i Partnerzy Architekci w Warszawie</h3>
                                <p class="timeline__paragraph">Opracowywanie projektu budowlanego dla hotelu Baltic Wave w Kołobrzegu.</p>
                            </div>
                        </div>    
                        <div class="timeline__item">
                            <p class="timeline__time">01.2016-02.2019</p>
                            <div class="timeline__content">
                                <h3 class="timeline__title">Asystent Architekta w APA Markowski Sp. z o.o. w Warszawie</h3>
                                <p class="timeline__paragraph">Projekt wykończenia wnętrz oraz koordynacja międzybranżowa projektu wykonawczego wysokościowca Złota 44 w Warszawie.<br/> Opracowywanie projektów  budowlanych.</p>
                            </div>
                        </div>   
                        <h2 class="timeline__section timeline__text-to-align">Wykształcenie</h2>  
                        <div class="timeline__item">
                            <p class="timeline__time">2010-2017</p>
                            <div class="timeline__content">
                                <h3 class="timeline__title">Architektura i Urbanistyka (I st.) / Architektura (II st.)</h3>
                                <p class="timeline__paragraph">Wyższa Szkoła Ekologii i Zarządzania w Warszawie.<br/> 
                                Specjalność: Projektowanie architektoniczne.<br/>
                                Tytuł zawodowy: Inżynier architekt / magister inżynier architekt.</p>
                            </div>
                        </div>     
                        <div class="timeline__item">
                            <p class="timeline__time">2005-2009</p>
                            <div class="timeline__content">
                                <h3 class="timeline__title">Informatyka</h3>
                                <p class="timeline__paragraph">Technikum Informatyczne IFNTUNiG w Iwano-Frankiwsk.<br/>
                                Specjalność: Inżynieria oprogramowania.<br/>
                                Tytuł zawodowy:  Technik informatyk-programista.</p>
                            </div>
                        </div>     
                    </div>
                </div>
            </section>
            </v-col>
        </v-row>
    </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
$color-primary: #222d31;
$color-secondary: #bbace6;
$color-border: #ededf3;
$color-background: #ffffff;
$color-background-secondary: #d8cff0;
$color-timeline-line: #d8cff0;
$color-timeline-bg: #ffffff;

.timeline {
  &__body {
    position: relative;
    margin-left: 100px;
    border-radius: 0 8px 8px 0;
    padding: 5px 0;
    // max-width: 900px;

    &:after {
      content: "";
      width: 2px;
      height: 100%;

      background-color: $color-timeline-line;
      position: absolute;
      left: -5px;
      top: 0;
    }
  }

  &__text-to-align {
    position: relative;
    left: 10px;
  }

  &__profession {
    margin-bottom: 10px;
    padding-bottom: 10px;
    // border-bottom: 1px dashed $color-timeline-line;
  }

  &__item {
    position: relative;

    &:after {
      content: "";
      width: 14px;
      height: 14px;
      border-radius: 50%;
      border: 2px solid $color-timeline-line;
      background-color: $color-timeline-bg;
      position: absolute;
      left: -13px;
      top: 3px;
      z-index: 1;
    }
  }

  &__time {
    position: absolute;
    left: -135px;
    top: 0px;
    opacity: 0.75;
    text-align: right;
    width: 10%;
  }

  &__content {
    margin: 10px;
    padding-bottom: 10px;
    border-bottom: 1px dashed $color-timeline-line;
  }

  &__title {
    margin-bottom: 5px;
  }
}
</style>
