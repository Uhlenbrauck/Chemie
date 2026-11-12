# Mathe GK Q2 – Binomialverteilung

Absprachen zur Reihe und zum Tool `binomialverteilung.html`.

## Ablauf der Reihe

| Schritt | Material | Inhalt | Tool |
|---|---|---|---|
| 1 | **AB 34** | Galtonbrett (PhET-Simulation), Wege und Wahrscheinlichkeiten für die Eimer bei p = 1/2 | – |
| 2 | **AB 35** | „Schiefes“ Galtonbrett, Term für P(E_k) bei P(rechts) = p | – |
| 3 | **AB 36** | Bernoulli-Experiment, Bernoulli-Kette, Zufallsgröße X, Definition der Binomialverteilung, GTR (binomPdf, binomCdf) | – |
| 4 | Erarbeitungsseite (statt AB) | A1 Histogramm lesen (MC-Test), A2 Abhängigkeit von n und p, A3 zuordnen, A4 prüfen, A5 schätzen | Teile 1–5 |
| 5 | **AB 37** | Übungen aus dem Buch | – |
| 6 | AB kumulierte Binomialverteilung (nach AB 62 des LK) | MC-Test mit 50 Fragen, P(X ≥ 20) usw. A1 d) bereitet das qualitativ vor, ohne Summen zu berechnen. | – |

## Links

- Erarbeitungsseite: https://uhlenbrauck.github.io/unterricht/mathe/q2/binomialverteilung-erarbeitung.html
  (Sprungziele `#aufgabe1` … `#aufgabe5`)
- Tool: https://uhlenbrauck.github.io/unterricht/mathe/q2/binomialverteilung.html mit `#lesen`, `#erkunden`, `#zuordnen`, `#pruefen`, `#schaetzen`
- Lehrermodus: `…/binomialverteilung.html?lehrer#erkunden`

## Tool: getroffene Entscheidungen

**Teil 1 – Histogramm lesen:** Multiple-Choice-Test mit 10 Fragen und 4 Antworten (eine richtig),
Raten: n = 10, p = 0,25. Die Parameter stehen **nicht** im Diagramm, weil A1 a) danach fragt.
Keine Regler. Antippen eines Balkens zeigt k und P(X = k) mit vier Nachkommastellen.
Der höchste Balken ist bewusst nicht hervorgehoben (A1 c). Werte: P(X = 2) ≈ 0,2816 (Maximum),
P(X = 3) ≈ 0,2503, P(X ≥ 5) ≈ 0,078.

**Teil 2 – n und p verändern:**
- n von 10 bis 50 (Regler und −/+), p von 0 bis 1 in Schritten von 0,01. Start: n = 10, p = 0,5.
- Der höchste Balken ist orange. Bei gleich hohen Balken sind beide orange.
- „k-Achse festhalten“ (k von 0 bis 50) und „Hochachse festhalten“ (bis 0,3) sind getrennte Schalter,
  beim Start beide an. Ausgeschaltet passt sich die jeweilige Achse an.
- Mit fester Hochachse (bis 0,3) So sieht man,
  dass das Histogramm mit wachsendem n flacher wird. Ab n = 10 bleiben alle Balken unter 0,3,
  solange 0,22 ≤ p ≤ 0,78 gilt. Höhere Balken (z. B. n = 10, p = 0,1, und die Extremfälle p = 0, p = 1)
  werden oben gekappt: weiße Bruchkante und Pfeil nach oben, der Wert ist per Antippen lesbar.
  Ausgeschaltet passt sich die Hochachse an, und die Form ist besser zu erkennen.
- „Vergleichsbild merken“ lässt das aktuelle Histogramm gestrichelt stehen.
  Ohne feste k-Achse reicht die Rechtsachse bis zum größeren der beiden n.
- Antippen eines Balkens zeigt wie in Teil 1 k und P(X = k); der Balken bekommt einen Rahmen.
- Kein Erwartungswert, keine Standardabweichung (noch nicht eingeführt).

**Teil 3 – Zuordnen:** vier Histogramme A–D mit gleichen Achsen (k bis 40, Hochachse bis 0,25),
ohne Parameter. Die vier Verteilungen stehen auf der Erarbeitungsseite. Zuordnung steht nur im
Quelltext und im Lehrermodus.

**Teil 4 – Prüfen:** sechs Diagramme A–F mit angegebener Verteilung, Auswahl über Buchstaben,
Antippen zeigt die Balkenhöhe. Zwei passen, vier nicht (je ein anderer Fehler: Summe der Höhen,
Symmetrie, Anzahl der Gipfel, Lage des Gipfels). Die Auflösung steht nicht im Repo.

**Teil 5 – Schätzen:** zufällige Binomialverteilung mit n zwischen 10 und 40, p zwischen 0,10 und 0,90
in Schritten von 0,05 (nur Verteilungen mit allen Balken unter 0,3), Achsen fest wie in Teil 2.
Die Regler stellen die Schätzung ein, „Vergleichen“ legt sie als orangen Umriss darüber,
„Neues Histogramm“ würfelt neu. Fachlich: n ist am Histogramm nicht direkt ablesbar (die Balken
am rechten Rand sind praktisch 0), sondern nur über Lage und Breite zusammen mit p.

**Lehrermodus (`?lehrer`):** n und p für Teil 1, kleinstes und größtes n am Regler (bis 100),
Obergrenze der festen Hochachse, „n und p anzeigen“ (Teil 1, 3 und 5),
„Werte kopieren“ (Tabelle des angezeigten Diagramms, in Teil 3 die Parameter A–D).

**Didaktische Reduktion:** Die Balken haben die Breite 1 (von k − 0,5 bis k + 0,5).
Deshalb ist ihr Flächeninhalt gleich ihrer Höhe, und die Wahrscheinlichkeit lässt sich an der
Höhe ablesen. Im Tool sind die Balken zur besseren Lesbarkeit etwas schmaler gezeichnet.

## Arbeitsaufträge

Stehen auf der Erarbeitungsseite `binomialverteilung-erarbeitung.html` (Aufgabe n gehört zu Teil n des Tools).
A2 e) und f) sowie die ganze A5 sind Sprinteraufgaben.
Zu jeder Teilaufgabe gibt es einen aufklappbaren Tipp (Denkanstoß, keine Lösung), damit die S selbstständig arbeiten können.
Kein Hinweis „im Heft notieren“: Die meisten arbeiten am iPad, und Q2 weiß, dass Ergebnisse notiert werden.
Das Tool ist dort bei jeder Aufgabe eingebettet (`binomialverteilung.html?eingebettet#…`, ohne Titel und Reiter).
Breiter Bildschirm (iPad quer): Aufgaben links, Tool rechts und mitlaufend. Schmal (hochkant): Tool oben, Aufgaben darunter.

Lösungen gehören nicht ins Repo.
