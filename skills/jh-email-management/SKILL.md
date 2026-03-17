---
skill_name: "jh-email-management"
skill_id: "S04"
version: "v0.1"
status: "platzhalter"
bereich: "Alle"
erstellt: "2026-02-17"
erstellt-durch: "Digital WinWin"
---

# S04 — E-Mail-Entwürfe und Vorlagen erstellen

## Beschreibung

Dieser Skill erstellt E-Mail-Entwürfe und wiederverwendbare Vorlagen für alle Tätigkeitsbereiche von Juliane. Er berücksichtigt die korrekte Ansprache (Sie/Du) je nach Bereich und Empfänger, orientiert sich an der Brandvoice und liefert versandfertige Entwürfe. Wichtig: Keine E-Mail wird ohne Julianes explizite Freigabe versendet.

## Input

- Kontext: Empfänger (Kunde, Partner, Kollegin etc.)
- Anlass (Erstansprache, Follow-up, Angebot, Terminbestätigung etc.)
- Gewünschter Ton (formell, freundlich-professionell, locker)
- Bereich (PB, PF, DF, WS) für korrekte Anrede-Regeln
- Optional: Inhaltliche Stichpunkte

## Output

- E-Mail-Entwurf mit:
  - Betreffzeile
  - Anrede (Sie/Du gemäß Brandvoice-Regeln pro Bereich)
  - Fließtext
  - Grussformel
  - Optional: Anhang-Hinweise

## Referenzen

- `basisdokumente/_uebergreifend/brandvoice-JH-v3.md` (Anrede-Regeln pro Bereich)

## Workflow

1. Kontext und Anlass erfassen
2. Bereich identifizieren und Anrede-Regeln aus Brandvoice laden
3. E-Mail-Entwurf verfassen
4. Ton und Anrede gegenlesen
5. Entwurf Juliane zur Freigabe vorlegen
6. Nach Freigabe: Juliane versendet die E-Mail selbst

## Hinweise

- WICHTIG: Nie ohne Julianes Freigabe versenden — alle E-Mails sind Entwürfe
- PB-Bereich: Sie-Anrede (professionell, wertschätzend)
- PF-Bereich: Sie-Anrede (fachlich, vertrauensvoll)
- DF-Bereich: Abhängig vom Empfänger (Brandvoice prüfen)
- WS-Bereich: Du-Anrede (kollegial, herzlich)
- Betreffzeilen kurz und aussagekräftig halten
- Bei Angebots-Mails: Keine Preise im E-Mail-Text, Verweis auf Angebot im Anhang
