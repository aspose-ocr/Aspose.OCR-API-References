---
title: "RecognitionResult"
second_title: "Aspose.OCR för Python via .NET API-referens"
description: 
type: docs
weight: 290
url: /sv/python-net/aspose.ocr/recognitionresult/
---

## RecognitionResult class

Resultaten av bildigenkänning.<br/>            Innehåller element med igenkänningsinformation och metoder för export av resultat.

RecognitionResult-typen exponerar följande medlemmar:


## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| igenkänning_regioner_resultat | Hämtar en lista med igenkänningsresultat med en lista av regioner (Rektanglar). |
| recognition_lines_result | Hämtar en lista med igenkänningsresultat med en lista av rader (rektanglar). |
| recognition_characters_list | En uppsättning tecken som hittats av igenkänningsalgoritmen och ordnas i fallande sannolikhetsordning. |
| recognition_text | Hämtar igenkänningsresultatet i en sträng. |
| file_name | Fullständig sökväg till filen. |
| warnings | Hämtar en lista med varningsmeddelanden som beskriver icke-kritiska fel som uppstod under genereringen. |
| serializable_image |  |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| save(full_file_name, save_format, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) | Sparar dokumentet som ren text, PDF eller Microsoft Word-dokument. |
| save(full_file_name, save_format, embedded_font_path, optimize_pdf) | Sparar dokumentet som ren text, PDF eller Microsoft Word-dokument. |
| save(full_file_name, save_format, optimize_pdf) | Sparar dokumentet som ren text, PDF eller Microsoft Word-dokument. |
| save(stream, save_format, optimize_pdf) | Sparar dokumentet som ren text, PDF eller Microsoft Word-dokument. |
| save(stream, save_format, apply_spelling_correction, language, dictionary_path) | Sparar dokumentet som ren text, PDF eller Microsoft Word-dokument. |
| get_spell_check_corrected_text(language, dictionary_path) | Korrigerar text (ersätter felstavade ord). |
| get_spell_check_error_list(language, dictionary_path) | Hitta felstavade ord med föreslagna stavningar för en given indatatext. |
| get_json(is_readable) | Skapa JSON-sträng med igenkänningsresultat. |
| get_xml() | Skapa XML-sträng med igenkänningsresultat. |
| get_keywords() | Hämta nyckelord från pasport (Testläge. Fungerar endast för USA- och MADAGASCAR-pass). |

### Se även

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

