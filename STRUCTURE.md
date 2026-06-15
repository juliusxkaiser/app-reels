# Reel-Library — Ordnerstruktur

Eine Master-Struktur für alle Apps. Für jede App drei Produktionsquellen, je mit Sprach-Ordnern.

```
library/
  <app>/                     backlyne · dateheart · ganglow · famcube
    remotion/                Remotion-gerenderte Reels (App-Walkthroughs, Hook-Reels, echte App-Mitschnitte)
      de/ en/ es/ fr/ it/ pt/   (+ hype/ wo vorhanden)
    higgsfield/              Higgsfield-KI-Clips (cineastisch) — Quelle: marketing/HIGGSFIELD-SHOTSHEETS.md
      de/ en/ …
    combined/                Remotion + Higgsfield kombiniert (App-Demo + KI-B-Roll im selben Schnitt)
      de/ en/ …
_archive/                    Alte Erst-Batch-Originale (superseded, nur zur Sicherung)
```

## Konventionen
- **Sprach-Codes:** `de en es fr it pt` (App-Locale). Weitere möglich: `nl pl sv da cs tr`.
- **Dateinamen:** `<APP>-<LANG>-<NN>.mp4` (z.B. `DH-DE-01.mp4`), echte App-Mitschnitte `BL-RealListing-<LANG>-01.mp4`.
- **Neue Reels:** immer unter die passende Quelle (`remotion`/`higgsfield`/`combined`) + Sprach-Ordner.
- **Galerie:** `library.html` (vollständig) zeigt die `remotion/`-Reels; `index.html` zeigt die `_archive/`-Originale.

## Status (2026-06-15)
- **remotion/**: gefüllt — Backlyne (DE/EN/ES/FR/IT/PT echt + synthetisch), DateHeart/GangGlow/FamCube (6 Sprachen).
- **higgsfield/** + **combined/**: Platzhalter (README), warten auf Higgsfield-Credits.
