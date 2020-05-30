<template>
    <div>
        <v-row id="aboutme">
            <v-col>
                <h2 class="aboutme__title">O mnie:</h2>
                <h3 class="aboutme__subtitle">Jestem początkującym programistą Front-End, dążącym do ciągłego rozwoju i poznawania nowych technologii. Charakteryzuje mnie pozytywne nastawienie i otwartość umysłu, praca w zespole i dynamiczne tempo pracy nie sprawia mi trudności. Obecnie skupiam się na doskonaleniu swoich umiejętności w technologiach Vue.js, HTML, CSS i JavaScript.</h3>
            </v-col>
        </v-row>
        <v-divider class="aboutme__divider"></v-divider>
        <v-row>
            <v-col>
                <h3 class="timeline-section__title" id="timeline">Moja ścieżka rozwoju w IT:</h3>
                <v-timeline class="timeline">
                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="@/assets/icons/timeline/vuemastery.jpg">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date"> 04.2020-obecnie</span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="timeline__title">
                                <a href="https://github.com/AndriiChemerys/vue" target="_blank" class="timeline__link">
                                    Kursy internetowe Vue.js na Vue Mastery.
                                </a>
                            </v-card-title>
                            <v-card-text class="timeline__desc">
                                Najlepsze źródło wiedzy dla programistów Vue<br />
                                Cotygodniowe kursy Vue.js, które poprowadzą Cię do mistrzostwa.
                            </v-card-text>
                        </v-card>
                    </v-timeline-item>
                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="@/assets/icons/timeline/warsawjs.jpg">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">11.05.2020</span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="timeline__title">
                                <a href="https://github.com/AndriiChemerys/warsawjs-workshop-44-2" target="_blank"
                                    class="timeline__link">
                                    Workshop #44 “Seria: Trening Architekta — Wzorce projektowe“
                                    od WarsawJS.
                                </a>
                            </v-card-title>
                            <v-card-text class="timeline__desc">
                                Wprowadzenie do wzorców projektowych.
                                Wzorzec obserwator - operacyjny.
                                Wzorzec faktory - kreacyjny.
                                Wzorzec strategia - operacyjny.
                                Wzorzec fasada - strukturalny.
                            </v-card-text>
                        </v-card>
                    </v-timeline-item>
                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="@/assets/icons/timeline/udemy.jpg">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date"> 04.2020-obecnie</span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="timeline__title">
                                <a href="https://github.com/AndriiChemerys/vue" target="_blank" class="timeline__link">
                                    Kurs internetowy “Build Web Apps with Vue JS 2 & Firebase“ na Udemy.
                                </a>
                            </v-card-title>
                            <v-card-text class="timeline__desc">
                                Vue JS i Firebase od podstaw. Implementacja uwierzytelniania Firebase w aplikacjach
                                internetowych Vue JS. Firestore, funkcje w chmurze i hosting. 11,5 godzin.
                            </v-card-text>
                        </v-card>
                    </v-timeline-item>
                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="@/assets/icons/timeline/udemy.jpg">                                
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">03.2020-obecnie</span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class=" timeline__title">
                                <a href="https://github.com/AndriiChemerys/practice_/tree/master/6_js_100_algorithms_challenge" target="_blank"
                                    class="timeline__link">
                                    Kurs internetowy “100 Algorithms Challenge” na Udemy.
                                </a>
                            </v-card-title>
                            <v-card-text class="timeline__desc">
                                Rozwiązywanie dziesiątków trudnych algorytmów i różnych wyzwań za pomocą JavaScript i TypeScript.
                            </v-card-text>
                        </v-card>
                    </v-timeline-item>
                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="@/assets/icons/timeline/warsawjs.jpg">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">23.02.2020</span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class=" timeline__title">
                                <a href="https://github.com/AndriiChemerys/warsawjs-workshop-41-4" target="_blank"
                                    class="timeline__link">
                                    Workshop #41 “JavaScript dla początkujących “
                                    od WarsawJS.
                                </a>
                            </v-card-title>
                            <v-card-text class="timeline__desc">
                                Tworzenie aplikacji z wykorzystaniem HTML, CSS i JavaScript: ”Habits App”.
                            </v-card-text>
                        </v-card>
                    </v-timeline-item>
                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="@/assets/icons/timeline/alx.jpg">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date"> 01.2020-03.2020</span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="timeline__title">
                                <a href="https://github.com/AndriiChemerys/alx_js" target="_blank"
                                    class="timeline__link">
                                    Bootcamp “Programista JavaScript “ w ALX w
                                    Warszawie.
                                </a>
                            </v-card-title>
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
                                <img class="timeline__img" src="@/assets/icons/timeline/daftcode.jpg">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">03.2019-04.2019</span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="  timeline__title">
                                <a href="https://github.com/AndriiChemerys/daftacademy-frontend_levelup-spring2019-clock"
                                    target="_blank" class="timeline__link">
                                    Kurs od DaftAcademy “Front End Level Up” w
                                    Warszawie.
                                </a>
                            </v-card-title>
                            <v-card-text class="timeline__desc">
                                Konfiguracja projektu frontendowego. Preprocesory, frameworki i metodologie w
                                stylowaniu. Asynchroniczny JS. Crashtest.
                            </v-card-text>
                        </v-card>
                    </v-timeline-item>
                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="@/assets/icons/timeline/udemy.jpg">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">
                                02.2019-obecnie
                            </span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="  timeline__title">
                                <a href="https://github.com/AndriiChemerys/natours_project" target="_blank"
                                    class="timeline__link">
                                    Kurs internetowy “Advanced CSS and Sass: Flexbox, Grid, Animations and More!” na Udemy.
                                </a>
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
                                <img class="timeline__img" src="@/assets/icons/timeline/websamurai.jpg">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">
                                01.2019-04.2019
                            </span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="  timeline__title">
                                <a href="https://github.com/AndriiChemerys/web-samurai_front-end_courses"
                                    target="_blank" class="timeline__link">
                                    Kurs internetowy “Programowanie w JavaScript” na Udemy.
                                </a>
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
                                <img class="timeline__img" src="@/assets/icons/timeline/daftcode.jpg">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">
                                11.2018-12.2018
                            </span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="  timeline__title">
                                <a href="https://github.com/AndriiChemerys/daftacademy_frontend4begginers"
                                    target="_blank" class="timeline__link">
                                    Kurs od DaftAcademy “Front End 4 Beginners” w Warszawie.
                                </a>
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
                                <img class="timeline__img" src="@/assets/icons/timeline/websamurai.jpg">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">
                                09.2018-10.2018
                            </span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="  timeline__title">
                                <a href="https://github.com/AndriiChemerys/web-samurai_front-end_courses"
                                    target="_blank" class="timeline__link">
                                    Kurs internetowy “Front-End zaawansowany w 15 dni” na Udemy.
                                </a>
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
                                <img class="timeline__img" src="@/assets/icons/timeline/treehouse.jpg">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">
                                03.2018-10.2018
                            </span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="  timeline__title">
                                <a href="https://github.com/AndriiChemerys/treehouse_front-end_course" target="_blank"
                                    class="timeline__link">
                                    Kurs internetowy “Front End Web Development Track” na Treehouse.
                                </a>
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
                                <img class="timeline__img" src="@/assets/icons/timeline/zlota.jpg">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">
                                01.2016-obecnie
                            </span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="  timeline__title">
                                <a href="https://andriichemerys.github.io/architecture_portfolio/" target="_blank"
                                    class="timeline__link">
                                    Doświadczenie zawodowe: Asystent Architekta / Architekt
                                </a>
                            </v-card-title>
                            <v-card-text class="timeline__desc">
                                Architekt w Portyk Architekci Sp. z o.o. Sp.k. w Warszawie.<br />
                                Asystent Architekta w Płaskowicki i Partnerzy Architekci w Warszawie.<br />
                                Asystent Architekta w APA Markowski Sp. z o.o. w Warszawie.
                            </v-card-text>
                        </v-card>
                    </v-timeline-item>
                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="@/assets/icons/timeline/wseiz.jpg">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">
                                2010–2017
                            </span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="  timeline__title">
                                <a href="http://www.wseiz.pl/pl/" target="_blank" class="timeline__link">
                                    Wykształcenie: Architektura i Urbanistyka (I st.) / Architektura (II st.)
                                </a>
                            </v-card-title>
                            <v-card-text class="timeline__desc">
                                Wyższa Szkoła Ekologii i Zarządzania w Warszawie.<br />
                                Specjalność: Projektowanie architektoniczne.<br />
                                Tytuł zawodowy: Inżynier architekt / magister inżynier architekt.
                            </v-card-text>
                        </v-card>
                    </v-timeline-item>
                    <v-timeline-item large class="timeline__item">
                        <template v-slot:icon>
                            <v-avatar>
                                <img class="timeline__img" src="@/assets/icons/timeline/kep.jpg">
                            </v-avatar>
                        </template>
                        <template v-slot:opposite>
                            <span class="timeline__date">
                                2005-2009
                            </span>
                        </template>
                        <v-card class="elevation-2 timeline__card">
                            <v-card-title class="  timeline__title">
                                <a href="http://www.ifkepnung.if.ua/" target="_blank" class="timeline__link">
                                    Wykształcenie: Informatyka.
                                </a>
                            </v-card-title>
                            <v-card-text class="timeline__desc">
                                Technikum Informatyczne IFNTUNiG w Iwano-Frankiwsk. <br />Specjalność: Inżynieria
                                oprogramowania.<br />
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

<style>
</style>