# Unterricht

Unterrichtsmaterial (Animationen, Simulationen, Hilfekarten) für Chemie und Mathe.
Veröffentlicht über GitHub Pages: https://uhlenbrauck.github.io/unterricht/

Arbeitsweise und Konventionen: `CLAUDE.md`. Absprachen zu einzelnen Reihen liegen neben dem Material,
z. B. `chemie/7/aggregatzustaende-reihe.md`.

Die Datei `.nojekyll` muss bleiben: Ohne sie verarbeitet GitHub Pages das Repo mit Jekyll,
und Ordner mit `_` am Anfang (z. B. `h/_bilder/`) würden nicht ausgeliefert.

## Aufbau

```
index.html            Startseite mit Übersicht
chemie/<stufe>/       Materialien nach Jahrgang (7, 9, ef, q1, …)
mathe/<stufe>/        ebenso für Mathe
h/<kennung>/          Hilfekarten, eine Seite pro Karte (erzeugt, nicht von Hand bearbeiten)
qr/<kennung>.png/svg  QR-Code zu jeder Hilfekarte (erzeugt)
hilfen/*.md           Quellen der Hilfekarten
hilfen/bilder/        Bilder für Hilfekarten
hilfen/UEBERSICHT.md  Liste aller Hilfekarten mit Adresse (erzeugt)
assets/               gemeinsames Design
tools/hilfen.py       erzeugt Hilfekarten und QR-Codes
```

## Hilfekarten

- Jede Karte hat eine feste Kennung, z. B. `c7-agg-1b-1` (Chemie 7, Aggregatzustände, Aufgabe 1b, Karte 1),
  und damit eine feste Adresse: `https://uhlenbrauck.github.io/unterricht/h/c7-agg-1b-1/`.
- Die Adresse steht fest, bevor die Karte geschrieben ist. Der QR-Code kann also schon aufs Arbeitsblatt,
  und spätere Korrekturen ändern ihn nicht. **Kennungen nie umbenennen oder neu vergeben.**
- Karten schreiben: in `hilfen/<thema>.md` (Format siehe `tools/hilfen.py`), dann

  ```
  pip install markdown segno
  python3 tools/hilfen.py
  ```

- Nur eigenes Material verwenden: Das Repo ist öffentlich, Abbildungen aus Schulbüchern gehören nicht hinein.
