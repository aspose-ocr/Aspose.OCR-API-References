---
title: "AsposeOcr"
second_title: "Aspose.OCR för Python via .NET API-referens"
description: 
type: docs
weight: 10
url: /sv/python-net/aspose.ocr/asposeocr/
---

## AsposeOcr class

Huvud-API för Aspose OCR-biblioteket

Typen AsposeOcr exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| AsposeOcr() | Initierar en ny instans av klassen [AsposeOcr](/ocr/python-net/aspose.ocr/asposeocr/).<br/>            Tom konstruktor. |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| set_debug_mode |  |
| set_debug_mode_save_directory |  |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| recognize(images) | Identifierar text på bilder / dokument.<br/>            Stöder GIF, PNG, JPEG, BMP, TIFF, JFIF, ström, katalog, arrayer, arkiv. |
| recognize(images, preset) |  |
| recognize(images, settings) | Identifierar text på bilder / dokument.<br/>            Stöder GIF, PNG, JPEG, BMP, TIFF, JFIF, ström, katalog, arrayer, arkiv. |
| recognize_receipt(images) | Identifierar text på kvitton. |
| recognize_receipt(images, settings) | Identifierar text på kvitton. |
| recognize_invoice(images) | Identifierar text på fakturor. |
| recognize_invoice(images, settings) | Identifierar text på fakturor. |
| recognize_id_card(images) | Känner igen text på ID-kortet. |
| recognize_id_card(images, settings) | Känner igen text på ID-kortet. |
| recognize_car_plate(images) | Känner igen text på registreringsskylt. |
| recognize_car_plate(images, settings) | Känner igen text på registreringsskylt. |
| recognize_passport(images) | Känner igen text på passet. |
| recognize_passport(images, settings) | Känner igen text på passet. |
| recognize_lines(images) | Känner igen bilder som innehåller en enda textrad.<br/>            Stöder GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
| recognize_lines(images, settings) | Känner igen bilder som innehåller en enda textrad.<br/>            Stöder GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
| detect_rectangles(images) | Detekterar textområden i bilder.<br/>            Stöder GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
| detect_rectangles(images, areas_type, detect_areas) | Detekterar textområden i bilder.<br/>            Stöder GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
| recognize_characters(images) | Detekterar symboler i bilder.<br/>            Stöder GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
| recognize_characters(images, detect_areas_mode, language) | Detekterar symboler i bilder.<br/>            Stöder GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
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
| recognize_fast(images) | Identifierar text på bilder / dokument.<br/>            Stöder GIF, PNG, JPEG, BMP, TIFF, JFIF, ström, katalog, arrayer, arkiv. |
| recognize_handwritten_text(images) | Känner igen handskriven text på bilder. |
| detect_document_layout(images) |  |
| recognize_formula(images, detect_areas) |  |
| recognize_formula_ai(images) |  |
| recognize_tables(images, language) |  |
| detect_tables(images) |  |
| calculate_skew(images) | Beräknar snedvinklarna för en bild.<br/>            Stöder GIF, PNG, JPEG, BMP, TIFF, JFIF, ström, mapp, arrayer, arkiv. |
| detect_defects(images, defect_type) | Hitta automatiskt problematiska områden i en bild som kan påverka OCR‑noggrannheten avsevärt.<br/>            Stöder PNG, JPEG, BMP, TIFF, JFIF och GIF‑bilder som tillhandahålls som fil, ström eller pixelarray. Stöder massigenkänning. |
| detect_languages(images) |  |
| image_has_text(full_path, text, settings, ignore_case, auto_skew) | Kontrollera om bilden innehåller det angivna textfragmentet. |
| compare_image_texts(full_path1, full_path2, settings, ignore_case) | Kontrollera om två bilder innehåller samma text. |
| image_text_diff(full_path1, full_path2, settings, ignore_case, auto_skew) | Jämför texterna på de två bilderna och returnera ett tal som representerar hur lika de är (0 till 1). |
| correct_spelling(text, language, dictionary_path) | Korrigerar text (ersätter felstavade ord). |

### Se även

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

