---
skill_name: "jh-massnahmenplan"
skill_id: "S03"
version: "v0.1"
status: "platzhalter"
bereich: "PB, PF"
erstellt: "2026-02-17"
erstellt-durch: "Digital WinWin"
---

# S03 — Massnahmenpläne aus Beratungen ableiten

## Beschreibung

Dieser Skill erstellt priorisierte Massnahmenpläne aus Beratungsprotokollen oder VFD-Ergebnissen. Er identifiziert konkrete Handlungsschritte, ordnet Verantwortlichkeiten zu, setzt realistische Deadlines und markiert Quick Wins. Einsetzbar in der Praxisberatung (PB) und bei PraxisFactory (PF).

## Input

- Beratungsprotokoll oder Meeting-Protokoll
- VFD-Ergebnis (bei PF-Mandaten)
- Optional: Bestehender Maßnahmenplan zur Aktualisierung
- Optional: Priorisierungsvorgaben von Juliane

## Output

- Priorisierter Maßnahmenplan mit:
  - Maßnahmen-ID und Beschreibung
  - Verantwortliche Person(en)
  - Deadline / Zeithorizont
  - Priorität (Hoch / Mittel / Niedrig)
  - Quick Wins (sofort umsetzbar, markiert)
  - Status-Tracking (Offen / In Arbeit / Erledigt)

## Referenzen

- `basisdokumente/tf01_praxisberatung/SOP-Beratungsprozess-PB-V2.md`

## Workflow

1. Beratungsprotokoll oder VFD-Ergebnis analysieren
2. Konkrete Maßnahmen extrahieren und formulieren
3. Abhängigkeiten zwischen Maßnahmen identifizieren
4. Quick Wins erkennen und markieren
5. Verantwortlichkeiten und Deadlines zuordnen
6. Maßnahmen nach Priorität sortieren
7. Plan in übersichtlicher Tabellenform formatieren
8. Juliane zur Abstimmung vorlegen

## Hinweise

- Quick Wins immer an den Anfang stellen — sie motivieren das Praxisteam
- Maßnahmen müssen SMART formuliert sein (Spezifisch, Messbar, Attraktiv, Realistisch, Terminiert)
- Bei PF-Mandaten: VFD-Termine als natürliche Meilensteine nutzen
- Beratungsprozess-SOP als Leitfaden für die korrekte Reihenfolge verwenden
- Sprache: klar und handlungsorientiert
