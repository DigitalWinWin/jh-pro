---
skill_name: "jh-vfd-prozess"
skill_id: "S09"
version: "v0.1"
status: "platzhalter"
bereich: "PF"
erstellt: "2026-02-17"
erstellt-durch: "Digital WinWin"
---

# S09 — VFD-Erstellung begleiten (4 Termine a 90 Min)

## Beschreibung

Dieser Skill begleitet die Erstellung eines Verfahrensdokuments (VFD) im Rahmen der PraxisFactory. Der VFD-Prozess umfasst 4 Termine a 90 Minuten mit dem Mandanten. Der Skill bereitet jeden Termin vor, liefert Fragenkatalog und erstellt einen VFD-Struktur-Entwurf. Tools: EasyDoku für die finale Dokumentation und MS Teams für die Termine.

## Input

- Mandatsname und Praxisbezeichnung
- Praxistyp (Zahnarzt, Arzt, MVZ etc.)
- Bestehende Dokumentation (falls vorhanden)
- Aktueller Termin-Status (Termin 1/2/3/4)

## Output

- Termin-Vorbereitung mit:
  - Agenda für den jeweiligen Termin
  - Fragenkatalog (termin-spezifisch)
  - Zu besprechende Themen und Prozesse
- VFD-Struktur-Entwurf (wird über die 4 Termine vervollständigt)
- Zwischen-Zusammenfassung nach jedem Termin

## Referenzen

- `basisdokumente/tf02_praxisfactory/produktdefinition-PF-v2.md`
- `basisdokumente/tf02_praxisfactory/prozessinventar-PF-v2.md`

## Workflow

1. Mandatsinformationen und aktuellen Stand erfassen
2. Produktdefinition und Prozessinventar laden
3. Termin-spezifische Vorbereitung erstellen:
   - Termin 1: Bestandsaufnahme, Praxisstruktur, Kernprozesse
   - Termin 2: Detailanalyse Behandlungsprozesse, QM-Status
   - Termin 3: Unterstützungsprozesse, Schnittstellen, IT
   - Termin 4: Finalisierung, Lückenschluss, Maßnahmenplan
4. Fragenkatalog pro Termin erstellen
5. VFD-Struktur fortschreiben
6. Juliane die Unterlagen vor jedem Termin bereitstellen

## Hinweise

- VFD = Verfahrensdokumentation — gesetzlich gefordert für Praxen
- 4 Termine a 90 Minuten — Struktur einhalten für Effizienz
- EasyDoku ist das führende Tool für die finale VFD
- MS Teams für die Termine — Aufzeichnung für Nachbereitung empfohlen
- Zwischen den Terminen: Juliane arbeitet Ergebnisse in EasyDoku ein
- Sie-Anrede im PF-Bereich (fachlich, vertrauensvoll)
- Bei großen Praxen (>15 MA) kann ein 5. Termin nötig sein
