---
title: "AsposeOcr"
second_title: "Aspose.OCR für Python via .NET API-Referenz"
description: 
type: docs
weight: 10
url: /de/python-net/aspose.ocr/asposeocr/
---

## AsposeOcr class

Haupt-API für die Aspose OCR-Bibliothek

Der AsposeOcr-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| AsposeOcr() | Initialisiert eine neue Instanz der [AsposeOcr](/ocr/python-net/aspose.ocr/asposeocr/) Klasse.<br/>            Leerer Konstruktor. |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| set_debug_mode |  |
| set_debug_mode_save_directory |  |
## Methoden
| Name | Beschreibung |
| :- | :- |
| recognize(images) | Erkennt Text in Bildern / Dokumenten.<br/>            Unterstützt GIF, PNG, JPEG, BMP, TIFF, JFIF, Stream, Verzeichnis, Arrays, Archive. |
| recognize(images, preset) |  |
| recognize(images, settings) | Erkennt Text in Bildern / Dokumenten.<br/>            Unterstützt GIF, PNG, JPEG, BMP, TIFF, JFIF, Stream, Verzeichnis, Arrays, Archive. |
| recognize_receipt(images) | Erkennt Text auf Quittungen. |
| recognize_receipt(images, settings) | Erkennt Text auf Quittungen. |
| recognize_invoice(images) | Erkennt Text auf Rechnungen. |
| recognize_invoice(images, settings) | Erkennt Text auf Rechnungen. |
| recognize_id_card(images) | Erkennt Text auf dem Personalausweis. |
| recognize_id_card(images, settings) | Erkennt Text auf dem Personalausweis. |
| recognize_car_plate(images) | Erkennt Text auf dem Kfz-Kennzeichen. |
| recognize_car_plate(images, settings) | Erkennt Text auf dem Kfz-Kennzeichen. |
| recognize_passport(images) | Erkennt Text im Reisepass. |
| recognize_passport(images, settings) | Erkennt Text im Reisepass. |
| recognize_lines(images) | Erkennt Bilder, die eine einzelne Textzeile enthalten.<br/>            Unterstützt GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, Ordner, Arrays, Archive. |
| recognize_lines(images, settings) | Erkennt Bilder, die eine einzelne Textzeile enthalten.<br/>            Unterstützt GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, Ordner, Arrays, Archive. |
| detect_rectangles(images) | Erkennt Textbereiche in Bildern.<br/>            Unterstützt GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, Ordner, Arrays, Archive. |
| detect_rectangles(images, areas_type, detect_areas) | Erkennt Textbereiche in Bildern.<br/>            Unterstützt GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, Ordner, Arrays, Archive. |
| recognize_characters(images) | Erkennt Symbole in Bildern.<br/>            Unterstützt GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, Ordner, Arrays, Archive. |
| recognize_characters(images, detect_areas_mode, language) | Erkennt Symbole in Bildern.<br/>            Unterstützt GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, Ordner, Arrays, Archive. |
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
| recognize_fast(images) | Erkennt Text in Bildern / Dokumenten.<br/>            Unterstützt GIF, PNG, JPEG, BMP, TIFF, JFIF, Stream, Verzeichnis, Arrays, Archive. |
| recognize_handwritten_text(images) | Erkennt handschriftlichen Text auf Bildern. |
| detect_document_layout(images) |  |
| recognize_formula(images, detect_areas) |  |
| recognize_formula_ai(images) |  |
| recognize_tables(images, language) |  |
| detect_tables(images) |  |
| calculate_skew(images) | Berechnet die Schrägwinkel von Bildern.<br/>            Unterstützt GIF, PNG, JPEG, BMP, TIFF, JFIF, Stream, Ordner, Arrays, Archive. |
| detect_defects(images, defect_type) | Findet automatisch problematische Bereiche eines Bildes, die die OCR‑Genauigkeit erheblich beeinträchtigen können.<br/>            Unterstützt PNG-, JPEG-, BMP-, TIFF-, JFIF- und GIF‑Bilder, die als Datei, Stream oder Pixel‑Array bereitgestellt werden. Unterstützt die Massen­erkennung. |
| detect_languages(images) |  |
| image_has_text(full_path, text, settings, ignore_case, auto_skew) | Prüft, ob das Bild das bereitgestellte Textfragment enthält. |
| compare_image_texts(full_path1, full_path2, settings, ignore_case) | Prüft, ob zwei Bilder denselben Text enthalten. |
| image_text_diff(full_path1, full_path2, settings, ignore_case, auto_skew) | Vergleicht die Texte der beiden Bilder und gibt eine Zahl zurück, die angibt, wie ähnlich sie sind (0 bis 1). |
| correct_spelling(text, language, dictionary_path) | Korrigiert Text (ersetzt falsch geschriebene Wörter). |

### Siehe auch

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

