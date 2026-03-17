# Skill-Übersicht — Juliane Hoffmann

> Alle 13 Skills für Julianes KI-Arbeitsumgebung.
> Skills werden über `skills/[skill-name]/SKILL.md` aufgerufen.

---

## Status-Legende

| Status | Bedeutung |
|--------|-----------|
| **Platzhalter** | Grundstruktur vorhanden, Skill noch nicht funktionsfähig |
| **Entwurf** | Erste Version geschrieben, noch nicht getestet |
| **Aktiv** | Getestet und einsatzbereit |

---

## Skill-Tabelle

| # | Skill-ID | Name | Bereich | Status | Beschreibung |
|---|----------|------|---------|--------|-------------|
| S01 | jh-coaching-protokoll | Coaching-Protokoll (Dual-Brand) | PB, PF | **Aktiv** | Erstellt Coaching-Protokolle aus Transkripten wahlweise im Branding von Praxis Factory GmbH oder JH Praxismanagement. Python-Script + DOCX-Templates. |
| S02 | jh-digitalisierungskonzept | Digitalisierungskonzept | PB | Entwurf | Erstellt ein Digitalisierungskonzept für Zahnarztpraxen basierend auf der Ist-Analyse. Berücksichtigt Medikit-Struktur und praxisspezifische Anforderungen. |
| S03 | jh-massnahmenplan | Maßnahmenplan | PB, PF | Entwurf | Leitet aus Beratungsgesprächen und Analysen konkrete Massnahmenpläne ab. Priorisiert nach Dringlichkeit und Aufwand, erstellt Zeitplan. |
| S04 | jh-email-management | E-Mail-Management | Alle | Entwurf | Erstellt E-Mail-Entwürfe, Follow-up-Vorlagen und Antwortvorschläge. Berücksichtigt Anrede-Regeln pro Bereich (Du/Sie) und Brand Voice. |
| S05 | jh-content-instagram | Instagram-Content | PB, WS | Entwurf | Plant und textet Instagram-Beiträge inkl. Bildideen, Hashtags und Posting-Zeiten. Unterscheidet zwischen PB (Juliane persönlich) und WS (Waldorfschule). |
| S06 | jh-angebotserstellung | Angebotserstellung | PB | Entwurf | Erstellt Angebote für Medikit-Pakete (Starter/Profi/Elite) mit individueller Anpassung. Nutzt Vorlagen aus `vorlagen/angebote/`. |
| S07 | jh-kundenbriefing | Kundenbriefing | PB, PF | Entwurf | Bereitet Kundenbriefings vor Erstgesprächen vor. Recherchiert verfügbare Infos (Website, Social Media) und erstellt Gesprächsleitfaden. |
| S08 | jh-medikit-setup | Medikit-Setup | PB | Entwurf | Erstellt die Medikit-Grundstruktur für neue Kunden: Organigramm, Vorlagen, Sichtrechte, Kapitelstruktur basierend auf Best Practices. |
| S09 | jh-vfd-prozess | VFD-Prozess | PF | Entwurf | Begleitet die VFD-Erstellung über 4 Termine. Erstellt Tagesordnungen, protokolliert Ergebnisse, trackt offene Punkte pro Termin. |
| S10 | jh-zen-betreuung | ZEN-Betreuung | DF | Entwurf | Betreut ZEN-Praxen durch die 7 Kapitel: Erstellt Video-Scripts (HeyGen), Aufgabenstellungen, Check-in-Vorbereitungen und Prüfungsfragen. |
| S11 | jh-faq-videokurs | FAQ-Videokurs | PB, DF | Entwurf | Plant FAQ-Videokurse mit HeyGen-Avatar: Themensammlung, Kursstruktur, Script-Erstellung, Produktionsplan. Erstes digitales Produkt. |
| S12 | jh-onboarding-plan | Onboarding-Plan | PB | Entwurf | Erstellt Onboarding-Pläne für neue Praxis-Mitarbeiter: Checklisten, Zeitpläne, Verantwortlichkeiten, Schulungsmaterial-Empfehlungen. |
| S13 | jh-unternehmensregeln | Unternehmensregeln | PB | Entwurf | Generiert Unternehmensregeln für Zahnarztpraxen anhand eines Fragebogens. Von Dresscode bis Kommunikationsregeln — strukturiert und praxistauglich. |

---

## Skill-Verteilung nach Bereich

| Bereich | Skills | Anzahl |
|---------|--------|--------|
| **PB** (Praxisberatung) | S01, S02, S03, S05, S06, S07, S08, S11, S12, S13 | 10 |
| **PF** (Praxis Factory) | S01, S03, S07, S09 | 4 |
| **DF** (Dr. Flex) | S01, S10, S11 | 3 |
| **WS** (Waldorfschule) | S01, S05 | 2 |
| **IN** (Innodentum) | S01 | 1 |
| **AB** (Didento) | S01 | 1 |

> Hinweis: S01 (Coaching-Protokoll) und S04 (E-Mail-Management) sind bereichsübergreifend einsetzbar.

---

## Skill-Dateien

Jeder Skill liegt unter `skills/[skill-name]/` mit folgender Struktur:

```
skills/
  jh-coaching-protokoll/
    SKILL.md              ← Skill-Definition (YAML Frontmatter + Anweisungen)
    references/           ← Referenz-Dokumente für den Skill
    assets/               ← Vorlagen, Beispiele
  jh-digitalisierungskonzept/
    SKILL.md
    references/
  ...
```

---

*Erstellt: Februar 2026 — Digital WinWin (Dominique Stalder)*
