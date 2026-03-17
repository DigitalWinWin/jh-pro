# Setup-Anleitung — KI-Arbeitsumgebung

> Anleitung zur Einrichtung der KI-Arbeitsumgebung für Juliane Hoffmann.

---

## Voraussetzungen

- **Claude Desktop** mit Cowork-Funktion (aktives Abo erforderlich)
- **Dateisystem-Zugriff** in Claude Desktop aktiviert (MCP-Server "Dateisystem")
- **Dieser Ordner** heruntergeladen oder synchronisiert auf dem lokalen Rechner
- **macOS** (empfohlen) oder Windows

---

## Ordnerstruktur

```
04_KI-Arbeitsumgebung/
  CLAUDE.md                  ← Zentrale Konfiguration (Claude liest diese automatisch)
  README.md                  ← Kurzübersicht
  basisdokumente/            ← 38 Wissensdokumente über alle 6 Tätigkeitsbereiche
  skills/                    ← 13 Skills für wiederkehrende Aufgaben
  kunden/                    ← Kundenordner (Protokolle, Konzepte, Dokumente)
  vorlagen/                  ← Templates für Angebote, Protokolle, Berichte
  brand/                     ← Logos, Farben, Brand-Assets
  mcp-konfiguration/         ← MCP-Server Setup-Anleitungen
  docs/                      ← Dokumentation und Anleitungen (dieses Verzeichnis)
```

**Wichtig:** Die `CLAUDE.md` im Wurzelverzeichnis ist die zentrale Datei. Claude liest sie automatisch beim Öffnen des Ordners und kennt dann alle Basisdokumente, Skills, Preise und Regeln.

---

## MCP-Server einrichten

MCP-Server erweitern Claudes Fähigkeiten um externe Dienste (E-Mail, Aufgabenverwaltung etc.).

### Aktive MCP-Server (bereits eingerichtet)

Diese sind über Claude Desktop konfiguriert und erfordern keine weitere Einrichtung:

1. **Dateisystem** — Lokaler Zugriff auf diesen Ordner
2. **Canva** — Grafiken erstellen nach Brand Guide
3. **Chrome Control** — Webseiten analysieren, Research

### Geplante MCP-Server

Folgende Server werden in späteren Updates eingerichtet:

- **Mac Mail** — E-Mails lesen und Entwürfe erstellen (siehe `mcp-konfiguration/mac-mail-setup.md`)
- **Todoist** — Aufgabenverwaltung und Action Items (siehe `mcp-konfiguration/todoist-setup.md`)

Details zur Einrichtung findest du in den jeweiligen Dateien unter `mcp-konfiguration/`.

---

## Erste Schritte

### 1. Ordner in Claude Desktop öffnen

Öffne Claude Desktop und navigiere zu diesem Ordner (`04_KI-Arbeitsumgebung/`). Claude erkennt die `CLAUDE.md` automatisch und lädt die Konfiguration.

### 2. Testen, ob Claude die Basisdokumente kennt

Stelle eine Testfrage:

> "Welche Medikit-Pakete bietet Juliane an und was kosten sie?"

Claude sollte die drei Pakete (Starter, Profi, Elite) mit den korrekten Preisen nennen können.

### 3. Ersten Skill ausprobieren

Starte mit einem einfachen Anwendungsfall:

> "Erstelle mir ein Kundenbriefing für eine Zahnarztpraxis in Hamburg, die sich für Medikit interessiert."

Claude wird den Skill S07 (Kundenbriefing) nutzen und ein strukturiertes Briefing erstellen.

### 4. Kundenordner anlegen

Für jeden neuen Kunden:

> "Lege einen Kundenordner an für Praxis Dr. Müller in Hamburg (Bereich PB)."

Claude erstellt den Ordner unter `kunden/pb_praxis-mueller-hamburg/` mit Unterordnern.

---

## Häufige Fragen

**Muss ich die Basisdokumente aktualisieren?**
Ja, wenn sich Preise, Produkte oder Prozesse ändern. Die Basisdokumente sind Claudes Wissensquelle — veraltete Dokumente führen zu veralteten Antworten.

**Kann Claude E-Mails versenden?**
Noch nicht. Der Mac Mail MCP-Server ist geplant. Auch nach Einrichtung wird Claude nie ohne deine explizite Freigabe E-Mails versenden.

**Was passiert, wenn ich neue Skills brauche?**
Wende dich an Dominique (Digital WinWin). Neue Skills werden als `SKILL.md` erstellt und in den `skills/`-Ordner gelegt.

**Kann ich Claude auch ohne Internet nutzen?**
Nein, Claude benötigt eine Internetverbindung. Die Basisdokumente liegen lokal, aber Claude selbst läuft in der Cloud.

---

*Erstellt: Februar 2026 — Digital WinWin (Dominique Stalder)*
