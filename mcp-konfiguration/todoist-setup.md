# Todoist MCP-Server — Setup-Anleitung

> Status: **Geplant** — Dieser MCP-Server wird in einem späteren Update eingerichtet.

---

## Was kann der Todoist MCP-Server?

Der Todoist MCP-Server verbindet Claude mit deiner Todoist-Aufgabenverwaltung. Damit kann Claude:

- **Aufgaben lesen** — Aktuelle To-Dos anzeigen und zusammenfassen
- **Aufgaben erstellen** — Neue Aufgaben mit Fälligkeitsdatum und Priorität anlegen
- **Aufgaben abschließen** — Erledigte Aufgaben als fertig markieren
- **Projekte verwalten** — Aufgaben in Projekte einsortieren
- **Aufgaben durchsuchen** — Nach Stichwort, Datum oder Projekt filtern

---

## Integration mit dem Beratungsprozess

### Action Items aus Protokollen → Todoist

Der wichtigste Anwendungsfall: Nach jedem Kundengespräch erstellt Claude ein Protokoll mit Action Items. Diese sollen direkt in Todoist landen.

**Ablauf:**
1. Gespräch führen → Transkript
2. Claude erstellt Protokoll mit Action Items → [S01]
3. Claude überträgt Action Items in Todoist (nach Freigabe)
4. Jedes Action Item wird eine Aufgabe mit:
   - Beschreibung
   - Fälligkeitsdatum
   - Priorität
   - Zuordnung zum Kundenprojekt

### Beispiel-Workflow

> "Erstelle aus dem heutigen Protokoll für Praxis Göttingen Todoist-Aufgaben für alle offenen Action Items."

Claude erstellt dann z.B.:
- "Organigramm-Entwurf an Praxis Göttingen senden" — Fällig: 21.02.2026, Priorität: Hoch
- "Medikit-Zugänge für 3 Mitarbeiter einrichten" — Fällig: 28.02.2026, Priorität: Mittel
- "Nächsten Termin koordinieren (KW 10)" — Fällig: 24.02.2026, Priorität: Hoch

### Empfohlene Todoist-Projektstruktur

```
Todoist/
  Praxisberatung (PB)/
    Praxis Goettingen/
    Praxis Mueller/
    ...
  Praxis Factory (PF)/
    VFD Schneider/
    VFD Berger/
    ...
  Dr. Flex (DF)/
    ZEN Praxis Sonnenschein/
    Support-Videos/
    ...
  Allgemein/
    Marketing/
    Admin/
    ...
```

---

## Geplante Einrichtung

### Voraussetzungen

- Todoist-Konto (Premium empfohlen für volle API-Funktionalität)
- Claude Desktop installiert
- Todoist API-Token (unter Einstellungen → Integrationen → API-Token)

### Einrichtungsschritte (wird ergänzt)

1. Todoist API-Token generieren
2. MCP-Server in Claude Desktop konfigurieren
3. Projekte gemäß Struktur oben anlegen
4. Testlauf: "Zeige mir meine heutigen Todoist-Aufgaben"

---

## Anwendungsbeispiele (nach Einrichtung)

### Morgen-Routine
> "Was steht heute auf meiner Todoist-Liste? Sortiere nach Priorität."

### Nach einem Gespräch
> "Erstelle Todoist-Aufgaben aus den Action Items des Protokolls für Praxis Göttingen."

### Wochenplanung
> "Zeige mir alle Aufgaben für diese Woche. Gibt es Konflikte oder Überschneidungen?"

### Cross-Selling-Reminder
> "Erstelle eine Aufgabe: 'Cross-Selling-Gespräch mit Praxis Schneider führen (VFD abgeschlossen, Medikit-Potenzial)' — Fällig nächsten Montag."

---

## Sicherheitshinweise

- Claude erstellt Aufgaben erst nach deiner Freigabe
- Bestehende Aufgaben werden nicht ohne Rückfrage geändert oder gelöscht
- Sensible Aufgaben (z.B. mit Kundendetails) bleiben in Todoist — Claude speichert sie nicht separat

---

> **Hinweis:** Dieser MCP-Server wird in einem späteren Update eingerichtet.
> Bei Fragen zur Einrichtung: Dominique kontaktieren (Digital WinWin).

---

*Erstellt: Februar 2026 — Digital WinWin (Dominique Stalder)*
