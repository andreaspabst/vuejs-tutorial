# vuejs-tutorial
Dies ist ein Tutorial von [Vue Seminare und Schulungen](https://www.vuejs-seminar.de/).
Jetzt hier lesen: [Vue JS Tutorial Anfänger](https://www.vuejs-seminar.de/vuejs-tutorial-anfaenger/)

## Vorwort
Dieses Tutorial soll den perfekten und einfachen Einstieg in die Welt des Vue JS Frameworks bieten. Du kannst das Wissen über Vue JS 3 auch in Vue JS 2 einsetzen, da wir uns hier auf die Composition API fokussieren. Die Setup API ist, wenn man die Composition API beherrscht, leicht erlernbar, da es sich “eigentlich” stark an Javascript anlehnt und leicht verständlich ist👍🏽

Für den Einstieg in Vue JS entwickeln wir eine eigene, kleine Todo App auf Basis von Vue JS – zunächst ohne API. Wir gehen Schritt für Schritt die Anforderungen durch um mit Vue JS erfolgreich zu starten! Ebenfalls erklären wir dir die einzelnen Bestandteile, was sie bedeuten und wie Du sie einsetzt.

## An wen richtet sich dieses VueJS Tutorial?
Grundsätzlich beschränkt sich dieses Tutorial auf das VueJS Framework. Dies bedeutet, dass Kenntnisse in der Javascript bzw. HTML Entwicklung bestehen sollten. Falls du deine HTML Kenntnisse auffrischen oder dich ganz neu damit beschäftigen möchtest, dann habe ich hier die perfekten HTML Anfänger/Auffrischkurse:

Sollte bislang eher prozedual statt objektorientiert entwickelt worden sein, empfehle ich vorab ein PHP OOP Tutorial für Einsteiger. Falls die beiden Begriffe jeweils unbekannt sind, empfehle ich meinen anderen Kurs Einstieg in die Programmierung mit PHP.

## Lieber ein VueJS Video Tutorial ansehen?
Falls Videos eher zu Deinen Präferenzen gehört, haben wir einen Vue JS Onlinekurs aufgesetzt.

[![Vue JS Onlinekurs](https://apprex-live.s3.eu-central-1.amazonaws.com/apprex_71c9344d-8e5c-4e40-98db-ffc171a95d6c/113/vue3.jpg)](https://www.codercampus.de/courses/vue-js-online-kurs/?utm_source=app_wordpress&cam=VJS.de_Blog/)

## Warum Vue JS?
- In der min-Variante (also die komprimierte) nur ganze 20 KB klein
- Extrem schnelle Seiten dank virtuellem DOM
- Bekanntes HTML, CSS und natürlich JavaScript verwendbar
- Geringer Aufwand, steile Lernkurve und Effizienz für große Projekte
- Nur das was man braucht, also relativ wenig Overhead

## Was ist Vue JS
Bei Vue.js handelt es sich allgemein gesagt um ein (Frontend-)Framework für Webanwendungen, mit dem man auf Basis von Javascript komponentenorientiert entwickeln kann. Viele Magazine im Netz sind der Meinung, dass es im Vergleich zu anderen Frameworks den Vorteil hat besonders schlank zu sein. Die Performance des Frameworks ist zudem besonders gut. Zudem ist Vue anpassungsfähig, einfach erweiterbar und universell einsetzbar. Also lasst uns loslegen und in diesem Tutorial die Eckpfeiler von Vue JS beleuchten.

## Vue JS Voraussetzungen
### 1) HTML5 kennen, können und beherrschen
Um erfolgreich Vue JS zu lernen sind einige Voraussetzungen zu erfüllen, wie etwa das Lernen von HTML. Wir empfehlen hierbei zB. die Grundlagen von HTML-Einfach.de oder für intensivere Einarbeitung unseren [HTML Onlinekurs](https://www.codercampus.de/courses/html-lernen-onlinekurs?ref=vjs).

### 2) Modernes JavaScript (zB. ECMA-Script bzw. ES6,…)
Wer sich bei “HTML5 kennen” gerade noch dachte, ja das kriege ich sehr gut hin, jetzt aber bei ECMA-Script ausgestiegen ist, dem empfehlen wir an dieser Stelle die JavaScript Grundlagen von SelfHTML durchzuarbeiten und mit dem ein oder anderen Projekt bereits Erfahrungen mit (modernem) JavaScript zu sammeln.

Wir haben aber auch hierfür eine YouTube Playlist auf unserem ständig aktualisierten YouTube Kanal erstellt, mit deren Hilfe ihr Euch noch einmal einen Überblick über die modernen JavaScript Grundlagen verschaffen könnt.

## Warum überhaupt ein Framework?
### Standards, Werkzeugkästen und Modernes JS

Aus welchen Blickwinkeln man es auch betrachtet, Frameworks helfen uns enorm in den Punkten Struktur, Standards und (Abwärts-)Kompatibilität. Denn abgesehen von dem Vorteil das Rad nicht ständig neu erfinden zu müssen, helfen die Standards von Frameworks vor allem in der Teamarbeit. Sie bringen Struktur, Standards und Kontinuität in unsere Anwendungsentwicklung. Modernes JavaScript wird schon seit einiger Zeit aus genau diesem Grund durch immer neue Frameworks angereichert. Doch ist es dabei besonders wichtig, vor allem auf ein Framework zu setzen, welches große internationale Anerkennung, eine lebhafte Community und somit auch viele Erweiterungen um sich scharen kann.

Frameworks können also auch als Werkzeugkästen gesehen werdne. Solche wie React, Angular JS oder eben Vue JS sind mittlerweile echte Vorreiter geworden.

### Web Components

In den Anfangszeiten von HTML, und das bildet noch heute die Grundlage, waren Entwickler durch einige, wenige Elemente beschränkt. Diese waren div, h1, h2, h3,... sowie p oder auch table bzw. form. Hiermit wird vor allem deutlich, dass der Ursprung "Web-Seiten" dem Umstand entsprang, dass die HTML Dokumente maßgeblich strukturierte Dokumente mit Überschriften (h1, h2, h3,...), Absätzen (p) und diversen Inhaltselementen (div) waren. Als Facebook, Google usw. damit begonnen nicht mehr nur ihr Unternehmen als Webseite vorzustellen sondern das Web als eine Art Anwendungsplattform verstanden, waren diese Elemente nicht mehr genug, die WebComponents waren geboren. Diese wurden von W3C (dem World Wide Web Consortium) maßgeblich vorangetrieben. Die WebComponents sollten sowohl Standard-Komponenten enthalten als auch eigene, von Entwicklern entworfene Komponenten im Browser ermöglichen. Doch als Organisation waren sie profitorientierten Unternehmen in der Umsetzung nicht schnell genug, weshalb eine nicht-native (also nicht bereits im Browser eingebaute Funktionalität) andere Variante gefunden werden musste. React und Angular waren geboren, Vue JS kam nach und dutzende andere Frameworks folgten dem Siegeszug.

### Dein perfekter Start mit Vue JS

Wir bieten mit unseren Onlinekursen deinen perfekten Start in das Framework!
[![Vue JS Onlinekurs](https://apprex-live.s3.eu-central-1.amazonaws.com/apprex_71c9344d-8e5c-4e40-98db-ffc171a95d6c/113/vue3.jpg)](https://www.codercampus.de/courses/vue-js-online-kurs/?utm_source=app_wordpress&cam=VJS.de_Blog/)

Der Start mit Vue JS
Minimalaufwand der Initialisierung

Etwas zu initiieren meint in der Fach- sowie Umgangssprache so viel wie beginnen, ins Leben rufen oder erschaffen.
Grundsätzlich muss darauf aufmerksam gemacht werden, dass beim Einsatz von Vue JS nur die Einbindung des Vue JS Core Quellcodes, welcher sehr klein ist, über das <script>-Tag notwendig ist. Anschließend muss initialisiert werden. Dies erfolgt aber durch die Einbindung von unserer app.js, worin die Anweisung `mount(#app)` steckt.

Nun sind wir startklar für den ersten Inhalt unserer Anwendung.

## Erstes Projekt erstellen

Kläre bitte, ob "Node JS" und "npm" auf deinem Rechner installiert sind, indem Du "node" und "npm" in die Kommandozeile eingibst. Dann können wir den npm Init Befehl für Vue JS ausführen, der dir alle wichtigen Bestandteile von Vue JS installiert.

Jetzt weiterlesen: [Vue JS Tutorial Anfänger](https://www.vuejs-seminar.de/vuejs-tutorial-anfaenger/)