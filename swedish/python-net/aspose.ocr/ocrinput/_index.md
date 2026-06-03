---
title: "OcrInput"
second_title: "Aspose.OCR för Python via .NET API-referens"
description: 
type: docs
weight: 240
url: /sv/python-net/aspose.ocr/ocrinput/
---

## OcrInput class

Behållare för att samla alla bilder / dokument för förbehandling / igenkänning.

Typen OcrInput exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| OcrInput(type, filters) | Initierar en ny instans av klassen OcrInput |
| OcrInput(type) | Initierar en ny instans av klassen OcrInput |
## Indexer
| Namn | Beskrivning |
| :- | :- |
| [index] | Returnerar information om bearbetad / igenkänd bild. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| add(full_path) | Lägg till sökvägen eller URI:n som innehåller bilden för igenkänning / bearbetning.<br/>            Bildens typ måste motsvara den typ som anges i konstruktorn. |
| add(stream) | Lägg till minnesströmmen som innehåller bilden för igenkänning / bearbetning.<br/>            Bildens typ måste motsvara den typ som anges i konstruktorn. |
| add(full_path, start_page, pages_count) | Lägg till flersidiga bilder / dokument för igenkänning / bearbetning.<br/>            Bildens typ måste motsvara den typ som anges i konstruktorn. |
| add(stream, start_page, pages_count) | Lägg till minnesströmmen som innehåller den flersidiga bilden för igenkänning / bearbetning.<br/>            Bildens typ måste motsvara den typ som anges i konstruktorn. |
| add(arr, width, height, pixel_format) | Lägg till den avkodade bilden i listan för igenkänning / bearbetning.<br/>            Bildens typ måste motsvara den typ som anges i konstruktorn (SingleImage). |
| replace_filters(filters) | Ta bort gamla filter och ange nya. |
| clear_filters() | Ta bort alla filter. |
| add_base64(base64) | Lägg till base64-strängen som innehåller bilden för igenkänning / bearbetning.<br/>            Bildens typ måste motsvara den typ som anges i konstruktorn. |
| clear() | Ta bort alla filter. |
| count() | Antal objekt för bearbetning / igenkänning. |
| get_input_type() | Typ av tillåtna bilder för igenkänning. |

### Se även

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

