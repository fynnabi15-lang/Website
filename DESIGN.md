# Design: EB Werbetechnik – Websites für kleine Firmen

Richtung (aktuell): wie die Brock-Elektrotechnik-Seite. Dunkel (#05070c), Blau-Akzent #1f8fff / #5cb6ff, Überschriften fett, kursiv, Versalien, Raster-Hintergrund im Hero, Buttons mit blauem Verlauf und Glow. Die Farbtabelle unten ist veraltet (frühere helle Variante).

## Farben (Light / Dark)
| Rolle | Light | Dark |
|---|---|---|
| Hintergrund | #faf8f4 | #111317 |
| Fläche (Karten) | #ffffff | #1a1d23 |
| Text | #16181d | #f2efe9 |
| Text gedämpft | #5a5f69 | #a6abb5 |
| Linie | #e4dfd5 | #2b2f38 |
| Akzent (Buttons) | #c2410c | #fb8a4c |
| Text auf Akzent | #ffffff | #111317 |
| Platzhalter-Markierung | #fff3b0 | #5a4b00 |

## Schrift
System-Schrift (system-ui). Überschriften 800, eng gesetzt, `clamp()` für Größen. Fließtext 17–18 px, Zeilenhöhe 1.6.

## Abstände und Form
Sektionen 88 px vertikal (mobil 56 px), Inhaltsbreite max. 1120 px, 20 px Seitenrand. Radius 14 px (Karten), 10 px (Buttons). Schatten nur dezent.

## Komponenten
- **Button primär:** Akzentfläche, 52 px hoch, sichtbarer Fokusring (3 px Akzent, 3 px Abstand).
- **Button sekundär:** transparent, 2 px Rahmen.
- **Karte:** Fläche, 1 px Linie, Radius 14 px.
- **Platzhalter:** gelb markiert, Format `[TEXT]`, muss vor Livegang ersetzt werden.
