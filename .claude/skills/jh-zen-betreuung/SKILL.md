---
skill_name: "jh-zen-betreuung"
skill_id: "S10"
version: "v0.1"
status: "platzhalter"
bereich: "DF"
erstellt: "2026-02-17"
erstellt-durch: "Digital WinWin"
---

# S10 — ZEN-Kapitel-Betreuung und Video-Scripts

## Beschreibung

Dieser Skill unterstützt die Betreuung von Praxen im ZEN-Programm von Dr. Flex (DF). Das ZEN-Programm umfasst 7 Kapitel, die Praxen schrittweise durchlaufen. Der Skill liefert kapitelspezifische Betreuungshinweise, erstellt Video-Script-Entwürfe für HeyGen-Avatare und formuliert begleitende E-Mail-Texte für die Praxen.

## Input

- Praxisname und Ansprechpartner
- Aktuelles Kapitel (1-7)
- Fortschritt innerhalb des Kapitels
- Optional: Rückmeldungen oder Fragen der Praxis

## Output

- Kapitel-spezifische Betreuungshinweise für Juliane
- Video-Script-Entwurf für HeyGen-Avatar (1-3 Minuten)
- E-Mail-Text für die Praxis (Kapitel-Begleitung)
- Optional: FAQ-Antworten auf Praxis-Fragen

## Referenzen

- `basisdokumente/tf03_drflex/zen-praxis-kontextdokument-DF-v1.md`

## Workflow

1. Praxis-Daten und aktuellen Kapitel-Stand erfassen
2. ZEN-Kontextdokument laden und relevantes Kapitel identifizieren
3. Betreuungshinweise für Juliane erstellen
4. Video-Script für HeyGen-Avatar schreiben (natürlicher Sprechstil)
5. Begleit-E-Mail für die Praxis formulieren
6. Juliane zur Prüfung vorlegen
7. Nach Freigabe: Video in HeyGen erstellen, E-Mail versenden

## Hinweise

- ZEN = 7 Kapitel, aufeinander aufbauend — Reihenfolge einhalten
- HeyGen-Scripts müssen natürlich klingen — geschriebene Sprache ≠ gesprochene Sprache
- Video-Länge: 1-3 Minuten optimal, max. 5 Minuten
- E-Mails: Motivierend und ermutigend, nicht belehrend
- Anrede in E-Mails: Abhängig von der Praxis (Brandvoice DF-Bereich prüfen)
- Bei Praxen, die stagnieren: Sanfte Erinnerung, Hilfsangebot, keine Druckausübung
