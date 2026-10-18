# Musik – Lernzettel zur Klassenarbeit

**Live:** https://maxi3011-ui.github.io/musik-politik-lernzettel/

## Ausschließliche Inhaltsquelle

`Musik_Lernzettel_Klassenarbeit.pdf`, Seiten 1–3. Sämtliche Lerninhalte sind neu aus dieser PDF übertragen. Frühere Texte und externe Quellen sind nicht Bestandteil dieser Fassung. Die Original-PDF wird nicht mitveröffentlicht.

## Gliederung

Die acht PDF-Abschnitte sind in vier Dropdown-Bereiche zusammengefasst:

| Bereich | Abschnitte der PDF |
| --- | --- |
| Grundlagen | 1: Agitatorische Musik und Wir-Lieder; Analyseschema aus 2; 8: Fünf Sätze |
| DDR | 2: Musteraufgabe „Lied der Partei“; 3: Hintergrund und Unterrichtslieder |
| Nationalsozialismus | 4: Musik als Propaganda; 5: Vier-Akte-Modell; 6: „Entartete Musik“ und verfemte Werke |
| Quintenzirkel | 7: Grundwissen, Tonarten, paralleles Moll und Vorgehen |

Die Musterantwort ist vollständig übernommen. Die Tonartentabelle enthält ausschließlich die 13 Dur-/Moll-Paare der PDF. Texte sind für kleine Bildschirme in kürzere Absätze und Stichpunkte gegliedert.

## Technik und Bedienung

Statische Seite ohne externe Laufzeitabhängigkeiten. `content.js` enthält ausschließlich den Lernstoff; `index.html` enthält Darstellung und Navigation. Vier Hauptbereiche im Dropdown; Unterthemen sind per URL verlinkbar, z. B. `#vier-akte`, `#hymne` und `#tonarten`. Für Handy, schmale Watch-Ansichten ab 160 px und Browserdruck.

```sh
python3 -m http.server 8876 --bind 127.0.0.1
```

`http://127.0.0.1:8876` öffnen. GitHub Pages veröffentlicht aus `main` und dem Stammverzeichnis.
