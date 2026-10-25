# Skill: Lektorat Deutsch (Line Editing)

Zweimal lesen: erst **Struktur** (Satz für Satz: braucht es diesen Satz?), dann **Sprache**.

## Struktur-Durchgang

- Satz muss eine Funktion haben: Handlung, Charakter, Atmosphäre, Information. Sonst streichen.
- Absätze: ein Gedanke pro Absatz, max. ~6 Sätze.
- Szenenwechsel ohne Übergangsmüll ("Später am Tag …" nur mit Funktion).

## Sprache-Durchgang — streichen/ersetzen

| Befund | Aktion |
|---|---|
| Füllwörter: eigentlich, irgendwie, gewissermaßen, sozusagen, einfach, wirklich | streichen |
| Adverbien auf -ly/-ig nach Sagverben ("sagte er wütend") | durch Handlung/Dialog ersetzen |
| Passiv ohne Grund ("wurde geöffnet") | aktivieren |
| Nominalstil ("zur Durchführung bringen") | verben ("durchführen") |
| doppelte Infos (Satz sagt, Prosa zuvor sagte es schon) | kürzen |
| Wortwiederholung im selben Absatz | Variante oder Umstellung |
| Modalpartikeln-Häufung (ja, doch, mal, denn) | auf 1 pro Satz senken |

## Grammatik-Fallstricke Deutsch

- Kommaregeln: Nebensätze mit Komma, erweiterter Infinitiv mit "zu" nur bei "um/ohne/anstatt/außer/als" oder mit Einleitungswort.
- "wie/als" bei Vergleichen: nach "als" Nominativ, wenn Vergleichsgröße Subjekt ist.
- Duden-konforme Schreibung bei New Media ("E-Mail", "gross" nur in CH).

## Output-Format

Tabelle pro Befund, dann den überarbeiteten Text komplett ausgeben:

```markdown
| Zeile/Befund | Vorher | Nachher | Grund |
|---|---|---|---|

<Überarbeiteter Text>
```

Niemals Sinn ändern, um einen Stilfehler zu fixen. Zweifelhafter Fall → Kommentar `<!-- LEKTORAT: … -->`.
