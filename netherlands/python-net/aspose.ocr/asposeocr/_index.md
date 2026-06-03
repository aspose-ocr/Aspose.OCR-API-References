---
title: "AsposeOcr"
second_title: "Aspose.OCR voor Python via .NET API-referentie"
description: 
type: docs
weight: 10
url: /nl/python-net/aspose.ocr/asposeocr/
---

## AsposeOcr class

Hoofd-API voor Aspose OCR-bibliotheek

Het AsposeOcr-type geeft de volgende leden weer:
## Constructors
| Naam | Beschrijving |
| :- | :- |
| AsposeOcr() | Initialiseert een nieuw exemplaar van de [AsposeOcr](/ocr/python-net/aspose.ocr/asposeocr/) klasse.<br/>            Lege constructor. |
## Eigenschappen
| Naam | Beschrijving |
| :- | :- |
| set_debug_mode |  |
| set_debug_mode_save_directory |  |
## Methods
| Naam | Beschrijving |
| :- | :- |
| recognize(images) | Herken tekst op afbeeldingen / documenten.<br/>            Ondersteunt GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, map, arrays, archieven. |
| recognize(images, preset) |  |
| recognize(images, settings) | Herken tekst op afbeeldingen / documenten.<br/>            Ondersteunt GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, map, arrays, archieven. |
| recognize_receipt(images) | Herken tekst op bonnen. |
| recognize_receipt(images, settings) | Herken tekst op bonnen. |
| recognize_invoice(images) | Herken tekst op facturen. |
| recognize_invoice(images, settings) | Herken tekst op facturen. |
| recognize_id_card(images) | Herken tekst op ID-kaart. |
| recognize_id_card(images, settings) | Herken tekst op ID-kaart. |
| recognize_car_plate(images) | Herken tekst op kentekenplaat. |
| recognize_car_plate(images, settings) | Herken tekst op kentekenplaat. |
| recognize_passport(images) | Herken tekst op paspoort. |
| recognize_passport(images, settings) | Herken tekst op paspoort. |
| recognize_lines(images) | Herken afbeeldingen die een enkele regel tekst bevatten.<br/>            Ondersteunt GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
| recognize_lines(images, settings) | Herken afbeeldingen die een enkele regel tekst bevatten.<br/>            Ondersteunt GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
| detect_rectangles(images) | Detecteert tekstgebieden op afbeeldingen.<br/>            Ondersteunt GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
| detect_rectangles(images, areas_type, detect_areas) | Detecteert tekstgebieden op afbeeldingen.<br/>            Ondersteunt GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
| recognize_characters(images) | Detecteert symbolen op afbeeldingen.<br/>            Ondersteunt GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
| recognize_characters(images, detect_areas_mode, language) | Detecteert symbolen op afbeeldingen.<br/>            Ondersteunt GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
| save_multipage_document(full_file_name, save_format, results, embedded_font_path, optimize_pdf) |  |
| save_multipage_document(full_file_name, save_format, results, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) |  |
| save_multipage_document(full_file_name, save_format, results, optimize_pdf) |  |
| save_multipage_document(full_file_name, save_format, results) |  |
| save_multipage_document(stream, save_format, results) |  |
| save_multipage_document(stream, save_format, results, optimize_pdf) |  |
| save_multipage_document(stream, save_format, results, embedded_font_path) |  |
| save_multipage_document(stream, save_format, results, embedded_font_path, optimize_pdf) |  |
| save_multipage_document(stream, save_format, results, apply_spelling_correction, language, dictionary_path, embedded_font_path) |  |
| save_multipage_document(stream, save_format, results, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) |  |
| recognize_fast(images) | Herken tekst op afbeeldingen / documenten.<br/>            Ondersteunt GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, map, arrays, archieven. |
| recognize_handwritten_text(images) | Herkent handgeschreven tekst op afbeeldingen. |
| detect_document_layout(images) |  |
| recognize_formula(images, detect_areas) |  |
| recognize_formula_ai(images) |  |
| recognize_tables(images, language) |  |
| detect_tables(images) |  |
| calculate_skew(images) | Berekent de scheefstandhoeken van een afbeelding.<br/>            Ondersteunt GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, map, arrays, archieven. |
| detect_defects(images, defect_type) | Zoek automatisch problematische gebieden in een afbeelding die de nauwkeurigheid van OCR aanzienlijk kunnen beïnvloeden.<br/>            Ondersteunt PNG, JPEG, BMP, TIFF, JFIF, en GIF-afbeeldingen die worden geleverd als bestand, stream of pixelarray. Ondersteunt bulkherkenning. |
| detect_languages(images) |  |
| image_has_text(full_path, text, settings, ignore_case, auto_skew) | Controleer of de afbeelding het opgegeven tekstfragment bevat. |
| compare_image_texts(full_path1, full_path2, settings, ignore_case) | Controleer of twee afbeeldingen dezelfde tekst bevatten. |
| image_text_diff(full_path1, full_path2, settings, ignore_case, auto_skew) | Vergelijk de teksten op de twee afbeeldingen en retourneer een getal dat aangeeft hoe vergelijkbaar ze zijn (0 tot 1). |
| correct_spelling(text, language, dictionary_path) | Corrigeert tekst (vervangt verkeerd gespelde woorden). |

### Zie ook

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

