---
skill_name: "jh-angebotserstellung"
skill_id: "S06"
version: "v0.1"
status: "platzhalter"
bereich: "PB"
erstellt: "2026-02-17"
erstellt-durch: "Digital WinWin"
---

# S06 — Angebote für Medikit-Pakete erstellen

## Beschreibung

Dieser Skill erstellt Angebotsentwürfe für Julianes Medikit-Pakete (Starter, Profi, Elite) im Rahmen der Praxisberatung. Er generiert eine vollständige Leistungsbeschreibung mit Preisen und Zahlungsbedingungen. Die finale Angebotserstellung erfolgt durch Juliane in Lexware.

## Input

- Kundenname und Praxisbezeichnung
- Paket (Starter / Profi / Elite)
- Besonderheiten oder individuelle Anpassungen
- Optional: Ergebnis aus Erstgespräch oder Kundenbriefing

## Output

- Angebotsentwurf mit:
  - Empfänger-Daten
  - Leistungsbeschreibung (paketspezifisch)
  - Preis (netto)
  - Zahlungsbedingungen
  - Gueltigkeitsdauer
  - Optional: Individuelle Zusatzleistungen

## Referenzen

- `basisdokumente/tf01_praxisberatung/Produktdefinition-PB-V2.md`

## Workflow

1. Kundeninformationen und gewünschtes Paket erfassen
2. Produktdefinition für das Paket laden
3. Leistungsbeschreibung individualisieren
4. Preis und Zahlungsbedingungen einfügen
5. Angebotsentwurf formatieren
6. Juliane zur Prüfung vorlegen
7. Juliane erstellt finales Angebot in Lexware

## Hinweise

- Preise (netto): Starter 8.500 EUR, Profi 10.500 EUR, Elite 17.000-18.500 EUR
- Preise NICHT eigenständig ändern — bei Sonderwünschen Juliane fragen
- Tool: Lexware ist das führende System — der Skill liefert nur den Entwurf
- Sie-Anrede im gesamten Angebot
- Zahlungsbedingungen: Standardmäßig 14 Tage netto, bei Ratenzahlung gesondert angeben
- Angebote haben eine Standardgültigkeit von 30 Tagen
