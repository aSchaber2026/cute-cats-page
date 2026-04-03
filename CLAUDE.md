# Keller GbR & GmbH — Projektanweisungen

## Kontext

Dieses Projekt dokumentiert zwei zusammenhängende Themen der Familie Keller:

### GbR (Keller / Regh GbR)
Die GbR verwaltet ein Hallengebäude (Kiemstr. 10, 54311 Trierweiler). Gesellschafter sind Horst Keller (Vater, 86 Jahre, gesundheitlich eingeschränkt, im Krankenhaus) und seine Tochter Mary-Lou Regh. Beide sind zerstritten. Christiane Keller (geb. Poss), Horst Kellers Ehefrau, kommuniziert für die GmbH-Seite per E-Mail (info@horst-keller-gmbh.de).

### GmbH (Horst Keller Gebäudereinigung GmbH)
Horst Keller ist alleiniger Gesellschafter und alleiniger Geschäftsführer. Christiane führt den Betrieb faktisch seit ca. 2 Jahren (nur Vollmacht, kein offizieller Titel). Mary-Lou hat früher in der GmbH gearbeitet, hat den Betrieb heruntergewirtschaftet (Buchhaltung ab ~2017) und ist Dezember 2023 fluchtartig ausgeschieden. Christiane baut systematisch wieder auf.

### Beteiligte Personen
- **Horst Keller** — Vater, Gesellschafter beider Entitäten, 86 Jahre, im Krankenhaus
- **Mary-Lou Regh** (geb. Keller) — Tochter, GbR-Gesellschafterin, ml.regh@yahoo.com
- **Christiane Keller** (geb. Poss) — Ehefrau von Horst, führt GmbH faktisch, info@horst-keller-gmbh.de
- **RA Zimmermann** — Anwältin der Horst Keller GmbH
- **KNP / Kadau** — Ehemaliger Steuerberater (GbR + GmbH)
- **Oliver Meyer** — Neuer Steuerberater (GmbH-seitig)

## Vorgehensweise

Dieses Projekt folgt dem gleichen bewährten Ansatz wie "Airbnb Vorfall":

### 1. Zuhören und Verstehen
- Andreas erzählt die Geschichte in seinem eigenen Tempo
- Keine Unterbrechungen, Rückfragen erst wenn er fertig ist oder darum bittet
- Alle Details aufnehmen — Personen, Daten, Abläufe, Gefühlslage

### 2. Strukturiert festhalten
- GbR-Tagebuch: `tagebuch.md` + `tagebuch.html` — chronologisch, alle E-Mails
- GmbH-Dokumentation: `gmbh.html` — Pensionsrückstellung, Strategie, Bundesanzeiger-Analyse
- Alles anwaltstauglich, wörtliche Zitate, verifiziert aus Original-EML-Dateien

### 3. Gemeinsam reflektieren
- Ehrliche Einschätzung — was ist stark, was ist riskant
- Bei Schriftverkehr: sachlich, professionell, deeskalierend

### 4. Unterstützung bei Kommunikation
- E-Mails per AppleScript als Entwurf in Apple Mail erstellen (NICHT per .eml!)
- Ton: sachlich aber menschlich, keine Eskalation
- Andreas entscheidet immer über Inhalt und Versand

## Über Andreas

- Gefühlsmensch, nimmt Dinge persönlich
- Bevorzugt Vertrauen über Formalitäten
- Kommunikation: direkt, ehrlich, locker
- Sprache: Deutsch, geduzt wird bevorzugt
- E-Mail: andreas@schaber.email
- Hat eine Rechtsschutzversicherung

## Dateistruktur

- `CLAUDE.md` — Projektanweisungen
- `CHANGELOG.md` — Änderungsprotokoll
- `tagebuch.md` — GbR: Chronologische E-Mail-Dokumentation (Markdown)
- `tagebuch.html` — GbR: Vollständige HTML-Dokumentation (88 E-Mails, anwaltstauglich)
- `gmbh.html` — GmbH: Pensionsrückstellung, GF-Thematik, Asset Deal, Bundesanzeiger-Analyse
- `index.html` — Katzen-Landing-Page mit verstecktem Login (Pfote der schwarzen Katze)
- `portal.html` — Auswahl-Portal: GbR-Tagebuch / GmbH-Dokumentation
- `mail_christiane.md` — E-Mail-Entwurf (versendet)
- `mail_christiane.eml` — E-Mail-Datei (versendet)
- `_Temp/` — Eingangskorb für neue Dateien + Bundesanzeiger-PDFs 2006–2019
- `.gitignore` — Schließt _Temp/, *.png, *.eml, .playwright-mcp/ aus

## Online-Zugang (GitHub Pages)

- **URL:** https://aschaber2026.github.io/cute-cats-page/
- **Repo:** aSchaber2026/cute-cats-page (öffentlich)
- **Passwort:** IbjFk2099** (Zugang über Klick auf rechte Pfote der schwarzen Katze)
- **Zugang:** Christiane Keller kennt Link + Passwort (E-Mail am 03.04.2026 versendet)
- **Update-Workflow:** Dateien ändern → `git add . && git commit -m "Update" && git push` → GitHub Pages aktualisiert automatisch (1-2 Min)

## Temp-Ordner Workflow

Der Ordner `_Temp/` dient als Eingangskorb:
1. Andreas legt Dateien dort ab (Fotos, PDFs, Screenshots, E-Mails etc.)
2. Zu Beginn jeder Session prüfe ich den Temp-Ordner
3. Dateien werden gesichtet, verarbeitet und in die richtige Ordnerstruktur verschoben
4. Relevante Infos werden ins Tagebuch übernommen
5. _Temp/ ist per .gitignore vom Repo ausgeschlossen (sensible Daten!)

## Architektur-Entscheidungen

- HTML-Dateien sind eigenständig (keine externen CSS/JS-Abhängigkeiten) → funktioniert offline + auf GitHub Pages
- E-Mails per AppleScript als outgoing message erstellen (nicht per .eml — die lassen sich nicht versenden)
- Passwortschutz via clientseitigem Hash (kein echter Schutz, aber ausreichend für Verschleierung)
- Katzen-Landing als Tarnung: Seite sieht harmlos aus, Login versteckt in Pfote
- Repo öffentlich (GitHub Pages Free erfordert das), daher .gitignore für sensible Dateien
- Print-Stylesheet in allen HTMLs integriert (Strg+P → PDF für Anwalt)
- GbR und GmbH in einem Repo, aber über Portal getrennt

## Aktueller Stand des Falls

### GbR — Keller / Regh
- **Vollstreckung FA Trier:** Erledigt — 818,31 € eingegangen, Konto bereinigt (bestätigt 02.04.2026)
- **SEPA-Lastschriftmandat:** Am 26.03. empfangen, am 28.03. per Post zurückgesendet, Regh müsste es haben
- **Mail Regh 01.04.2026:** Persönlich beleidigend gegen Christiane (Nachnamen, Trauerfeier, "Arroganz") → Empfehlung: Nicht antworten
- **Mail Regh 03.04.2026:** Fordert SEPA-Lastschrift erneut mit Frist 07.04. → Antwortentwurf erstellt (sachlich: wurde am 28.03. versendet)
- **Gas-Bestellung:** Regh betrachtet Bestellung als "hinfällig", Christiane hat auf Mieterversorgungspflicht hingewiesen

### GmbH — Horst Keller Gebäudereinigung
- **Geschäftszahlen 2025:** 489k Einnahmen, 67k Gewinn
- **Betriebsrente Horst:** 1.303 €/Monat seit 2003, Horst ist 86
- **Pensionsrückstellung:** War gebucht (182.246 € per 2010), Witwenrente = 2/3 davon → Christiane kann darauf verzichten
- **Bundesanzeiger 2006–2019:** Alle 14 Jahresabschlüsse analysiert, ab 2020 fehlen Veröffentlichungen (Pflichtverstoß)
- **Crash 2019:** Bilanzsumme halbiert, 363k Forderung gg. Gesellschafter verschwunden, 302k Gewinnvortrag weg — fällt in Mary-Lous Buchhaltungszeit
- **Strategische Optionen:** GF-Eintragung, Asset Deal, Rechtsform-Empfehlung GmbH dokumentiert

## Offene Aufgaben / TODOs (Stand: 2026-04-03)

- [ ] **Kapitel-Navigation in tagebuch.html und gmbh.html einbauen** (Inhaltsverzeichnis mit Sprungmarken, bei Print trotzdem alles anzeigen)
- [ ] Antwort auf Reghs Mail vom 03.04. (Lastschrift) versenden — Entwurf liegt im Tagebuch
- [ ] Prüfen ob SEPA-Lastschriftmandat bei Regh angekommen ist
- [ ] Aufklärung Vermögensabfluss 2018/2019: Wohin sind ~363.000 € geflossen?
- [ ] PSVaG-Mitgliedschaft prüfen (direkt beim PSVaG anfragen)
- [ ] Fehlende Jahresabschlüsse 2020–2025 beim Bundesanzeiger nachreichen
- [ ] Rolle von Mary-Lou in der Buchhaltung 2017–2023 prüfen lassen
- [ ] Schadensersatz gegen KNP prüfen (Fachanwalt)
- [ ] GF-Eintragung Christiane mit Notar/Steuerberater besprechen
- [ ] Gas-Bestellung: Monitoring ob Regh bestellt oder nicht

### Nächste Session — Hier weitermachen
1. **Kapitel-Navigation** in tagebuch.html und gmbh.html einbauen (Inhaltsverzeichnis, Sprungmarken, Print-kompatibel)
2. Antwort-Mail an Regh (Lastschrift) versenden lassen
3. Prüfen ob neue E-Mails von Regh im _Temp-Ordner liegen
4. GmbH: Strategische Entscheidung (alte GmbH behalten vs. neue gründen) mit Christiane besprechen

## Wichtig

- Ich bin eine KI und kein Ersatz für rechtliche oder psychologische Beratung
- Bei rechtlichen Fragen immer empfehlen: Fachanwalt konsultieren
- Telefonseelsorge bei Bedarf: 0800 111 0 111 (kostenlos, 24/7)
