---
skill_name: "jh-kundenbriefing"
skill_id: "S07"
version: "v0.1"
status: "platzhalter"
bereich: "PB, PF"
erstellt: "2026-02-17"
erstellt-durch: "Digital WinWin"
---

# S07 — Kundenbriefings vor Erstgespräch erstellen

## Beschreibung

Dieser Skill erstellt kompakte Kundenbriefings (1-Seiter) zur Vorbereitung auf Erstgespräche mit potenziellen Praxiskunden. Er recherchiert anhand der Website und verfügbarer Informationen ein Praxis-Profil, identifiziert potenzielle Schmerzpunkte und schlägt passende Gesprächspunkte sowie Produkte vor. Einsetzbar für PB- und PF-Erstgespräche.

## Input

- Kundenname und Praxisbezeichnung
- Website-URL der Praxis
- Verfügbare Vorinformationen (Empfehlung, Kontaktweg etc.)
- Optional: Branche (Zahnarzt, Arzt, Physio etc.)

## Output

- 1-Seiter Kundenbriefing mit:
  - Praxis-Profil (Größe, Fachrichtung, Standort, Team)
  - Potenzielle Schmerzpunkte (basierend auf Zielgruppen-Analyse)
  - Vorgeschlagene Gesprächspunkte (priorisiert)
  - Passende Produkte/Pakete (Medikit, VFD etc.)
  - Eisbrecher / Gesprächseinstieg

## Referenzen

- `basisdokumente/tf01_praxisberatung/Zielgruppen-PB-V3.md`
- `basisdokumente/tf01_praxisberatung/customer-journey-PB-v3.md`

## Workflow

1. Kundenname und Website-URL entgegennehmen
2. Website analysieren (Praxisgröße, Team, Leistungen, Auftritt)
3. Zielgruppen-Dokument laden und passende Persona identifizieren
4. Customer Journey analysieren — wo steht diese Praxis vermutlich?
5. Schmerzpunkte und Bedürfnisse ableiten
6. Passende Produkte/Pakete zuordnen
7. 1-Seiter formatieren
8. Juliane vor dem Gespräch übergeben

## Hinweise

- Das Briefing soll Juliane vorbereiten, nicht den Kunden ersetzen — Raum für Entdeckungen lassen
- Website-Analyse ist keine Bewertung — neutral und wertschätzend formulieren
- Schmerzpunkte als "mögliche Herausforderungen" formulieren, nicht als Mängel
- Bei fehlender Website: Briefing auf Basis der verfügbaren Infos erstellen, Lücken markieren
- Zeitaufwand: Briefing soll in unter 5 Minuten lesbar sein
