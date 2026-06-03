---
title: "OcrInput"
second_title: "Aspose.OCR für Python via .NET API-Referenz"
description: 
type: docs
weight: 240
url: /de/python-net/aspose.ocr/ocrinput/
---

## OcrInput class

Container zum Sammeln aller Bilder / Dokumente für die Vorverarbeitung / Erkennung.

Der OcrInput-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| OcrInput(type, filters) | Initialisiert eine neue Instanz der OcrInput-Klasse |
| OcrInput(type) | Initialisiert eine neue Instanz der OcrInput-Klasse |
## Indexer
| Name | Beschreibung |
| :- | :- |
| [index] | Gibt Informationen über das verarbeitete / erkannte Bild zurück. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| add(full_path) | Fügt den Pfad oder die URI hinzu, die das Bild für die Erkennung / Verarbeitung enthält.<br/>            Der Typ des Bildes muss dem im Konstruktor angegebenen Typ entsprechen. |
| add(stream) | Fügt den Speicherstream hinzu, der das Bild für die Erkennung / Verarbeitung enthält.<br/>            Der Typ des Bildes muss dem im Konstruktor angegebenen Typ entsprechen. |
| add(full_path, start_page, pages_count) | Fügt die mehrseitigen Bilder / Dokumente für die Erkennung / Verarbeitung hinzu.<br/>            Der Typ des Bildes muss dem im Konstruktor angegebenen Typ entsprechen. |
| add(stream, start_page, pages_count) | Fügt den Speicherstream hinzu, der das mehrseitige Bild für die Erkennung / Verarbeitung enthält.<br/>            Der Typ des Bildes muss dem im Konstruktor angegebenen Typ entsprechen. |
| add(arr, width, height, pixel_format) | Fügen Sie das dekodierte Bild zur Liste für Erkennung / Verarbeitung hinzu.<br/>            Der Typ des Bildes muss dem im Konstruktor angegebenen Typ entsprechen (SingleImage). |
| replace_filters(filters) | Entfernen Sie alte Filter und setzen Sie neue. |
| clear_filters() | Entfernen Sie alle Filter. |
| add_base64(base64) | Fügen Sie die Base64-Zeichenkette, die das Bild für Erkennung / Verarbeitung enthält, hinzu.<br/>            Der Typ des Bildes muss dem im Konstruktor angegebenen Typ entsprechen. |
| clear() | Entfernen Sie alle Filter. |
| count() | Anzahl der Elemente für Verarbeitung / Erkennung. |
| get_input_type() | Typ der zulässigen Bilder für die Erkennung. |

### Siehe auch

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

