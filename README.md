# Musik-Lernzettel – Musik und Politik

11. Klasse · DDR und Nationalsozialismus

**Live:** https://maxi3011-ui.github.io/musik-politik-lernzettel/

## Inhalt

Das Dropdown enthält bewusst nur fünf Hauptbereiche:

1. **Grundlagen:** Agitation, Wir-Lieder, typische Mittel und Wirkungen, Vier-Akte-Modell, Lernreihenfolge.
2. **Nationalsozialismus:** Propaganda, „Es zittern die morschen Knochen“, Modellanwendung, „entartete Musik“, Mendelssohn und Webern.
3. **DDR:** Geschichte, Musikerziehung, vier Liedbeispiele und die Nationalhymne.
4. **Musiklehre:** Analysebegriffe, Punktierung, Wirkung begründen, Quintenzirkel und Dur-/Moll-Zuordnung bis sieben Vorzeichen.
5. **Musterantworten:** fünf ausformulierte Antworten zu typischen Aufgaben.

## Grundlage

Grundlage ist die vom Nutzer bereitgestellte Zusammenfassung. Die darin erwähnten 14 Unterrichtsseiten und das Themenbild lagen nicht vor. Die Seite behauptet deshalb keinen vollständigen Abgleich mit diesen Materialien. Historische Einordnung und einzelne fachliche Präzisierungen wurden mit den in `content.js` verlinkten Quellen abgeglichen. Konkrete Liedanalysen müssen in der Klassenarbeit am gegebenen Noten- oder Hörbeispiel belegt werden.

## Technik und Bedienung

Statische Seite ohne externe Laufzeitabhängigkeiten. `content.js` enthält Inhalte und Quellen; `index.html` Darstellung und Navigation. Layout für Handy und schmale Watch-Ansichten ab 160 px. Die fünf Kapitel stehen im Dropdown; Unterthemen können per URL verlinkt werden, z. B. `#vier-akte`, `#hymne` oder `#tonarten`. Druck über den Browser öffnet die Quellen vorübergehend mit.

```sh
python3 -m http.server 8876 --bind 127.0.0.1
```

Danach `http://127.0.0.1:8876` öffnen. GitHub Pages veröffentlicht aus `main` und dem Stammverzeichnis.
