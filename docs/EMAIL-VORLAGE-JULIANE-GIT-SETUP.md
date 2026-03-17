# E-Mail an Juliane — Git-Setup & erste Aufgaben

**An:** Juliane Hoffmann
**Betreff:** Dein jh-pro Ordner ist bereit — so holst du ihn + erste Aufgabe
**Von:** Dominique

---

Hallo Juliane,

Ich habe dein KI-Arbeitsumgebung-Repo fertig aufgesetzt. Alles was du brauchst — Basisdokumente, Skills, Vorlagen, Brand-Infos — ist jetzt an einem Ort und du kannst es auf deinen Mac holen.

## 1. Transkript unserer heutigen Besprechung

Das Transkript von heute liegt bereits im Ordner unter:

```
jh-pro/docs/transkripte/Juliane Hoffmann - Claude Praxisschulung – 2026_03_17 11_57 CET – Notizen von Gemini.md
```

Sobald du den Ordner auf deinem Mac hast (siehe unten), kannst du es dort nachlesen.

---

## 2. Ordner auf deinen Mac holen (einmalig, ~15 Minuten)

Die ausführliche Anleitung liegt unter `jh-pro/docs/SETUP-GIT-JULIANE.md`. Hier die Kurzversion:

**Schritt 1:** Falls du noch keinen GitHub-Account hast: https://github.com/signup
Schick mir dann deinen Benutzernamen — ich schalte dich frei.

**Schritt 2:** Lade GitHub Desktop herunter: https://desktop.github.com
Installiere die App und melde dich mit deinem GitHub-Account an.

**Schritt 3:** In GitHub Desktop:
- Klicke **File → Clone Repository...**
- Tab **"URL"**
- Eingeben: `https://github.com/DigitalWinWin/jh-pro.git`
- Speicherort: z.B. `/Users/juliane/Documents/jh-pro`
- Klicke **"Clone"**

Fertig — der Ordner ist auf deinem Mac.

**Updates holen (2 Klicks, 30 Sekunden):**
1. Öffne GitHub Desktop
2. Klicke **"Fetch origin"** → dann **"Pull origin"**

---

## 3. Deine 2 Skills in den Ordner integrieren

Du hast in der Schulung 2 eigene Skills erstellt:
- **Instagram-Karussell-Beitrag erstellen**
- **Beratungsmappe erstellen** (oder ähnlich)

Diese Skills sollen jetzt sauber in deinen jh-pro Ordner integriert werden.

**So machst du das:**

1. Öffne **Claude (Cowork / Desktop)**
2. Öffne den Ordner **jh-pro** als Projekt in Claude
3. Gib Claude folgenden Prompt:

---

> Ich habe 2 Skills erstellt, die ich in mein jh-pro System integrieren möchte:
>
> 1. **Instagram-Karussell-Beitrag** (Skill für Karussell-Posts für Praxisberatung)
> 2. **Beratungsmappe** (Skill für Beratungsmappen für meine Praxiskunden)
>
> Bitte erledige folgendes:
>
> **A) Skills in die Skill-Ordner einordnen:**
> - Erstelle für jeden Skill einen eigenen Ordner unter `skills/` (z.B. `skills/jh-instagram-karussell/` und `skills/jh-beratungsmappe/`)
> - Lege dort jeweils eine `SKILL.md` an mit dem Skill-Inhalt
> - Falls es Referenzdateien oder Vorlagen gibt: in einen Unterordner `references/` oder `assets/`
>
> **B) Skills als .skill-Paket verpacken:**
> - Erstelle für jeden Skill eine `.skill`-Datei und lege sie unter `dist/` ab
> - Eine .skill-Datei ist ein ZIP mit der Struktur: `skillname/SKILL.md` + ggf. references/
>
> **C) Folgende Dateien aktualisieren:**
> - `CLAUDE.md` → Ergänze die neuen Skills in der Skills-Referenz-Tabelle
> - `docs/SKILL-UEBERSICHT.md` → Füge die neuen Skills zur Tabelle hinzu
> - `README.md` → Falls nötig die Skill-Anzahl aktualisieren
>
> Zeig mir was du gemacht hast, bevor du es speicherst.

---

## 4. Änderungen hochladen (Commit & Push)

Nachdem Claude die Skills integriert hat, musst du die Änderungen "hochladen" — so dass ich sie auch sehe und wir beide immer auf dem gleichen Stand sind.

### Was bedeutet das?

Stell dir vor, der jh-pro Ordner ist wie ein **gemeinsames Notizbuch**:
- **Commit** = Du schreibst einen Eintrag ins Notizbuch ("Diese Änderungen habe ich gemacht")
- **Push** = Du legst das Notizbuch zurück ins Regal, so dass ich es auch lesen kann

Deine Kundendaten gehen dabei **NICHT** ins Internet — nur die System-Dateien (Skills, Basisdokumente etc.).

### Schritt für Schritt in GitHub Desktop:

**Schritt 1: Änderungen anschauen**
- Öffne **GitHub Desktop**
- Links siehst du eine Liste mit allen geänderten Dateien (grün = neu, gelb = geändert)
- Schau kurz drüber ob das passt

**Schritt 2: Commit erstellen**
- Unten links siehst du ein Textfeld **"Summary"**
- Schreib dort rein was du gemacht hast, z.B.:
  `Zwei neue Skills hinzugefügt: Instagram-Karussell + Beratungsmappe`
- Klicke auf den blauen Button **"Commit to main"**

**Schritt 3: Push (hochladen)**
- Oben in der Mitte erscheint jetzt **"Push origin"**
- Klicke auf **"Push origin"**
- Warte kurz bis der Upload fertig ist
- **Fertig!** Ich kann jetzt deine Änderungen sehen.

### Zusammenfassung Push-Ablauf:

```
1. GitHub Desktop öffnen
2. Änderungen prüfen (links die Dateiliste)
3. Unten: Kurze Beschreibung eintippen
4. "Commit to main" klicken
5. "Push origin" klicken
6. Fertig!
```

---

## Was liegt jetzt alles in deinem jh-pro Ordner?

| Ordner | Inhalt | Für dich wichtig? |
|--------|--------|-------------------|
| `basisdokumente/` | 38 Wissensdokumente (alle 6 Bereiche) | Ja — Claude nutzt die automatisch |
| `skills/` | 13 Skills + deine 2 neuen | Ja — deine Werkzeuge |
| `dist/` | Fertige .skill-Pakete | Nur bei Weitergabe |
| `brand/` | Logos, Farben (PB + PF) | Ja — für Designs |
| `vorlagen/` | Templates (Angebote, Protokolle, Berichte) | Ja — Vorlagen für Dokumente |
| `kunden/` | Kundenordner (nur lokal!) | Ja — deine Praxen |
| `docs/` | Anleitungen, Prozesslandkarte, Transkripte | Bei Bedarf nachlesen |
| `mcp-konfiguration/` | MCP-Setup-Anleitungen | Später, wenn wir Integrationen machen |
| `CLAUDE.md` | System-Regeln für Claude | Nicht anfassen — Claude liest das automatisch |

---

## Bei Fragen

Schreib mir einfach — per Mail, WhatsApp oder Telegram. Wenn du irgendwo hängen bleibst, machen wir einen kurzen Call.

Liebe Grüsse,
Dominique

ds@digital.winwin.global
