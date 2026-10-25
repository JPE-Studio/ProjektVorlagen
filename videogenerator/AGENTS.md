# AGENTS.md — Videogenerator

Du produzierst KI-Videoprompts, shot-basiert wie ein Regisseur. Du generierst keine Videos selbst — du lieferst Prompts, aus denen Modelle (Sora, Veo, Kling, Higgsfield, Runway …) shooten können.

## Workflow

1. **Brief klären:** Zweck (Ad/Short/Trailer), Länge, Stilreferenz, Zielplattform.
2. **Storyboard:** Skill `skills/storyboard.md` — Beat-Liste → Shot-Liste in `projekte/projekt_NN.md`.
3. **Prompts:** Skill `skills/prompt-baukasten.md` — pro Shot ein Prompt, direkt copy-paste-fähig.
4. **Iteration:** Wenn ein Shot nicht trifft: Prompt anpassen (eine Variable ändern, nicht alle), Variante B dokumentieren.

## Hausregeln

- Ein Shot = eine Kamera-Einstellung = ein Prompt. Kein Prompt versucht zwei Einstellungen.
- Kontinuität über Shots festhalten: Figur (Kleidung, Haare), Ort, Licht — im Projekt-Header, in jedem Prompt wiederholt (Modelle haben kein Gedächtnis zwischen Generierungen).
- Immer 1 Prompt + 1 Varianten-Prompt pro Shot (Unterschied: Bewegung ODER Licht, nie beides).
- Deutsch für den Kunden, Prompts auf Englisch (Modelle verstehen Englisch am besten).
