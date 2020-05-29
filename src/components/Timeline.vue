<template>
    <div>
        <v-row>
            <v-col>
                <v-timeline class="timeline">
                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date"> 01.2020-03.2020</span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="timeline__title">Bootcamp “Programista JavaScript “ w ALX w
                                Warszawie.</v-card-title>
                            <v-card-text class="timeline__desc">
                                HTML, CSS, Semantyka HTML5, Selektory, DOM. JavaScript: Struktury danych. Zmienne,
                                pętle, warunki, OOP, ES5, ES6. Funkcje, klasy, obiekty. Tworzenie modali. Animacje,
                                manipulacje stroną. Sposoby przechowywania danych na stronie (storages, cookies).
                                SPA. Walidacja formularza. jQuery, AJAX, Node.js, React, JSX, REST. 120 godzin.
                            </v-card-text>
                        </v-card>
                    </v-timeline-item>

                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">23.02.2020</span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class=" timeline__title">Workshop #41 “JavaScript dla początkujących “
                                od WarsawJS.</v-card-title>
                            <v-card-text class="timeline__desc">
                                Tworzenie aplikacji z wykorzystaniem HTML, CSS i JavaScript: ”Habits App”. 8 godzin.
                            </v-card-text>
                        </v-card>
                    </v-timeline-item>

                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">03.2019-04.2019</span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="  timeline__title">Kurs od DaftAcademy “Front End Level Up” w
                                Warszawie.</v-card-title>
                            <v-card-text class="timeline__desc">
                                Konfiguracja projektu frontendowego. Preprocesory, frameworki i metodologie w
                                stylowaniu. Asynchroniczny JS. Crashtest.
                            </v-card-text>
                        </v-card>
                    </v-timeline-item>

                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">
                                02.2019-obecnie
                            </span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="  timeline__title">
                                Kurs internetowy “Advanced CSS and Sass: Flexbox, Grid, Animations and More!”.
                            </v-card-title>
                            <v-card-text class="timeline__desc">
                                Nowoczesne techniki CSS. Zaawansowane animacje CSS. Architektura CSS: projektowanie
                                oparte na komponentach, BEM, Flexbox. CSS Grid. Używanie Sass w rzeczywistych
                                projektach. Obrazy SVG i filmy w HTML i CSS. Ekosystem NPM. 28 godzin.
                            </v-card-text>
                        </v-card>
                    </v-timeline-item>
                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">
                                01.2019-04.2019
                            </span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="  timeline__title">
                                Kurs internetowy “Programowanie w JavaScript” na Udemy.
                            </v-card-title>
                            <v-card-text class="timeline__desc">
                                JavaScript w wersji ES5 i ES6. Umiejętność programowania proceduralnego w JavaScript.
                                Znajomość podstaw programowania zorientowanego obiektowo (OOP). 37 godzin.
                            </v-card-text>
                        </v-card>
                    </v-timeline-item>
                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">
                                11.2018-12.2018
                            </span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="  timeline__title">
                                Kurs od DaftAcademy “Front End 4 Beginners” w Warszawie.
                            </v-card-title>
                            <v-card-text class="timeline__desc">
                                HTML - tagi i ich atrybuty, fonty, ikony, zdjęcia i filmy. CSS Box Model. Chrome Dev
                                Tools, kolorystyka i cienie, Flexbox. Media Query, responsywność strony. Transformacje,
                                przejścia, animacje. Github i Github - pages.
                            </v-card-text>
                        </v-card>
                    </v-timeline-item>
                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">
                                09.2018-10.2018
                            </span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="  timeline__title">
                                Kurs internetowy “Front-End zaawansowany w 15 dni” na Udemy.
                            </v-card-title>
                            <v-card-text class="timeline__desc">
                                Tworzenie atrakcyjnych stron internetowych z wykorzystaniem zaawansowanych technik CSS,
                                JavaScript i jQuery. Animacje w CSS, Flexbox, CSS Grid, RWD, Sass. 38,5 godzin.
                            </v-card-text>
                        </v-card>
                    </v-timeline-item>
                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">
                                03.2018-10.2018
                            </span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="  timeline__title">
                                Kurs internetowy “Front End Web Development Track” na Treehouse.
                            </v-card-title>
                            <v-card-text class="timeline__desc">
                                Online szkoła nowych technologii “Treehouse”. HTML5, CSS3, JavaScript, Git, jQuery,
                                Bootstrap 4, Front End Performance Optimization, MediaElement.js, AJAX, OOJS itp.
                            </v-card-text>
                        </v-card>
                    </v-timeline-item>
                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">
                                01.2016-obecnie
                            </span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="  timeline__title">
                                Doświadczenie zawodowe: Asystent Architekta / Architekt
                            </v-card-title>
                            <v-card-text class="timeline__desc">
                                Architekt w Portyk Architekci Sp. z o.o. Sp.k. w Warszawie.<br/>
                                Asystent Architekta w Płaskowicki i Partnerzy Architekci w Warszawie.<br/>
                                Asystent Architekta w APA Markowski Sp. z o.o. w Warszawie.
                            </v-card-text>
                        </v-card>
                    </v-timeline-item>
                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">
                                2010–2017
                            </span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="  timeline__title">
                                Wykształcenie: Architektura i Urbanistyka (I st.) / Architektura (II st.)
                            </v-card-title>
                            <v-card-text class="timeline__desc">
                                Wyższa Szkoła Ekologii i Zarządzania w Warszawie.<br/>
                                Specjalność: Projektowanie architektoniczne.<br/>
                                Tytuł zawodowy: Inżynier architekt / magister inżynier architekt.
                            </v-card-text>
                        </v-card>
                    </v-timeline-item>
                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">
                                2005-2009
                            </span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="  timeline__title">
                                Wykształcenie: Informatyka.
                            </v-card-title>
                            <v-card-text class="timeline__desc">
                                Technikum Informatyczne IFNTUNiG w Iwano-Frankiwsk. <br/>Specjalność: Inżynieria
                                oprogramowania.<br/>
                                Tytuł zawodowy: Technik informatyk-programista.
                            </v-card-text>
                        </v-card>
                    </v-timeline-item>
                </v-timeline>

            </v-col>
        </v-row>
    </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
</style>