# Abbildung 6 — BIP pro Kopf in der Schweiz

CDE-Style-Grafik für `2_gegenstandsbereich/2_intro.qmd`, Abbildung 6 (Bildunterschrift war bereits im Text vorhanden, die Abbildung selbst fehlte — im ursprünglichen Word-Dokument war dies ein natives Excel-Chart-Objekt, das bei der docx→Quarto-Konvertierung nicht automatisch extrahiert werden konnte).

## Datenquelle

**Maddison Project Database, Release 2020** (Bolt, J. & van Zanden, J. L., 2020), Groningen Growth and Development Centre, University of Groningen.
- Datei: `mpd2020.xlsx`, Sheet "Full data", Spalte `gdppc` (reales BIP pro Kopf in 2011-US-Dollar, KKP-bereinigt), Land "Switzerland".
- Heruntergeladen am 2026-08-17 direkt von `https://www.rug.nl/ggdc/historicaldevelopment/maddison/data/mpd2020.xlsx` (Downloadlink von der offiziellen Release-Seite `https://www.rug.nl/ggdc/historicaldevelopment/maddison/releases/maddison-project-database-2020`) — exakt die Version, auf die die bestehende Bildunterschrift im qmd bereits verweist.
- Für die Schweiz liegen in MPD2020 durchgehende Jahreswerte von 1851 bis 2018 vor (ein einzelner sehr grob geschätzter Wert für Jahr 1 wurde nicht verwendet).

## Transformation

Keine Berechnung — alle geplotteten Werte sind unveränderte `gdppc`-Werte aus der Quelle, auf ganze USD gerundet.

Für die Grafik wurde aus den 168 durchgehenden Jahreswerten (1851–2018) eine Zehnjahresauswahl getroffen (1851, 1860, 1870, …, 2010, 2018), damit die Linienchart-Vorlage (Marker + Punktbeschriftung pro Datenpunkt) lesbar bleibt — bei allen 168 Einzeljahren wären die Marker nicht mehr unterscheidbar. Die vollständige Jahresreihe liegt zusätzlich in `che_mpd2020_full_1851-2018.csv` in diesem Ordner, falls die volle Auflösung gebraucht wird.

## Transparenzhinweis

Diese Grafik wurde mit Unterstützung von Claude Code (Anthropic) erstellt — Transparenzhinweis gem. Art. 50 EU AI Act.

## Dateien

- `abbildung6-bip-pro-kopf-schweiz.png` — für den Druck/PDF-Export des Begleitskripts, auch bereits nach `../../images/abb0.png` kopiert und im qmd eingebunden.
- `abbildung6-bip-pro-kopf-schweiz.gif` — animierte Variante (autoplay bei Einfügen in PowerPoint), falls die Abbildung auch für eine Präsentation gebraucht wird.
- `abbildung6-bip-pro-kopf-schweiz.csv` — die 18 geplotteten Werte (Zehnjahresauswahl).
- `che_mpd2020_full_1851-2018.csv` — alle 168 Jahreswerte 1851–2018, ungekürzt.
