# Skill: Prompt-Baukasten (Video)

Ein Video-Prompt ist ein Drehbuch für eine Kamera-Einstellung. Baukasten in fester Reihenfolge — leere Slots weglassen, nicht mit Floskeln füllen.

## Prompt-Struktur (Englisch)

```
[SHOT] — [SUBJECT] — [ACTION] — [SETTING] — [LIGHT] — [CAMERA] — [STYLE] — [AUDIO] — [NEGATIVE]
```

| Slot | Inhalt | Beispiel |
|---|---|---|
| SHOT | Größe + Winkel | "medium close-up, eye level" |
| SUBJECT | Wer/Was, mit 2–3 festen Merkmalen | "a 60-year-old fisherman, grey beard, yellow raincoat" |
| ACTION | EINE Bewegung, konkret + zeitlich | "hauls a net over the railing, water dripping" |
| SETTING | Ort + Wetter + Tageszeit | "small harbor at dawn, light fog" |
| LIGHT | Lichtquelle + Stimmung | "soft golden backlight, long shadows" |
| CAMERA | Bewegung + Geschwindigkeit | "slow dolly-in, handheld sway" |
| STYLE | Filmreferenz/Filmstock/Ära | "shot on 16mm, documentary style, muted colors" |
| AUDIO | Ambience/Dialog/Musik (falls Modell Audio unterstützt) | "seagulls, distant engine hum, no music" |
| NEGATIVE | Was das Modell lassen soll | "no text, no camera shake, no cuts" |

## Regeln

- **Kontinuität steckt in SUBJECT+LIGHT:** Diese Slots werden Wort für Wort aus dem Projekt-Header übernommen, nichts umschreiben.
- Eine Änderung pro Iteration: trifft der Shot nicht, nur einen Slot ändern und neu generieren.
- Statisch schlägt kitschig: ruhige Kamera + klare Action gewinnt gegen "epic dramatic cinematic 8k".
- Zahlen statt Adjektive: "3 seconds of silence" statt "brief moment".
- Keine abstrakten Emotionen im Prompt ("feels lonely") — zeigbar machen ("sits alone at a table for two, untouched coffee").

## Beispiel (fertiger Prompt)

> Medium close-up, eye level. A 60-year-old fisherman, grey beard, yellow raincoat, hauls a net over the railing, water dripping. Small harbor at dawn, light fog. Soft golden backlight, long shadows. Slow dolly-in, handheld sway. Shot on 16mm, documentary style, muted colors. Seagulls, distant engine hum. No text, no cuts.
