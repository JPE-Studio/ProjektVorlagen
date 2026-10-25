# Skill: Qualitäts-Check

Vor Übergabe durchgehen und als Liste ausgeben. Erst wenn alles ✓ ist, "fertig" sagen.

## Funktion

- [ ] Hauptaktion in ≤ 3 Sekunden erkennbar (was kann ich hier tun?)
- [ ] Alle Links/Buttons haben Ziel und funktionieren (nicht `href="#"`-Zombies)
- [ ] Formulare: Labels sichtbar (kein Placeholder-als-Label), Fehlermeldungen in Text

## Barrierefreiheit

- [ ] Kontrast Text/Hintergrund ≥ 4.5:1 (groß ≥ 3:1)
- [ ] Bilder mit aussagekräftigem `alt`, dekorative mit `alt=""`
- [ ] Tastatur-Navigation: Fokus sichtbar, Reihenfolge logisch
- [ ] Überschriften-Hierarchie ohne Sprünge (h1 → h2 → h3)
- [ ] `lang="de"` im html-Tag

## Responsiv

- [ ] 360px Breite: kein horizontales Scrollen, kein abgeschnittener Text
- [ ] Touch-Ziele ≥ 44x44px
- [ ] Text bleibt lesbar bei 200% Zoom (keine fixen Höhen)

## Performance & Hygiene

- [ ] Keine ungenutzten CSS-Regeln, keine Inline-Styles außer Testzwecken
- [ ] Bilder komprimiert und sinnvoll dimensioniert (`width`/`height` gesetzt gegen Layout-Shift)
- [ ] Titel + Meta-Description gesetzt, sinnvoll für Suchmaschine/Preview
