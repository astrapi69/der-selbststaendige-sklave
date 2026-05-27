# Der selbstständige Sklave

**Autor:** Asterios Raptis
**Status:** Veröffentlicht (v1.0.0)
**Plattform:** Amazon KDP (eBook + Print)

## Über das Buch

Eine systematische Analyse der Mechanismen, mit denen der moderne Staat seine Bürger verwaltet, besteuert und kontrolliert, ohne dass diese es als solches wahrnehmen. Kein akademisches Buch, sondern eine Abrechnung.

## Struktur

| Teil | Thema | Kapitel |
|------|-------|---------|
| 1 | Was dir gehört | 1-3: Steuerbelastung, Sozialleistungen, Eigentum |
| 2 | Was du darfst | 4-6: Genehmigungspflichten, Regulierung, Überwachung |
| 3 | Was du wählen darfst | 7-9: Wahlsystem, Parteienstruktur, direkte Demokratie |
| 4 | Was sich ändern muss | 10-11: Reformansätze, Souveränität |

Plus Epilog und Impressum.

## Projektstruktur

```
.
├── der-selbststaendige-sklave_ebook.md    # Hauptmanuskript (eBook)
├── der-selbststaendige-sklave_ebook.epub  # Generiertes EPUB
├── der-selbststaendige-sklave_toc.md      # Inhaltsverzeichnis (eBook, verlinkt)
├── der-selbststaendige-sklave_toc-print.md # Inhaltsverzeichnis (Print, mit Seitenzahlen)
├── about-the-author.md                    # Über den Autor
├── acknowledgments.md                     # Danksagung
└── README.md
```

## Build

EPUB-Generierung via Pandoc:

```bash
pandoc der-selbststaendige-sklave_ebook.md -o der-selbststaendige-sklave_ebook.epub
```

Validierung:

```bash
epubcheck der-selbststaendige-sklave_ebook.epub
```

## Lizenz

Alle Rechte vorbehalten. Kein Teil dieses Werkes darf ohne schriftliche Genehmigung des Autors reproduziert oder verbreitet werden.
