# Mathe GK Q2 – Binomialverteilung

Absprachen zur Reihe und zum Tool `binomialverteilung.html`.

## Ablauf der Reihe

| Schritt | Material | Inhalt | Tool |
|---|---|---|---|
| 1 | **AB 34** | Galtonbrett (PhET-Simulation), Wege und Wahrscheinlichkeiten für die Eimer bei p = 1/2 | – |
| 2 | **AB 35** | „Schiefes“ Galtonbrett, Term für P(E_k) bei P(rechts) = p | – |
| 3 | **AB 36** | Bernoulli-Experiment, Bernoulli-Kette, Zufallsgröße X, Definition der Binomialverteilung, GTR (binomPdf, binomCdf) | – |
| 4 | AB zum Tool | Histogramme lesen, danach Abhängigkeit von n und p untersuchen | Teil 1 `#lesen`, Teil 2 `#erkunden` |
| 5 | **AB 37** | Übungen aus dem Buch | – |

## Links

- Teil 1: https://uhlenbrauck.github.io/unterricht/mathe/q2/binomialverteilung.html#lesen
- Teil 2: https://uhlenbrauck.github.io/unterricht/mathe/q2/binomialverteilung.html#erkunden
- Lehrermodus: `…/binomialverteilung.html?lehrer#erkunden`

## Tool: getroffene Entscheidungen

**Teil 1 – Histogramm lesen:** fest eingestellt auf n = 10, p = 0,2 (das GTR-Beispiel aus AB 36,
die Werte kennen die S aus ihrer Tabelle). Keine Regler. Antippen eines Balkens zeigt
k und P(X = k) mit vier Nachkommastellen. Der höchste Balken ist hier bewusst **nicht**
hervorgehoben, weil Auftrag 2 danach fragt.

**Teil 2 – n und p verändern:**
- n von 1 bis 50 (Regler und −/+), p von 0 bis 1 in Schritten von 0,01.
- Der höchste Balken ist orange. Bei gleich hohen Balken (z. B. n = 3, p = 0,5) sind beide orange.
- „Hochachse festhalten“ ist beim Start an, die Hochachse reicht dann bis 1. So sieht man,
  dass das Histogramm mit wachsendem n flacher wird. Ausgeschaltet passt sich die Hochachse an,
  und die Form ist besser zu erkennen.
- „Vergleichsbild merken“ lässt das aktuelle Histogramm gestrichelt stehen.
  Die Rechtsachse reicht dann bis zum größeren der beiden n.
- Antippen eines Balkens zeigt wie in Teil 1 k und P(X = k); der Balken bekommt einen Rahmen.
- Kein Erwartungswert, keine Standardabweichung (noch nicht eingeführt).

**Lehrermodus (`?lehrer`):** n und p für Teil 1, größtes n am Regler (bis 100),
Obergrenze der festen Hochachse, „Werte kopieren“ (Tabelle k, P(X = k) des angezeigten Histogramms).

**Didaktische Reduktion:** Die Balken haben die Breite 1 (von k − 0,5 bis k + 0,5).
Deshalb ist ihr Flächeninhalt gleich ihrer Höhe, und die Wahrscheinlichkeit lässt sich an der
Höhe ablesen. Im Tool sind die Balken zur besseren Lesbarkeit etwas schmaler gezeichnet.

## Arbeitsaufträge (zum Einfügen ins AB)

**Aufgabe 1 | Was zeigt ein Histogramm?** (Teil 1)

Das Tool zeigt die Binomialverteilung aus AB 36 als **Histogramm**. Tippe auf die Balken.

a) Beschreibe, was auf der Rechtsachse und was auf der Hochachse abgetragen ist und was ein einzelner Balken darstellt.

b) Gib an, welchen Wert die Zufallsgröße X am wahrscheinlichsten annimmt. Vergleiche mit deiner GTR-Tabelle aus AB 36.

c) Bestimme P(X ≤ 2) mithilfe des Histogramms. Erläutere, wie man diese Wahrscheinlichkeit im Histogramm „sieht“.

d) Begründe, warum die Höhen aller Balken zusammen 1 ergeben.

e) Deute das Histogramm am Galtonbrett: Was bedeuten n, p und k, was bedeutet die Höhe eines Balkens?

**Aufgabe 2 | Wie hängt die Gestalt des Histogramms von n und p ab?** (Teil 2)

Mit „Vergleichsbild merken“ bleibt ein Histogramm gestrichelt stehen, sodass du zwei Einstellungen vergleichen kannst.

a) Stelle n = 10 ein und verändere p. Beschreibe, wie sich die Lage des höchsten Balkens verändert.

b) Vergleiche die Histogramme für p = 0,3 und p = 0,7 (n = 10). Erkläre deine Beobachtung mithilfe von Erfolg und Misserfolg.

c) Nenne die Besonderheit des Histogramms für p = 0,5 und begründe sie am Galtonbrett.

d) Stelle p = 0,3 ein und erhöhe n schrittweise von 5 bis 50. Beschreibe, wie sich Lage, Breite und Höhe des Histogramms verändern.

e) Erkläre, warum das Histogramm mit wachsendem n flacher werden muss. *Tipp: Aufgabe 1 d).*

f) Stelle eine Vermutung auf, bei welchem k der höchste Balken in Abhängigkeit von n und p liegt. Überprüfe deine Vermutung an drei selbst gewählten Beispielen.

g) *Für Schnelle:* Untersuche die Extremfälle p = 0 und p = 1. Erläutere die Histogramme.

Lösungen gehören nicht ins Repo.
