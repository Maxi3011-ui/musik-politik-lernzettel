# Musik – Lernzettel zur Klassenarbeit

**Live:** https://maxi3011-ui.github.io/musik-politik-lernzettel/

## Ausschließliche Inhaltsquelle

`Musik_Lernzettel_Klassenarbeit.pdf`, Seiten 1–3. Die Lerninhalte sind aus dieser PDF übertragen; auf Wunsch ersetzt die bereitgestellte Grafik `mlto10b.jpg` das bisherige Quintenzirkel-Grundwissen. Sie ist unverändert als `quintenzirkel-dur.jpg` eingebunden, ohne Link oder Vergrößerungshinweis. Frühere Texte und externe Quellen sind nicht Bestandteil dieser Fassung. Die Original-PDF wird nicht mitveröffentlicht.

## Gliederung

Die acht PDF-Abschnitte sind in vier Dropdown-Bereiche zusammengefasst:

| Bereich | Abschnitte der PDF |
| --- | --- |
| Grundlagen | 1: Agitatorische Musik und Wir-Lieder; Analyseschema aus 2; 8: Fünf Sätze |
| DDR | 2: Musteraufgabe „Lied der Partei“; 3: Hintergrund und Unterrichtslieder |
| Nationalsozialismus | 4: Musik als Propaganda; 5: Vier-Akte-Modell; 6: „Entartete Musik“ und verfemte Werke |
| Quintenzirkel | Dur-Kreisgrafik anstelle des Textabschnitts 7 |

Die Musterantwort ist vollständig übernommen. Der Quintenzirkel zeigt ausschließlich Dur-Tonarten und ihre Vorzeichen; Molltonarten, Tabellen und Erklärungstexte sind entfernt. Texte sind für kleine Bildschirme in kürzere Absätze und Stichpunkte gegliedert.

## Technik und Bedienung

Statische Seite ohne externe Laufzeitabhängigkeiten. `content.js` enthält ausschließlich den Lernstoff; `index.html` enthält Darstellung und Navigation. Vier Hauptbereiche im Dropdown; Unterthemen sind per URL verlinkbar, z. B. `#vier-akte`, `#hymne` und `#dur-quintenzirkel`. Für Handy, schmale Watch-Ansichten ab 160 px und Browserdruck.

```sh
python3 -m http.server 8876 --bind 127.0.0.1
```

`http://127.0.0.1:8876` öffnen. GitHub Pages veröffentlicht aus `main` und dem Stammverzeichnis.
