# Nachhaltig-Wirtschaften

Quarto-Book-Quellcode für **„Einführung Nachhaltige Ökonomie"**, das Begleitskript zum gleichnamigen Kurs an der Universität Bern.

## 🎓 Über den Kurs

*Einführung Nachhaltige Ökonomie* ist eine Vorlesung an der Universität Bern im **Inverted-Classroom-Format**: Die Studierenden erarbeiten sich die Kursinhalte in Selbststudienphasen anhand dieses Begleitskripts sowie ergänzender Materialien auf [ILIAS](https://ilias.unibe.ch/go/crs/3443640); die Präsenzzeit wird für Vertiefung, Diskussion und Anwendung genutzt.

Das Skript führt in sechs Kapiteln in eine nachhaltige, pluralistische Perspektive auf Ökonomie ein:

1. Wie können wir über Ökonomie nachdenken?
2. Gegenstandsbereich der Ökonomie
3. Problemanalyse: Woran krankt unsere Wirtschaft?
4. Strategien für eine nachhaltige Wirtschaft: Effizienz, Konsistenz, Suffizienz
5. Die Rolle des Staates und wirtschaftspolitische Leitbilder
6. Nachhaltige Ökonomie: Zusammenführung

## 📚 CDE Open Educational Resources

Dieser Kurs ist Teil der Open Educational Resources des [Centre for Development and Environment (CDE)](https://www.cde.unibe.ch/) der Universität Bern. Eine Übersicht aller frei zugänglichen CDE-Lehrmaterialien findet sich unter [CDEteaching](https://cdeteaching.github.io/CDEteaching/). Struktur und Tooling dieses Repos sind an [CDEteaching/Basics-of-sustainability](https://github.com/CDEteaching/Basics-of-sustainability) angelehnt.

## 📜 Lizenz

Sofern nicht anders angegeben, stehen alle Materialien unter der [CC-BY-NC-SA 4.0 Int Lizenz](https://creativecommons.org/licenses/by-nc-sa/4.0/). Erstellt mit [Quarto](https://quarto.org/).

## 📖 Zitation

Bader, C., Bezzola, N., Brülisauer, S. (Hrsg.). (2026). Einführung Nachhaltige Ökonomie [Begleitskript]. CDE, Universität Bern.

## 🧩 Beitragsmatrix (CRediT-Taxonomie)

| Name | Affiliation | ORCID | Rollen (CRediT) |
|------------------|------------------|------------------|------------------|
| Christoph Bader | CDE, Universität Bern | [0000-0002-8991-353X](https://orcid.org/0000-0002-8991-353X) | Conceptualization, Software, Supervision, Writing – original draft, Writing – review & editing, Project administration |
| Nicolà Bezzola | CDE, Universität Bern | — | Writing – original draft, Writing – review & editing |
| Samuel Brülisauer | CDE, Universität Bern | [0000-0002-2196-1922](https://orcid.org/0000-0002-2196-1922) | Writing – original draft, Writing – review & editing |

## Struktur

- `_quarto.yml` — Quarto-Book-Konfiguration (Titel, Kapitelliste, Theme, Sidebar).
- `index.qmd` — Vorwort.
- `1_oekonomie-denken/` … `6_zusammenfuehrung/` — die sechs Kapitel, je ein `_intro.qmd` plus `images/`.
- `references.qmd` / `references.bib` — Literaturverzeichnis.
- `theme.scss`, `theme.css`, `webex.css`, `webex.js` — Theme- und Self-Check-Quiz-Assets, aus dem Referenz-Repo übernommen.
- `_extensions/coatless-quarto/custom-callout/` — Callout-Extension, aus dem Referenz-Repo übernommen.
