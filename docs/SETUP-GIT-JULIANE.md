# Git-Setup fuer Juliane — Schritt-fuer-Schritt

## Was ist das Ziel?

Du bekommst den kompletten JH Pro Ordner auf deinen Mac.
Darin sind alle deine Basisdokumente, Dossiers, Skills und Vorlagen.

Wenn Dominique Updates macht (neue Skills, verbesserte Dokumente),
holst du sie mit **2 Klicks** auf deinen Rechner.
Du musst nichts programmieren oder im Terminal arbeiten.

---

## Schritt 1: GitHub-Account erstellen

1. Oeffne im Browser: **https://github.com/signup**
2. Erstelle einen kostenlosen Account
   - E-Mail: z.B. `hallo@juliane-hoffmann.de`
   - Benutzername: z.B. `juliane-hoffmann` (oder was du magst)
   - Passwort: Sicheres Passwort waehlen
3. Bestatige deine E-Mail-Adresse (GitHub schickt dir einen Link)
4. **Schick Dominique deinen GitHub-Benutzernamen** per Nachricht
   → Er schaltet dich dann frei

⏳ **Warte auf Schritt 2, bis Dominique dich freigeschaltet hat.**

---

## Schritt 2: Einladung annehmen

- Du erhaeltst eine E-Mail von GitHub:
  **"DigitalWinWin has invited you to collaborate on jh-pro"**
- Klicke in der E-Mail auf **"Accept invitation"**
- Falls du keine E-Mail findest: Schau im Spam-Ordner
  oder oeffne direkt https://github.com/DigitalWinWin/jh-pro

---

## Schritt 3: GitHub Desktop installieren

GitHub Desktop ist eine App — kein Terminal, keine Befehle.

1. Oeffne im Browser: **https://desktop.github.com**
2. Klicke auf **"Download for macOS"**
3. Oeffne die heruntergeladene Datei
4. Ziehe die App in deinen **Programme**-Ordner
5. Oeffne **GitHub Desktop**
6. Klicke auf **"Sign in to GitHub.com"**
7. Melde dich mit deinem GitHub-Account an (aus Schritt 1)

---

## Schritt 4: Ordner auf deinen Mac holen ("Klonen")

1. In GitHub Desktop: Klicke oben auf **File → Clone Repository...**
2. Klicke auf den Tab **"URL"**
3. Gib diese Adresse ein:

   ```
   https://github.com/DigitalWinWin/jh-pro.git
   ```

4. Bei **"Local Path"** waehle, wo der Ordner hin soll:
   - Empfehlung: `/Users/juliane/Documents/jh-pro`
   - (Klicke auf "Choose..." und waehle deinen Dokumente-Ordner)
5. Klicke auf **"Clone"**
6. Warte bis der Download fertig ist (wenige Sekunden)

**Fertig!** Der Ordner `jh-pro` ist jetzt auf deinem Mac.

---

## Schritt 5: Updates holen (ab jetzt dein Alltag)

Wenn Dominique dir schreibt "Neues Update verfuegbar":

1. Oeffne **GitHub Desktop**
2. Klicke oben auf **"Fetch origin"** (blauer Button)
3. Falls es Neuigkeiten gibt, aendert sich der Button zu **"Pull origin"**
4. Klicke auf **"Pull origin"**
5. **Fertig** — alle Aenderungen sind auf deinem Mac

```
Das ist alles. 2 Klicks — Fetch, Pull.
```

---

## Was ist im Ordner?

Nach dem Klonen findest du diese Struktur:

```
jh-pro/
│
├── basisdokumente/           ← Deine 7 Basisdokumente pro Bereich
│   ├── _uebergreifend/       ← Persoenliche Marke (fuer ALLE Bereiche)
│   │   ├── v1/               ← Version 1
│   │   └── v2/               ← Version 2 (neuer)
│   ├── tf01_praxisberatung/  ← Praxisberatung
│   ├── tf02_praxisfactory/   ← Praxis Factory
│   ├── tf03_drflex/          ← Dr. Flex
│   ├── tf04_innodentum/      ← Innodentum
│   ├── tf05_abrechnung/      ← Abrechnungsunternehmen
│   └── tf06_waldorfschule/   ← Waldorfschule
│
├── dossier/                  ← Faktsheets & Uebersichten
│   ├── 00_Taetigkeitsbereiche-Uebersicht.md
│   ├── 01_Faktsheet-Praxisberatung.md
│   └── ... (6 Faktsheets)
│
├── brand/                    ← Logo, Schriften, Templates (kommt spaeter)
├── dist/                     ← Fertige Skills zum Installieren (kommt spaeter)
├── docs/                     ← Anleitungen (diese Datei!)
├── wissensextraktion/        ← Dein Wissens-Archiv
└── taetigkeitsfeld-register.md  ← Uebersicht aller 6 Bereiche
```

---

## Haeufige Fragen

### "Ich habe aus Versehen eine Datei geaendert"
Kein Problem:
1. Oeffne GitHub Desktop
2. Rechtsklick auf die geaenderte Datei
3. Waehle **"Discard Changes"**
→ Die Datei ist wieder wie vorher

### "Muss ich etwas hochladen?"
**Nein.** Du holst dir nur Updates ab. Dominique macht alle
Aenderungen im System. Du arbeitest nur mit den Dateien auf deinem Mac.

### "Kann ich den Ordner verschieben?"
Ja, aber dann musst du in GitHub Desktop den neuen Pfad angeben:
File → Add Local Repository → neuen Ordner waehlen.

### "Wie verbinde ich das mit Claude?"
Das kommt in einem naechsten Schritt — Dominique richtet das
zusammen mit dir ein. Vorerst hast du einfach alle Dokumente
als Nachschlagewerk auf deinem Mac.

### "Was kostet das?"
GitHub ist kostenlos. GitHub Desktop ist kostenlos.
Kein Abo, keine versteckten Kosten.

---

## Zusammenfassung

| Schritt | Was | Zeitaufwand |
|---------|-----|-------------|
| 1 | GitHub-Account erstellen | 5 Minuten |
| 2 | Einladung annehmen | 1 Minute |
| 3 | GitHub Desktop installieren | 5 Minuten |
| 4 | Ordner klonen (einmalig) | 2 Minuten |
| 5 | Updates holen (ab jetzt) | 30 Sekunden |

**Gesamtaufwand einmalig: ~15 Minuten**
**Updates holen: 30 Sekunden pro Mal**

---

## Bei Fragen

Schreib Dominique: **ds@digital.winwin.global**
Oder per WhatsApp/Telegram — wie gewohnt.

---

*JH Pro v1.0 — Erstellt von Digital WinWin fuer Juliane Hoffmann*
*Stand: 17. Maerz 2026*
