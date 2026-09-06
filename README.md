# Zweites Gehirn

Ein Langzeitgedächtnis für Claude, das in einer Sitzung steht und danach mit dir wächst. Kein Server, kein Abo, keine Datenbank: ein Ordner mit Markdown-Dateien, den du in Obsidian liest und den Claude Code pflegt.

## Was es ist

Claude vergisst nach jeder Sitzung alles. Dieses Repository gibt ihm einen Ort, an dem Wissen bleibt: Quellen in `raw/`, gepflegte Wissensseiten in `wiki/`, ein Katalog in `index.md`, ein Logbuch in `log.md`. Die `CLAUDE.md` sagt Claude, wie er damit umgeht: drei Operationen (aufnehmen, fragen, prüfen) und ein paar harte Wissensregeln, damit der Ordner mit der Zeit besser wird statt unordentlicher.

Es ist kein Werkzeug zum Kaufen. Es ist die Struktur, die ich selbst benutze, auf das Nötigste reduziert.

## Aufsetzen in einer Sitzung

1. Repository klonen oder als ZIP laden, Ordner in Obsidian öffnen (optional, zum Lesen).
2. Claude Code im Ordner starten.
3. Den Block aus `prompts/start-prompt.md` einfügen. Claude fragt dich fünf Dinge, füllt die `CLAUDE.md` aus, legt die ersten Wiki-Seiten an und nimmt die erste Quelle mit dir auf.
4. Fertig. Ab jetzt liest Claude den Vault zu Beginn jeder Sitzung.

Prüfung: Neue Sitzung öffnen und fragen „Woran arbeite ich gerade?". Kommt die Antwort aus dem Vault, läuft es.

## Was danach läuft

- **Im Alltag:** Du sagst „nimm das auf" (Ingest), stellst Fragen (Query) oder lässt prüfen (Lint). Claude hält Katalog und Logbuch selbst in Ordnung.
- **Einmal die Woche, ohne dich:** `prompts/routinen-prompt.md`. Lokal per Kommandozeile oder als Cloud-Routine über einen GitHub-Branch, dann braucht es nicht einmal einen laufenden Rechner.
- **Wenn es wächst:** Die Skill-Bibliothek (separates Paket) ergänzt Routinen wie Tagesplanung, Zusammenfassen, Übergabe bei vollem Kontext.

## Die vier Elemente

| | |
|---|---|
| `raw/` | Originalquellen, unverändert. Jahr als Unterordner. |
| `wiki/` | Eine Seite je Thema, Frontmatter, Zusammenfassung oben, Quellen unten, Wikilinks. |
| `index.md` | Alle Wiki-Seiten mit einem Satz. Wird zuerst gelesen. |
| `log.md` | Was wann passiert ist, neueste Zeile oben. |

Dazu `prompts/` mit dem Start- und dem Routinen-Prompt.

## Worauf es beruht

Die Grundstruktur (raw, wiki, index, log) und die drei Operationen Ingest, Query, Lint stammen von **Sebastian Kauffmann** (SKAILE Academy, Modul Agentic OS), ebenso die Idee, Cloud-Routinen über einen GitHub-Branch in den Vault schreiben zu lassen. Beides ist hier mit Nennung übernommen und um die Wissensregeln ergänzt, die sich in meinem eigenen System über ein Jahr bewährt haben: eine Quelle je Information, alter Stand wird markiert statt gelöscht, fünf Fragen vor dem Speichern, nichts nach außen ohne Nachfrage.

## Lizenz

MIT. Nimm es, bau es um, behalte den Hinweis auf die Herkunft.
