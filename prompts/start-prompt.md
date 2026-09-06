# Start-Prompt: das Gedächtnis in einer Sitzung einrichten

Kopiere den Block unten in eine neue Claude-Code-Sitzung, geöffnet im Ordner dieses Vaults. Claude führt dich durch ein kurzes Interview, füllt die `CLAUDE.md` aus und legt die erste Wiki-Seite an. Dauer: etwa 20 Minuten.

---

Du richtest mein Zweites Gehirn ein. Lies zuerst `CLAUDE.md` und `README.md` in diesem Ordner, dann führe mich durch ein Interview.

Regeln für das Interview:
- Eine Frage auf einmal. Warte auf meine Antwort, bevor die nächste kommt.
- Zu jeder Frage schlägst du eine Antwort vor, die ich übernehmen oder ändern kann.
- Was du aus den Dateien im Ordner schon weißt, fragst du nicht noch einmal.

Die Fragen, in dieser Reihenfolge:
1. Wer bin ich und was mache ich? (Zwei bis drei Sätze, die du später jeder Sitzung mitgibst.)
2. Mit welchen Themen und Projekten arbeite ich gerade? (Das werden die ersten Wiki-Seiten.)
3. Wofür brauche ich das Gedächtnis zuerst: Wissen sammeln, Projekte im Blick behalten, Entscheidungen festhalten, etwas anderes?
4. Wie soll Claude mit mir sprechen? (Du oder Sie, Sprache, Tonfall, was nervt.)
5. Was ist tabu? (Was nie gespeichert oder nie nach außen gegeben werden darf.)

Danach:
- Ersetze in `CLAUDE.md` jedes `{{NAME}}` durch meinen Namen und fülle den Block „Was {{NAME}} beim Einrichten festgelegt hat" mit meinen Antworten.
- Lege für jedes Thema aus Frage 2 eine leere Wiki-Seite mit Frontmatter und einer Zeile Zusammenfassung an, trage sie in `index.md` ein.
- Lege `wiki/offen.md` an mit dem, was im Interview offen geblieben ist.
- Schreibe die erste Zeile in `log.md`: heutiges Datum, „Einrichtung", ein Satz.
- Zum Schluss: Zeig mir in fünf Zeilen, was jetzt da ist, und frag mich nach der ersten Quelle, die ich aufnehmen will. Dann führe einen Ingest damit durch, genau nach `CLAUDE.md`.

Prüfung am Ende: Öffne eine gedachte neue Sitzung und beantworte die Frage „Woran arbeite ich gerade?" nur aus dem Vault. Wenn die Antwort dünn ist, sag mir, was fehlt.
