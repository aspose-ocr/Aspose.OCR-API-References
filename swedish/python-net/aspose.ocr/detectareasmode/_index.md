---
title: "DetectAreasMode"
second_title: "Aspose.OCR för Python via .NET API-referens"
description: 
type: docs
weight: 540
url: /sv/python-net/aspose.ocr/detectareasmode/
---

## DetectAreasMode enumeration

Bestämmer typen av neuralt nätverk som används för områdesdetektering.

## Members
| Medlemsnamn | Beskrivning |
| :- | :- |
| LEAN | Prioriterar hastighet och minskar resursförbrukning genom att utelämna stöd för komplexa layouter. Lämplig endast för enkla bilder med några rader text utan illustrationer eller formatering. |
| MULTICOLUMN | Detekterar stora textblock som är formaterade i kolumner. Det bästa valet för flerkolumnslayouter såsom bokblad, artiklar eller kontrakt. |
| UNIVERSAL | Detekterar alla textblock i bilden, inklusive gles och oregelbunden text på foton. Ett mångsidigt alternativ för de flesta bilder, förutom tabeller och flerkolumnslayouter. |
| TABLE | Detekterar tabellstrukturer i bilden och extraherar text från enskilda celler. Rekommenderas för skannade kalkylblad, rapporter och andra tabellbaserade dokument. |
| CURVED_TEXT | Rätar automatiskt upp böjda textrader i bilden, vilket förbättrar igenkänningsnoggrannheten och möjliggör att mer text kan återvinnas och extraheras. Kräver betydande processorkraft och RAM. |
| FORMULA |  |

### Se även

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.OCR](/ocr/python-net/)

