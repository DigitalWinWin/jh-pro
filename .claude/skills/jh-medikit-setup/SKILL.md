---
skill_name: "jh-medikit-setup"
skill_id: "S08"
version: "v0.1"
status: "platzhalter"
bereich: "PB"
erstellt: "2026-02-17"
erstellt-durch: "Digital WinWin"
---

# S08 — Medikit-Struktur für neue Kunden aufsetzen

## Beschreibung

Dieser Skill erstellt die initiale Medikit-Struktur für neue Praxiskunden. Basierend auf Praxisgröße, Teamstruktur und gebuchtem Paket (Starter/Profi/Elite) wird ein Organigramm-Vorlage, eine Ordnerstruktur und eine Implementierungs-Checkliste generiert. Dies bildet das Fundament für die weitere Praxisberatung.

## Input

- Praxisgröße (Anzahl Mitarbeiter, Behandlungsräume)
- Teamstruktur (Rollen: Zahnärzte, ZFA, Empfang, Prophylaxe etc.)
- Gebuchtes Paket (Starter / Profi / Elite)
- Optional: Bestehende Organisationsstruktur

## Output

- Organigramm-Vorlage (angepasst an Praxisgröße)
- Ordnerstruktur (digitale Ablage für die Praxis)
- Implementierungs-Checkliste mit:
  - Setup-Schritte (chronologisch)
  - Verantwortlichkeiten
  - Zeitschätzung pro Schritt
  - Abhängigkeiten

## Referenzen

- `basisdokumente/tf01_praxisberatung/Best-Practices-Medikit-PB-V2.md`

## Workflow

1. Praxisdaten erfassen (Größe, Team, Paket)
2. Best Practices laden und passendes Template wählen
3. Organigramm an Teamstruktur anpassen
4. Ordnerstruktur gemäß Paket-Umfang erstellen
5. Implementierungs-Checkliste generieren
6. Juliane zur Abstimmung vorlegen
7. Nach Freigabe: Setup-Unterlagen an Praxis übergeben

## Hinweise

- Starter-Paket: Basis-Organigramm, reduzierte Ordnerstruktur
- Profi-Paket: Erweitertes Organigramm, vollständige Ordnerstruktur
- Elite-Paket: Individuelles Organigramm, erweiterte Struktur mit Zusatzmodulen
- Ordnerstruktur muss zur bestehenden Praxis-Software passen
- Checkliste in "Häppchen" aufteilen — kleine Schritte für das Praxisteam
- Naming-Konventionen aus Best Practices übernehmen
