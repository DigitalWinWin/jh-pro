# JH Pro — KI-Betriebssystem Juliane Hoffmann

Kundensystem fuer Juliane Hoffmann (Praxisberatung & Multi-TF).
Entwickelt von Digital WinWin (Dominique Stalder).

## Taetigkeitsfelder

| # | Bereich | Kuerzel |
|---|---------|---------|
| TF1 | Praxisberatung & Praxismanagement | PB |
| TF2 | Praxis Factory GmbH | PF |
| TF3 | Dr. Flex Kooperation | DF |
| TF4 | Innodentum | IN |
| TF5 | Abrechnungsunternehmen | AB |
| TF6 | Waldorfschule (Ehrenamt) | WS |

## Struktur

```
jh-pro/
├── .claude/              # Claude Code Konfiguration (CLAUDE.md, Skills, Agents)
├── basisdokumente/       # 7 Basisdokumente pro TF + uebergreifend
│   ├── _uebergreifend/   # Persoenliche Marke (gilt fuer alle TF)
│   ├── tf01_.../         # Pro Taetigkeitsfeld
│   └── ...
├── brand/                # Logo, Fonts, Templates
├── dist/                 # Fertige .skill-Dateien
├── docs/                 # Dokumentation, Transkripte
├── dossier/              # Faktsheets & Uebersichten
├── regelwerke/           # System-Regelwerke
├── rohdaten-input/       # Interview-Rohdaten
├── templates/            # Vorlagen
└── wissensextraktion/    # Knowledge Base, Nugget-Inventar
```

## Setup

1. Repo klonen: `git clone https://github.com/DigitalWinWin/jh-pro.git`
2. In Claude Code oeffnen: `cd jh-pro && claude`

## Lizenz

Proprietary — Digital WinWin GmbH
