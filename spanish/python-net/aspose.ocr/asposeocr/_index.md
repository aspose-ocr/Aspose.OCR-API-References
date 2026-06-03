---
title: "AsposeOcr"
second_title: "Aspose.OCR para Python a través de .NET Referencia de API"
description: 
type: docs
weight: 10
url: /es/python-net/aspose.ocr/asposeocr/
---

## AsposeOcr class

API principal de la biblioteca Aspose OCR

El tipo AsposeOcr expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| AsposeOcr() | Inicializa una nueva instancia de la clase [AsposeOcr](/ocr/python-net/aspose.ocr/asposeocr/).<br/>            Constructor vacío. |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| set_debug_mode |  |
| set_debug_mode_save_directory |  |
## Methods
| Nombre | Descripción |
| :- | :- |
| recognize(images) | Reconoce texto en imágenes / documentos.<br/>            Soporta GIF, PNG, JPEG, BMP, TIFF, JFIF, flujo, directorio, matrices, archivos comprimidos. |
| recognize(images, preset) |  |
| recognize(images, settings) | Reconoce texto en imágenes / documentos.<br/>            Soporta GIF, PNG, JPEG, BMP, TIFF, JFIF, flujo, directorio, matrices, archivos comprimidos. |
| recognize_receipt(images) | Reconoce texto en recibos. |
| recognize_receipt(images, settings) | Reconoce texto en recibos. |
| recognize_invoice(images) | Reconoce texto en facturas. |
| recognize_invoice(images, settings) | Reconoce texto en facturas. |
| recognize_id_card(images) | Reconoce texto en la tarjeta de identificación. |
| recognize_id_card(images, settings) | Reconoce texto en la tarjeta de identificación. |
| recognize_car_plate(images) | Reconoce texto en la placa del coche. |
| recognize_car_plate(images, settings) | Reconoce texto en la placa del coche. |
| recognize_passport(images) | Reconoce texto en el pasaporte. |
| recognize_passport(images, settings) | Reconoce texto en el pasaporte. |
| recognize_lines(images) | Reconoce imágenes que contienen una sola línea de texto.<br/>            Soporta GIF, PNG, JPEG, BMP, TIFF, JFIF, flujo, carpeta, matrices, archivos. |
| recognize_lines(images, settings) | Reconoce imágenes que contienen una sola línea de texto.<br/>            Soporta GIF, PNG, JPEG, BMP, TIFF, JFIF, flujo, carpeta, matrices, archivos. |
| detect_rectangles(images) | Detecta áreas de texto en imágenes.<br/>            Soporta GIF, PNG, JPEG, BMP, TIFF, JFIF, flujo, carpeta, matrices, archivos. |
| detect_rectangles(images, areas_type, detect_areas) | Detecta áreas de texto en imágenes.<br/>            Soporta GIF, PNG, JPEG, BMP, TIFF, JFIF, flujo, carpeta, matrices, archivos. |
| recognize_characters(images) | Detecta símbolos en imágenes.<br/>            Soporta GIF, PNG, JPEG, BMP, TIFF, JFIF, flujo, carpeta, matrices, archivos. |
| recognize_characters(images, detect_areas_mode, language) | Detecta símbolos en imágenes.<br/>            Soporta GIF, PNG, JPEG, BMP, TIFF, JFIF, flujo, carpeta, matrices, archivos. |
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
| recognize_fast(images) | Reconoce texto en imágenes / documentos.<br/>            Soporta GIF, PNG, JPEG, BMP, TIFF, JFIF, flujo, directorio, matrices, archivos comprimidos. |
| recognize_handwritten_text(images) | Reconoce texto manuscrito en imágenes. |
| detect_document_layout(images) |  |
| recognize_formula(images, detect_areas) |  |
| recognize_formula_ai(images) |  |
| recognize_tables(images, language) |  |
| detect_tables(images) |  |
| calculate_skew(images) | Calcula los ángulos de sesgo de una imagen.<br/>            Soporta GIF, PNG, JPEG, BMP, TIFF, JFIF, flujo, carpeta, matrices, archivos. |
| detect_defects(images, defect_type) | Encuentra automáticamente áreas problemáticas de una imagen que pueden afectar significativamente la precisión del OCR.<br/>            Soporta imágenes PNG, JPEG, BMP, TIFF, JFIF y GIF proporcionadas como archivo, flujo o matriz de píxeles. Soporta reconocimiento masivo. |
| detect_languages(images) |  |
| image_has_text(full_path, text, settings, ignore_case, auto_skew) | Verifica si la imagen contiene el fragmento de texto proporcionado. |
| compare_image_texts(full_path1, full_path2, settings, ignore_case) | Verifica si dos imágenes contienen el mismo texto. |
| image_text_diff(full_path1, full_path2, settings, ignore_case, auto_skew) | Compara los textos de las dos imágenes y devuelve un número que representa cuán similares son (0 a 1). |
| correct_spelling(text, language, dictionary_path) | Corrige texto (reemplaza palabras mal escritas). |

### Ver también

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

