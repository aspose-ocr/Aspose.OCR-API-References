---
title: "RecognitionSettings"
second_title: "Aspose.OCR för Python via .NET API-referens"
description: 
type: docs
weight: 330
url: /sv/python-net/aspose.ocr/recognitionsettings/
---

## RecognitionSettings class

Inställningar för bildigenkänning.<br/>            Innehåller element som möjliggör anpassning av igenkänningsprocessen.

Typen RecognitionSettings exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| RecognitionSettings() | Initierar en ny instans av |
| RecognitionSettings(language, recognition_areas, recognize_single_line) | Initierar en ny instans av klassen RecognitionSettings |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| recognize_vertical_lines |  |
| threads_count | Hämtar eller anger antalet trådar för bearbetning. |
| language | Hämtar eller anger språket som används för OCR. |
| ignored_symbols | Ställer in svartlista för igenkänningssymboler. |
| allowed_symbols | Ställ in de tillåtna tecknen med egenskapen alphabet. |
| allowed_characters | Uppsättning av tillåtna tecken. Bestämmer vilken typ av tecken som är tillåtna för igenkänningsresultatet. |
| automatic_color_inversion | Detektera bilder med vit text på mörk/svart bakgrund och automatiskt välja en speciell OCR-algoritm för dem. |
| recognition_areas | Hämtar eller anger listan över textområden för bearbetning. |
| recognize_single_line | Ställer in enradig bildigenkänning. <br/>            Inaktiverad (false) som standard. <br/>            Inaktivera alla bearbetningssteg som är associerade med att dela upp i rader. <br/>            Sätt detta parameter till true om din bild bara innehåller en rad. Inaktiverar inställningar för RecognitionAreas, så alla områdesinställningar kommer att ignoreras. |
| language_detection_level |  |
| lines_filtration | Tillåter att känna igen text i tabellerna (regioner omgivna av linjer). |
| detect_areas_mode | Tillåter att välja det optimala läget för områden av dokumenttyp: dokument, foto, vanlig text, kolumn, bild. |
| upscale_small_font | Tillåter dig att använda ytterligare algoritmer specifikt för igenkänning av små teckensnitt.<br/>            Användbart för bilder med små tecken. |

### Se även

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

