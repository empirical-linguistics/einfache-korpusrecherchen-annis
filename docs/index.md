---
title: "Einfache Korpusrecherchen in ANNIS: Ein Schnelleinstieg"
author: "Stefan Hartmann"
date: "2020-06-29"
---




# Einführung

In diesem kurzen Tutorial zeige ich, wie man in Korpora, die über die Plattform ANNIS verfügbar sind, einfache Korpusrecherchen durchführen kann und wie man die Ergebnisse anschließend in Form einer KWIC-Konkordanz in ein Tabellenkalkulationsprogramm exportieren kann. Dabei liegt der Fokus vor allem auf dem letztgenannten Aspekt, also den Herausforderungen, die der Export mit sich bringt. Für die Suche in ANNIS gibt es nämlich schon eine ganze Reihe hervorragender Tutorials zusätzlich zur sehr ausführlichen und hilfreichen Dokumentation. Beispielsweise gibt es [hier](https://www.linguistik.hu-berlin.de/de/institut/professuren/korpuslinguistik/corpus-tools/annis-tutorials) einige Videotutorials und [hier](https://corpus-tools.org/annis/resources/SE_HistorischeKorpora_ANNIS2015-05-06.pdf) einen Einstieg am Beispiel des RIDGES-Korpus.

ANNIS ist ein Such- und Visualisierungstool, das zum einen als Open-Source-Software herunterladbar und auf dem eigenen Rechner verwendbar ist, zum anderen auch über verschiedene öffentliche Instanzen online verwendet werden kann. In diesem Tutorial beschäftigen wir uns nur mit diesem Szenario, also der Nutzung von Online-Schnittstellen.

Da prinzipiell jede/r, der oder die einen Server zur Verfügung hat, eine eigene öffentliche ANNIS-Instanz starten kann, gibt es mehrere Instanzen, über die unterschiedliche Korpora verfügbar sind. Nennenswerte ANNIS-Instanzen sind:

- HU Berlin: Hier finden sich u.a. das Referenzkorpus Altdeutsch (Deutsch Diachron Digital, kurz DDD), das Lernerkorpus FALKO oder auch das RIDGES-Korpus, mit dem wir im folgenden Beispiel arbeiten werden: <https://korpling.german.hu-berlin.de/annis3/>

- Georgetown University: Über diese Instanz ist z.B. das Georgetown University Multilayer Corpus (GUM) verfügbar, https://corpling.uis.georgetown.edu/annis-corpora/

- Über eine Bonner ANNIS-Instanz ist das für die germanistische Sprachgeschichtsforschung sehr wichtige Bonner Frühneuhochdeutschkorpus verfügbar https://korpora.zim.uni-due.de/FnhdC/

- Das Referenzkorpus Mittelhochdeutsch ist auf einer Bochumer ANNIS-Instanz zu finden: https://www.linguistics.rub.de/rem/

Diese Liste ließe sich noch fortsetzen. Wichtig zu wissen ist, dass die grundlegenden Methoden, die wir im Folgenden kennenlernen werden, sich im Grunde auf alle über ANNIS verfügbaren Korpora übertragen lassen.

Zu den deutschsprachigen Korpora, die über öffentliche ANNIS-Instanzen verfügbar sind, gehören unter anderem

- [das Referenzkorpus Altdeutsch](https://www.deutschdiachrondigital.de/)
- [das Referenzkorpus Mittelhochdeutsch](https://www.linguistics.rub.de/rem/)
- [das Bonner Frühneuhochdeutschkorpus](https://korpora.zim.uni-due.de/FnhdC/)
- [das Referenzkorpus Frühneuhochdeutsch](https://www.linguistics.rub.de/ref/)
- [das RIDGES-Korpus ("Registers in Diachronic German Science")](https://www.linguistik.hu-berlin.de/de/institut/professuren/korpuslinguistik/forschung/ridges-projekt/)
- [das Kiezdeutsch-Korpus (Registrierung erforderlich)](https://www.kiezdeutschkorpus.de/kidko-home-EN.html)

In diesem Tutorial arbeiten wir mit dem RIDGES-Korpus, das, wie viele andere Korpora auch, über [https://korpling.german.hu-berlin.de/annis3/](https://korpling.german.hu-berlin.de/annis3/) verfügbar ist.

Für alle, die lieber schauen statt lesen, gibt eine auch eine Video-Version des Tutorials (die minimal anders ist und außerdem mein allererstes Video, deshalb teilweise etwas holprig). Um es zu sehen, klappen Sie einfach durch Klick auf den Pfeil den entsprechenden Abschnitt aus:

<details>
<summary>klick mich</summary>

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/9pgjeFjj138" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

</details>


<img src="docs/fig/by-sa.png" width="20%" height="20%" style="display: block; margin: auto;" />

Dieses Tutorial wurde mit Hilfe von <a href="https://bookdown.org/" target="_blank">Bookdown</a> für <a href="https://www.r-project.org/" target="_blank">R</a> geschrieben und publiziert. Es ist lizenziert unter CC-BY-SA und kann gerne mit Quellenangabe weitergegeben und adaptiert werden.
