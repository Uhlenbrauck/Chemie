# Mathe GK Q2 – Binomialverteilung

Absprachen zur Reihe und zum Tool `binomialverteilung.html`.

## Ablauf der Reihe

| Schritt | Material | Inhalt | Tool |
|---|---|---|---|
| 1 | **AB 34** | Galtonbrett (PhET-Simulation), Wege und Wahrscheinlichkeiten für die Eimer bei p = 1/2 | – |
| 2 | **AB 35** | „Schiefes“ Galtonbrett, Term für P(E_k) bei P(rechts) = p | – |
| 3 | **AB 36** | Bernoulli-Experiment, Bernoulli-Kette, Zufallsgröße X, Definition der Binomialverteilung, GTR (binomPdf, binomCdf) | – |
| 4 | Erarbeitungsseite (statt AB) | Histogramme lesen, danach Abhängigkeit von n und p untersuchen | Teil 1 `#lesen`, Teil 2 `#erkunden` |
| 5 | **AB 37** | Übungen aus dem Buch | – |

## Links

- Erarbeitungsseite: https://uhlenbrauck.github.io/unterricht/mathe/q2/binomialverteilung-erarbeitung.html
  (Sprungziele `#aufgabe1`, `#aufgabe2`)
- Teil 1: https://uhlenbrauck.github.io/unterricht/mathe/q2/binomialverteilung.html#lesen
- Teil 2: https://uhlenbrauck.github.io/unterricht/mathe/q2/binomialverteilung.html#erkunden
- Lehrermodus: `…/binomialverteilung.html?lehrer#erkunden`

## Tool: getroffene Entscheidungen

**Teil 1 – Histogramm lesen:** fest eingestellt auf n = 10, p = 0,2 (das GTR-Beispiel aus AB 36,
die Werte kennen die S aus ihrer Tabelle). Keine Regler. Antippen eines Balkens zeigt
k und P(X = k) mit vier Nachkommastellen. Der höchste Balken ist hier bewusst **nicht**
hervorgehoben, weil Auftrag 2 danach fragt.

**Teil 2 – n und p verändern:**
- n von 10 bis 50 (Regler und −/+), p von 0 bis 1 in Schritten von 0,01. Start: n = 10, p = 0,5.
- Der höchste Balken ist orange. Bei gleich hohen Balken sind beide orange.
- „Hochachse festhalten“ ist beim Start an, die Hochachse reicht dann bis 0,3. So sieht man,
  dass das Histogramm mit wachsendem n flacher wird. Ab n = 10 bleiben alle Balken unter 0,3,
  solange 0,22 ≤ p ≤ 0,78 gilt. Höhere Balken (z. B. n = 10, p = 0,1, und die Extremfälle p = 0, p = 1)
  werden oben gekappt: weiße Bruchkante und Pfeil nach oben, der Wert ist per Antippen lesbar.
  Ausgeschaltet passt sich die Hochachse an, und die Form ist besser zu erkennen.
- „Vergleichsbild merken“ lässt das aktuelle Histogramm gestrichelt stehen.
  Die Rechtsachse reicht dann bis zum größeren der beiden n.
- Antippen eines Balkens zeigt wie in Teil 1 k und P(X = k); der Balken bekommt einen Rahmen.
- Kein Erwartungswert, keine Standardabweichung (noch nicht eingeführt).

**Lehrermodus (`?lehrer`):** n und p für Teil 1, kleinstes und größtes n am Regler (bis 100),
Obergrenze der festen Hochachse, „Werte kopieren“ (Tabelle k, P(X = k) des angezeigten Histogramms).

**Didaktische Reduktion:** Die Balken haben die Breite 1 (von k − 0,5 bis k + 0,5).
Deshalb ist ihr Flächeninhalt gleich ihrer Höhe, und die Wahrscheinlichkeit lässt sich an der
Höhe ablesen. Im Tool sind die Balken zur besseren Lesbarkeit etwas schmaler gezeichnet.

## Arbeitsaufträge

Stehen auf der Erarbeitungsseite `binomialverteilung-erarbeitung.html` (Aufgabe 1 zu Teil 1, Aufgabe 2 zu Teil 2).
Das Tool ist dort bei jeder Aufgabe eingebettet (`binomialverteilung.html?eingebettet#…`, ohne Titel und Reiter).
Breiter Bildschirm (iPad quer): Aufgaben links, Tool rechts und mitlaufend. Schmal (hochkant): Tool oben, Aufgaben darunter.

Lösungen gehören nicht ins Repo.
