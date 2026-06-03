---
title: "RecognitionResult"
second_title: "Aspose.OCR voor Python via .NET API-referentie"
description: 
type: docs
weight: 290
url: /nl/python-net/aspose.ocr/recognitionresult/
---

## RecognitionResult class

De resultaten van de beeldherkenning.<br/>            Bevat elementen met herkenningsinformatie en methoden voor het exporteren van resultaten.

Het RecognitionResult-type geeft de volgende leden weer:


## Eigenschappen
| Naam | Beschrijving |
| :- | :- |
| herkenningsregio_result | Haalt een lijst met herkenningsresultaten op met een lijst van regio's (Rechthoeken). |
| recognition_lines_result | Haalt een lijst met herkenningsresultaten op met een lijst met rijen (Rechthoeken). |
| recognition_characters_list | Een set tekens gevonden door het herkenningsalgoritme en gerangschikt in aflopende volgorde van waarschijnlijkheid. |
| recognition_text | Haalt het herkenningsresultaat op in één tekenreeks. |
| file_name | Volledig pad naar het bestand. |
| warnings | Haalt een lijst op van de waarschuwingsberichten die niet‑kritieke fouten beschrijven die tijdens de generatie zijn opgetreden. |
| serializable_image |  |
## Methods
| Naam | Beschrijving |
| :- | :- |
| save(full_file_name, save_format, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) | Slaat het document op als platte tekst, PDF of Microsoft Word‑document. |
| save(full_file_name, save_format, embedded_font_path, optimize_pdf) | Slaat het document op als platte tekst, PDF of Microsoft Word‑document. |
| save(full_file_name, save_format, optimize_pdf) | Slaat het document op als platte tekst, PDF of Microsoft Word‑document. |
| save(stream, save_format, optimize_pdf) | Slaat het document op als platte tekst, PDF of Microsoft Word‑document. |
| save(stream, save_format, apply_spelling_correction, language, dictionary_path) | Slaat het document op als platte tekst, PDF of Microsoft Word‑document. |
| get_spell_check_corrected_text(language, dictionary_path) | Corrigeert tekst (vervangt verkeerd gespelde woorden). |
| get_spell_check_error_list(language, dictionary_path) | Zoek de verkeerd gespelde woorden met voorgestelde spellingen voor een gegeven invoertekst. |
| get_json(is_readable) | Stel JSON‑string samen met herkenningsresultaten. |
| get_xml() | Stel XML‑string samen met herkenningsresultaten. |
| get_keywords() | Haalt trefwoorden op uit paspoort (Testmodus. Werkt alleen voor USA- en MADAGASCAR-paspoorten). |

### Zie ook

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

