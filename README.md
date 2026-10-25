# ProjektVorlagen

Ein Repo, das nur aus **Templates** besteht: fertige Ordnerstrukturen mit eingebauten Skills für Agenten (Claude Code, Codex, pi — egal welcher).

## Prinzip: Der Ordner ist der Vertrag

- `AGENTS.md` — kanonische Regeln, liest jeder Agent nativ (Codex, pi, und via Zeiger auch Claude Code)
- `CLAUDE.md` — 2-Zeilen-Zeiger auf `AGENTS.md` (Claude Code)
- `skills/` — flache Markdown-Dateien. `AGENTS.md` sagt dem Agent, wann er welche liest.
- Domain-Ordner — die eigentliche Arbeit entsteht hier und bleibt versionierbar (Story Bible, Kapitel, Fälle, Prompts)

Kein Tool-Lock-in: kopiere einen Template-Ordner in dein Projekt und öffne ihn mit jedem Agent.

## Nutzung

```bash
cp -r buchautor/ ~/Documents/mein-roman/
cd ~/Documents/mein-roman
# dann: claude / codex / pi starten und loslegen
```

## Templates

| Template | Zweck | Skills |
|---|---|---|
| `buchautor/` | Roman schreiben, szenenweise | Szenen-Generator (Beat-basiert), Lektorat Deutsch |
| `webseite-starter/` | Eine-Pager/Website mit Designsystem | Design-System, Qualitäts-Check |
| `videogenerator/` | KI-Videoproduktion (Shot-basiert) | Prompt-Baukasten, Storyboard |
| `steuerberater/` | Steuer-/Behördenfälle bearbeiten | Zuständigkeits-Zuweisung, Behörden-Wegweiser |

## Neues Template beitragen

1. Ordner anlegen mit `AGENTS.md`, `CLAUDE.md`, `skills/`
2. `AGENTS.md` muss die Skills zuweisen (wann liest der Agent welche Datei)
3. Mindestens einen Starter-Content-Ordner (da entsteht die Arbeit)
4. In die Tabelle oben eintragen

Regel für Skills: eine Datei = ein Skill, max. ~60 Zeilen, mit Beispielen statt Prosa.

## Lizenz

MIT — siehe [LICENSE](LICENSE).
