# VS-Code-Clicker

Ein Idle-/Tycoon-Spiel, das aussieht wie ein Code-Editor. Du startest mit einem kleinen Blog und baust ein Tech-Imperium auf, und für alle anderen sieht es so aus, als würdest du programmieren.

Inspiriert von [Quarter Close](https://kpa-clawbot.github.io/quarter-close/), nur im Editor-Stil statt Excel.

## Spielen

Öffne `index.html` im Browser oder aktiviere GitHub Pages (Settings → Pages → Branch `main`, Ordner `/`).
Drücke **F11** für den Vollbildmodus, dann sieht man den Browser nicht mehr.

## Tasten

| Taste | Funktion |
|---|---|
| **Esc** | Boss-Taste: wechselt sofort zu einer Python-Hausübung |
| Strg+S | Speichern (zusätzlich automatisch alle 15 s) |
| Strg+Enter | Alle Umsätze committen |
| Strg+Umschalt+P / F1 | Befehlspalette |
| Strg+B / Strg+J | Seitenleiste / Panel umschalten |

## Spielprinzip

- **company.ts**: Die grauen Links über den Abteilungen sind Aktionen: Einstellen, Max, Upgrade (+50 %), Automatisieren, Commit.
- **Commit**: Nicht automatisierte Abteilungen sammeln „uncommitted“ Umsatz, den du einsammeln musst.
- **Fokus**: Ein Klick auf den Abteilungsnamen gibt +25 % (bis ×3, verfällt langsam).
- **💡 Leuchtende Zeile**: Schnell anklicken bringt einen Bonus.
- **Pull Requests**: Mehrmals „Approve“ klicken bringt einen Enterprise-Vertrag.
- **Quick Fixes**: Serien geben bis zu ×3.
- **Terminal**: Funktioniert wirklich, tippe `help`.
- **finance.ts**: Jedes Quartal eine Guidance wählen. Übertriffst du das Ziel, bekommst du Retained Earnings (RE).
- **Erweiterungen**: RE im Marketplace für dauerhafte Boni ausgeben.
- **Steuern**: Alle 90 Tage kommt ein Steuerbescheid. Wer nicht zahlt, wird gepfändet.
- **Series A** (ab $100K Gesamtumsatz) schaltet die C-Suite (CFO/CTO/COO) frei, der **IPO** (ab $25M Jahresumsatz) bringt Aktienkurs und Restrukturierung (★).
- **Krisen**: Absturz, Ransomware, DDoS, Merge-Konflikt und mehr.

Der Spielstand wird im Browser gespeichert (localStorage) und lässt sich als `.json` exportieren und importieren.
