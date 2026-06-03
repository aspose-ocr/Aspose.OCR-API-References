---
title: "RecognitionResult"
second_title: "Aspose.OCR für Python via .NET API-Referenz"
description: 
type: docs
weight: 290
url: /de/python-net/aspose.ocr/recognitionresult/
---

## RecognitionResult class

Die Ergebnisse der Bilderkennung.<br/>            Enthält Elemente mit Erkennungsinformationen und Methoden zum Exportieren der Ergebnisse.

Der RecognitionResult-Typ stellt die folgenden Mitglieder bereit:


## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| recognition_regions_result | Gibt eine Liste von Erkennungsergebnissen mit einer Liste von Regionen (Rechtecke) zurück. |
| recognition_lines_result | Gibt eine Liste von Erkennungsergebnissen mit einer Liste von Zeilen (Rectangles) zurück. |
| recognition_characters_list | Eine Menge von Zeichen, die vom Erkennungsalgorithmus gefunden wurden und in absteigender Reihenfolge der Wahrscheinlichkeit angeordnet sind. |
| recognition_text | Gibt das Erkennungsergebnis als einen einzelnen String zurück. |
| file_name | Vollständiger Pfad zur Datei. |
| warnings | Gibt eine Liste der Warnmeldungen zurück, die nicht kritische Fehler beschreiben, die während der Generierung aufgetreten sind. |
| serializable_image |  |
## Methoden
| Name | Beschreibung |
| :- | :- |
| save(full_file_name, save_format, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) | Speichert das Dokument als Nur-Text, PDF oder Microsoft Word-Dokument. |
| save(full_file_name, save_format, embedded_font_path, optimize_pdf) | Speichert das Dokument als Nur-Text, PDF oder Microsoft Word-Dokument. |
| save(full_file_name, save_format, optimize_pdf) | Speichert das Dokument als Nur-Text, PDF oder Microsoft Word-Dokument. |
| save(stream, save_format, optimize_pdf) | Speichert das Dokument als Nur-Text, PDF oder Microsoft Word-Dokument. |
| save(stream, save_format, apply_spelling_correction, language, dictionary_path) | Speichert das Dokument als Nur-Text, PDF oder Microsoft Word-Dokument. |
| get_spell_check_corrected_text(language, dictionary_path) | Korrigiert Text (ersetzt falsch geschriebene Wörter). |
| get_spell_check_error_list(language, dictionary_path) | Findet die falsch geschriebenen Wörter mit vorgeschlagenen Rechtschreibungen für einen gegebenen Eingabetext. |
| get_json(is_readable) | Erstellt einen JSON-String mit Erkennungsergebnissen. |
| get_xml() | Erstellt einen XML-String mit Erkennungsergebnissen. |
| get_keywords() | Schlüsselwörter aus dem Pass (Testmodus. Funktioniert nur für USA- und MADAGASKAR-Pässe). |

### Siehe auch

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

