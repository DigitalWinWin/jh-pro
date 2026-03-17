---
name: jh-coaching-protokoll
description: |
  Juliane Hoffmann Coaching-Protokoll Generator (Dual-Brand).
  Erstellt Coaching-Protokolle wahlweise im Branding von Praxis Factory GmbH oder JH Praxismanagement.
  Aktivieren bei: Juliane Hoffmann, Praxismanagement, Praxis Factory, Praxisberatung, QM-Coaching, 
  Zahnarztpraxis-Beratung, JH Protokoll. Auch aktivieren wenn ein Coaching-Transkript für Juliane 
  verarbeitet werden soll oder ein Beratungsprotokoll im JH- oder PF-Branding benötigt wird.
  WICHTIG: Dieses Skill ist eigenständig - KEINE anderen Skills laden!
---

# JH Coaching-Protokoll (Dual-Brand)

Erzeugt Coaching-Protokolle wahlweise im Corporate Design von:
- **Praxis Factory GmbH** (Navy + Lime-Grün)
- **JH Praxismanagement** (Teal/Blau-Grau)

## WICHTIG - Dieses Skill ist komplett eigenständig!

- **KEIN** anderes Skill laden (kein docx, kein theme-factory, nichts!)
- **KEIN** JavaScript/docx-js verwenden
- **NUR** das enthaltene Python-Script `scripts/generate.py` verwenden
- Alle Brand-Werte sind bereits im Script hardcoded

## Workflow (4 Schritte)

1. **Brand klären** → Nutzer fragen: Praxis Factory oder JH Praxismanagement?
2. **Transkript analysieren** → Kernthemen, Erkenntnisse, Maßnahmen extrahieren
3. **JSON-Datei erstellen** → Speichern als `data.json` (mit `"brand"` Feld!)
4. **Script ausführen** → `python scripts/generate.py data.json Protokoll.docx`

## Brand-Auswahl

**Wenn aus dem Transkript oder Kontext nicht klar ersichtlich ist, für welche Firma das Protokoll ist, MUSS der Nutzer gefragt werden:**

> Für welche Firma soll das Protokoll erstellt werden?
> 1. **Praxis Factory GmbH** (praxisfactory)
> 2. **JH Praxismanagement** (praxismanagement)

**Hinweise zur automatischen Erkennung:**
- Erwähnung von "Praxis Factory", "PF", "GmbH", "VFD" → `praxisfactory`
- Erwähnung von "Praxismanagement", "JH", "Praxisberatung", "QM" → `praxismanagement`
- Im Zweifel: IMMER fragen!

Das brand-Feld wird im JSON gesetzt:
```json
{
  "brand": "praxisfactory",
  ...
}
```

## WICHTIG: JSON-Formatierung

**NIEMALS Anführungszeichen " im Text verwenden!** Sie brechen die JSON-Struktur.

Stattdessen:
- Apostrophe `'` verwenden: `"Er sagte: 'Das ist wichtig'"`
- Oder Anführungszeichen weglassen: `"Er sagte, das sei wichtig"`

Beispiel FALSCH:
```json
"text": "Sie sagte "Danke" zu mir"
```

Beispiel RICHTIG:
```json
"text": "Sie sagte 'Danke' zu mir"
```

## JSON-Schema

```json
{
  "brand": "praxisfactory",
  "kunde": "Dr. Max Mustermann",
  "datum": "17.02.2026",
  "dauer": "60",
  "format": "Zoom",
  "anliegen": "Freitext zum Anliegen der Session",
  "kernthemen": [
    {
      "titel": "Thema-Titel",
      "einleitung": "Einleitungssatz (optional)",
      "punkte": ["Punkt 1", "Punkt 2", "Punkt 3"],
      "erkenntnis": "Zentrale Erkenntnis (optional)"
    }
  ],
  "erkenntnisse": ["Aha-Moment 1", "Aha-Moment 2"],
  "zitat": "Wörtliches Kundenzitat OHNE Anführungszeichen (optional)",
  "reflexion": ["Absatz 1", "Absatz 2"],
  "massnahmen": [
    {"wer": "Kunde", "was": "Beschreibung der Maßnahme", "bis_wann": "24.02.2026"},
    {"wer": "Juliane", "was": "Beschreibung der Maßnahme", "bis_wann": "21.02.2026"}
  ],
  "sonstiges": ["Notiz 1", "Notiz 2"],
  "sessions": [
    {"session": "Aktuelle Session", "datum": "17.02.2026", "status": "✓ Abgeschlossen"},
    {"session": "Nächste Session", "datum": "03.03.2026", "status": "Geplant"}
  ]
}
```

## Die 7 Abschnitte

| # | Abschnitt | Inhalt |
|---|-----------|--------|
| 1 | Anliegen & Ziel | Was war das Thema? (2-4 Sätze) |
| 2 | Kernthemen | 3-5 Themen mit Unterpunkten |
| 3 | Erkenntnisse | Aha-Momente + Kundenzitat |
| 4 | Reflexion | Wie hat Kunde die Session erlebt? |
| 5 | Maßnahmen | Tabelle: Wer / Was / Bis wann |
| 6 | Sonstiges | Randnotizen, Organisatorisches |
| 7 | Status | Tabelle: Session / Datum / Status |

## Inhaltliche Regeln

**Kernthemen identifizieren:**
- 3-5 Hauptthemen pro Session
- Je Thema: Titel + 2-4 Unterpunkte
- Zentrale Erkenntnisse hervorheben

**Maßnahmen formulieren:**
- Jede Maßnahme braucht eine Deadline
- Verantwortlichkeit klar: Kunde oder Juliane
- Konkret und überprüfbar
- "Coach" im wer-Feld wird automatisch zu "Juliane" konvertiert

**Zitate verwenden:**
- Wörtlich aus Transkript übernehmen
- Im JSON OHNE Anführungszeichen eingeben (Script fügt sie hinzu)
- Nur besonders prägnante Aussagen

## Anti-Floskeln

NIEMALS verwenden:
- "In der heutigen schnelllebigen Zeit..."
- "Auf das nächste Level bringen"
- "Game-Changer" / "Transformativ"
- "Potenzial entfalten"
- "Es ist bemerkenswert, dass..."
- Jegliche Marketing-Buzzwords

## Tone of Voice

- **Kollegial** - wie eine erfahrene Kollegin
- **Direkt** - klar und pragmatisch
- **Kompetent** - fundiert, branchenkundig
- **Empathisch** - verständnisvoll, nicht weich

## Brand-Farbschemen (Referenz)

### Praxis Factory GmbH
| Element | Farbe | Hex |
|---------|-------|-----|
| Titel/H1 | Navy | #1B3A5C |
| H2/Meta | Blau | #234B6E |
| Akzent/Linien | Lime-Grün | #C2D530 |
| Hintergründe | Hell-Lime | #EEF5D5 |

### JH Praxismanagement
| Element | Farbe | Hex |
|---------|-------|-----|
| Titel/H1 | Dunkel-Teal | #3D5A6B |
| H2/Meta | Teal | #7A9BA5 |
| Akzent/Linien | Teal | #7A9BA5 |
| Hintergründe | Hell-Teal | #E4EDF0 |

## Dateien

- `scripts/generate.py` - Generiert DOCX aus JSON (Dual-Brand)
- `assets/template-praxisfactory.docx` - Template mit PF-Header/Footer/Logo
- `assets/template-praxismanagement.docx` - Template mit JH-Header/Footer/Logo
