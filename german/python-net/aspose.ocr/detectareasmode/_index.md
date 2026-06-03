---
title: "DetectAreasMode"
second_title: "Aspose.OCR für Python via .NET API-Referenz"
description: 
type: docs
weight: 540
url: /de/python-net/aspose.ocr/detectareasmode/
---

## DetectAreasMode enumeration

Bestimmt den Typ des für die Flächenerkennung verwendeten neuronalen Netzwerks.

## Members
| Membername | Beschreibung |
| :- | :- |
| LEAN | Priorisiert Geschwindigkeit und reduziert den Ressourcenverbrauch, indem die Unterstützung für komplexe Layouts weggelassen wird. Nur geeignet für einfache Bilder mit wenigen Textzeilen ohne Illustrationen oder Formatierungen. |
| MULTICOLUMN | Erkennt große Textblöcke, die in Spalten formatiert sind. Die beste Wahl für mehrspaltige Layouts wie Buchseiten, Artikel oder Verträge. |
| UNIVERSAL | Erkennt alle Textblöcke im Bild, einschließlich spärlicher und unregelmäßiger Texte auf Fotos. Eine vielseitige Option für die meisten Bilder, außer für Tabellen und mehrspaltige Layouts. |
| TABLE | Erkennt tabellarische Strukturen im Bild und extrahiert Text aus einzelnen Zellen. Empfohlen für gescannte Tabellenkalkulationen, Berichte und andere tabellenbasierte Dokumente. |
| CURVED_TEXT | Richtet automatisch gekrümmte Textzeilen im Bild aus, verbessert die Erkennungsgenauigkeit und ermöglicht das Wiederherstellen und Extrahieren von mehr Text. Erfordert erhebliche Rechenleistung und RAM. |
| FORMULA |  |

### Siehe auch

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.OCR](/ocr/python-net/)

