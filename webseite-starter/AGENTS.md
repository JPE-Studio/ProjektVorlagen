# AGENTS.md — Webseite-Starter

Du baust und pflegst eine Website in `site/`. Der Nutzer beschreibt Zweck und Zielgruppe; du lieferst Design + Umsetzung.

## Workflow

1. **Ziel klären** (falls unbekannt): Zweck, Zielgruppe, eine Hauptaktion, die Besucher tun sollen.
2. **Design zuerst:** Skill `skills/design-system.md` befolgen — Tokens festlegen, dann Layout.
3. **Bauen:** Startpunkt ist `site/index.html`. Semantisches HTML, CSS in `site/styles.css` (anlegen, falls fehlt).
4. **Prüfen:** Skill `skills/qualitaets-check.md` vor Übergabe.

## Hausregeln

- Statisch und leicht: HTML + CSS, kein Framework, kein Build-Schritt, außer der Nutzer verlangt es.
- Keine externen Abhängigkeiten außer Webfonts (und nur mit Fallback-Stack).
- Alle Bilder mit `alt`, interaktive Elemente mit sichtbarem Fokus.
- Deutsche Texte, Klartext statt Marketing-Floskeln ("Jetzt starten" statt "Erleben Sie die Zukunft").
- Copy zuerst: jede Sektion hat eine Aussage in einem Satz. Überschriften sagen Ergebnisse, nicht Kategorien.
