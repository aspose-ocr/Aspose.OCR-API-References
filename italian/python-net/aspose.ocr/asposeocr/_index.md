---
title: "AsposeOcr"
second_title: "Riferimento API di Aspose.OCR per Python via .NET"
description: 
type: docs
weight: 10
url: /it/python-net/aspose.ocr/asposeocr/
---

## AsposeOcr class

API principale per la libreria Aspose OCR

Il tipo AsposeOcr espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| AsposeOcr() | Inizializza una nuova istanza della classe [AsposeOcr](/ocr/python-net/aspose.ocr/asposeocr/).<br/>            Costruttore vuoto. |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| set_debug_mode |  |
| set_debug_mode_save_directory |  |
## Methods
| Nome | Descrizione |
| :- | :- |
| recognize(images) | Riconosce il testo su immagini / documenti.<br/>            Supporta GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, directory, array, archivi. |
| recognize(images, preset) |  |
| recognize(images, settings) | Riconosce il testo su immagini / documenti.<br/>            Supporta GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, directory, array, archivi. |
| recognize_receipt(images) | Riconosce il testo sulle ricevute. |
| recognize_receipt(images, settings) | Riconosce il testo sulle ricevute. |
| recognize_invoice(images) | Riconosce il testo sulle fatture. |
| recognize_invoice(images, settings) | Riconosce il testo sulle fatture. |
| recognize_id_card(images) | Riconosce il testo sulla carta d'identità. |
| recognize_id_card(images, settings) | Riconosce il testo sulla carta d'identità. |
| recognize_car_plate(images) | Riconosce il testo sulla targa dell'auto. |
| recognize_car_plate(images, settings) | Riconosce il testo sulla targa dell'auto. |
| recognize_passport(images) | Riconosce il testo sul passaporto. |
| recognize_passport(images, settings) | Riconosce il testo sul passaporto. |
| recognize_lines(images) | Riconosce le immagini che contengono una singola riga di testo.<br/>            Supporta GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, cartella, array, archivi. |
| recognize_lines(images, settings) | Riconosce le immagini che contengono una singola riga di testo.<br/>            Supporta GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, cartella, array, archivi. |
| detect_rectangles(images) | Rileva le aree di testo nelle immagini.<br/>            Supporta GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, cartella, array, archivi. |
| detect_rectangles(images, areas_type, detect_areas) | Rileva le aree di testo nelle immagini.<br/>            Supporta GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, cartella, array, archivi. |
| recognize_characters(images) | Rileva i simboli nelle immagini.<br/>            Supporta GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, cartella, array, archivi. |
| recognize_characters(images, detect_areas_mode, language) | Rileva i simboli nelle immagini.<br/>            Supporta GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, cartella, array, archivi. |
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
| recognize_fast(images) | Riconosce il testo su immagini / documenti.<br/>            Supporta GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, directory, array, archivi. |
| recognize_handwritten_text(images) | Riconosce il testo scritto a mano nelle immagini. |
| detect_document_layout(images) |  |
| recognize_formula(images, detect_areas) |  |
| recognize_formula_ai(images) |  |
| recognize_tables(images, language) |  |
| detect_tables(images) |  |
| calculate_skew(images) | Calcola gli angoli di inclinazione di un'immagine.<br/>            Supporta GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, cartella, array, archivi. |
| detect_defects(images, defect_type) | Trova automaticamente le aree problematiche di un'immagine che possono influire significativamente sulla precisione dell'OCR.<br/>            Supporta immagini PNG, JPEG, BMP, TIFF, JFIF e GIF fornite come file, stream o array di pixel. Supporta il riconoscimento in blocco. |
| detect_languages(images) |  |
| image_has_text(full_path, text, settings, ignore_case, auto_skew) | Verifica se l'immagine contiene il frammento di testo fornito. |
| compare_image_texts(full_path1, full_path2, settings, ignore_case) | Verifica se due immagini contengono lo stesso testo. |
| image_text_diff(full_path1, full_path2, settings, ignore_case, auto_skew) | Confronta i testi delle due immagini e restituisce un numero che rappresenta quanto sono simili (da 0 a 1). |
| correct_spelling(text, language, dictionary_path) | Corregge il testo (sostituisce le parole errate). |

### Vedi anche

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

