# Mac Mail MCP-Server — Setup-Anleitung

> Status: **Geplant** — Dieser MCP-Server wird in einem späteren Update eingerichtet.

---

## Was kann der Mac Mail MCP-Server?

Der Mac Mail MCP-Server verbindet Claude mit der Apple Mail App auf dem Mac. Damit kann Claude:

- **E-Mails lesen** — Eingehende Nachrichten anzeigen und zusammenfassen
- **E-Mails durchsuchen** — Nach Absender, Betreff oder Inhalt filtern
- **Entwürfe erstellen** — Antworten und neue E-Mails als Entwurf vorbereiten
- **Anhänge erkennen** — Anhänge in E-Mails identifizieren

### Was der MCP-Server NICHT kann (by Design)

- **NICHT automatisch senden** — Jede E-Mail muss von dir freigegeben werden
- **NICHT löschen** — Claude kann keine E-Mails entfernen
- **NICHT auf andere Konten zugreifen** — Nur das konfigurierte Konto

---

## Human-in-the-Loop: Deine Kontrolle

Dieses Prinzip ist zentral und nicht verhandelbar:

1. Claude erstellt einen **E-Mail-Entwurf**
2. Der Entwurf erscheint in deinem **Entwürfe-Ordner** in Apple Mail
3. Du **prüfst** den Entwurf
4. Du **sendest** die E-Mail manuell

Claude wird **NIEMALS** eine E-Mail ohne deine explizite Freigabe versenden. Das ist in der CLAUDE.md als feste Regel verankert.

---

## Geplante Einrichtung

### Voraussetzungen

- macOS mit Apple Mail konfiguriert
- Claude Desktop installiert
- E-Mail-Konto in Apple Mail eingerichtet (IMAP empfohlen)

### Einrichtungsschritte (wird ergänzt)

1. MCP-Server in Claude Desktop aktivieren
2. Zugriff auf Apple Mail erlauben (macOS Berechtigungen)
3. Konto auswählen
4. Testlauf: "Zeige mir meine letzten 5 E-Mails"

---

## Anwendungsbeispiele (nach Einrichtung)

### Morgen-Routine
> "Zeige mir die wichtigsten E-Mails von heute. Priorisiere Kundenanfragen."

### Nach einem Gespräch
> "Schreibe eine Zusammenfassungs-E-Mail an Praxis Göttingen mit den Ergebnissen aus dem heutigen Protokoll."

### Follow-up
> "Prüfe, ob Praxis Dr. Müller auf mein Angebot vom 10. Februar geantwortet hat. Falls nicht, erstelle eine Follow-up-E-Mail."

---

## Sicherheitshinweise

- Der MCP-Server hat nur Lesezugriff und Entwurf-Erstellung — kein Senden
- Claude sieht nur E-Mails des konfigurierten Kontos
- Sensible E-Mails (Bankdaten, Passwörter) sollten manuell behandelt werden
- Bei Zweifeln: E-Mail-Kontext immer manuell prüfen

---

> **Hinweis:** Dieser MCP-Server wird in einem späteren Update eingerichtet.
> Bei Fragen zur Einrichtung: Dominique kontaktieren (Digital WinWin).

---

*Erstellt: Februar 2026 — Digital WinWin (Dominique Stalder)*
