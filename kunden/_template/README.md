# Kunden-Template

Diesen Ordner als Vorlage für neue Kunden verwenden.

## Verwendung

1. Ordner kopieren und umbenennen: `[bereich]_[kundenname]` (z.B. `pb_praxis-mueller`)
2. `KONTEXT.md` öffnen und Stammdaten ausfüllen
3. Diese README.md löschen
4. Dateien in die jeweiligen Unterordner ablegen

## Ordnerstruktur

```
[bereich]_[kundenname]/
├── KONTEXT.md          ← ZENTRAL: Status, Fortschritt, Verlauf (immer aktuell halten!)
├── protokolle/         ← Meeting-Protokolle, chronologisch [S01]
├── konzepte/           ← Digitalisierungskonzepte [S02], Maßnahmenpläne [S03]
├── angebote/           ← Angebote [S06], Auftragsbestätigungen
├── medikit/            ← Medikit-Setup-Dokumentation [S08]
├── onboarding/         ← Onboarding-Pläne [S12], Unternehmensregeln [S13]
├── transkripte/        ← Gesprächs-Transkripte (Zoom, Meet)
└── dokumente/          ← Sonstige Unterlagen
```

## Namenskonvention

- Protokolle: `YYYY-MM-DD-[thema].md`
- Konzepte: `[typ]-[kundenname]-v[version].md`
- Angebote: `angebot-[kundenname]-[datum].md`
- Transkripte: `YYYY-MM-DD-[gespraechstyp].txt`

## KONTEXT.md-Workflow

**Vor jedem Skill:** KONTEXT.md lesen → aktuellen Stand prüfen
**Nach jedem Skill:** Checkbox abhaken, Verlauf-Eintrag, nächsten Schritt setzen

So weiß Claude bei jedem Gespräch sofort, wo du mit diesem Kunden stehst.
