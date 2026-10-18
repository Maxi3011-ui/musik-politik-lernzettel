# Musik – Lernzettel zur Klassenarbeit

**Live:** https://maxi3011-ui.github.io/musik-politik-lernzettel/

## Ausschließliche Inhaltsquelle

`Musik_Lernzettel_Klassenarbeit.pdf`, Seiten 1–3. Die Lerninhalte sind aus dieser PDF übertragen; auf Wunsch ersetzt die bereitgestellte Grafik `mlto10b.jpg` das bisherige Quintenzirkel-Grundwissen. Sie ist unverändert als `quintenzirkel-dur.jpg` eingebunden, ohne Link oder Vergrößerungshinweis. Frühere Texte und externe Quellen sind nicht Bestandteil dieser Fassung. Die Original-PDF wird nicht mitveröffentlicht.

## Gliederung

Die Navigation folgt fünf Aufgabenbereichen; die Zwischenüberschriften benennen die jeweilige Frage:

| Bereich | Gesuchte Antwort |
| --- | --- |
| Lied analysieren | Definitionen, Text- und Musikmerkmale, Wirkung, Aufbau und Musterantwort zum „Lied der Partei“ |
| Lieder: DDR & NS | Politischer Zweck der Musik sowie Inhalt und Werte der einzelnen Unterrichtslieder |
| Vier-Akte-Modell | Vier Akte nennen und am NS-Jugendlied anwenden |
| „Entartete Musik“ | Begriff erklären, Mendelssohn und Webern einordnen und vergleichen |
| Quintenzirkel (Dur) | Vorzeichen und Dur-Tonarten in der bereitgestellten Grafik finden |

Die Musterantwort ist vollständig übernommen. Der Quintenzirkel zeigt ausschließlich Dur-Tonarten und ihre Vorzeichen; Molltonarten, Tabellen und Erklärungstexte sind entfernt. Texte sind für kleine Bildschirme in kürzere Absätze und Stichpunkte gegliedert.

## Technik und Bedienung

Statische Seite ohne externe Laufzeitabhängigkeiten. `content.js` enthält ausschließlich den Lernstoff; `index.html` enthält Darstellung und Navigation. Fünf Aufgabenbereiche im Dropdown; Unterthemen sind per URL verlinkbar, z. B. `#vier-akte`, `#hymne` und `#dur-quintenzirkel`. Für Handy, schmale Watch-Ansichten ab 160 px und Browserdruck.

```sh
python3 -m http.server 8876 --bind 127.0.0.1
```

`http://127.0.0.1:8876` öffnen. GitHub Pages veröffentlicht aus `main` und dem Stammverzeichnis.
