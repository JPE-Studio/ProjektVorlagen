# Skill: Design-System

Ziel: Seite soll gestaltet aussehen, nicht generiert. Erst Tokens, dann Layout, dann Details.

## 1. Tokens festlegen (in `site/styles.css` oben als CSS-Variablen)

```css
:root {
  --farbe-hintergrund: /* neutrale Fläche, nicht reinweiß, z.B. #faf9f7 */;
  --farbe-text: /* mindestens 4.5:1 auf Hintergrund */;
  --farbe-akzent: /* EINE Signalfarbe für Aktionen, nicht mehr */;
  --abstand: 4px;   /* Basis — alles als Vielfaches: 8/12/16/24/48/96 */
  --radius: 8px;
  --schrift: /* 1 charaktervolle Font + 1 System-Fallback */;
}
```

## 2. Anti-Generik-Regeln (die "AI-Look"-Fehler)

- Keine 3 gleichen Karten nebeneinander, wenn 2 + 1 hervorgehoben reichen.
- Keine Lila-Blau-Gradienten. Akzentfarbe sparsam: Buttons, Links, ein Highlight.
- Überschriften mit Hierarchie: klare Größensprünge (1.6x), nicht fein abgestuft.
- Weißraum gewinnt: Sektionen mit min. 96px vertikalem Abstand trennen.
- Ein Held pro Seite: eine große Aussage, eine Aktion. Kein Karussell.

## 3. Layout-Reihenfolge

1. Typografie-Skala festlegen (body 1rem, Faktor 1.25–1.333)
2. Mobile zuerst bauen, dann `@media (min-width: 48rem)` Breakpoint ergänzen
3. Container max-width: 64rem, mit padding 24px

## 4. Buttons & Interaktion

- Primärbutton: gefüllt, Akzentfarbe. Sekundär: Outline. Es gibt genau einen Primärstil.
- Hover: sanft (Farbe/Transform 150ms ease). Fokus: 2px Outline in Akzentfarbe, nie `outline: none`.
