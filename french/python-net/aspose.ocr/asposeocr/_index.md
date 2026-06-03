---
title: "AsposeOcr"
second_title: "Référence de l'API Aspose.OCR pour Python via .NET"
description: 
type: docs
weight: 10
url: /fr/python-net/aspose.ocr/asposeocr/
---

## AsposeOcr class

API principale pour la bibliothèque Aspose OCR

Le type AsposeOcr expose les membres suivants :
## Constructors
| Name | Description |
| :- | :- |
| AsposeOcr() | Initialise une nouvelle instance de la classe [AsposeOcr](/ocr/python-net/aspose.ocr/asposeocr/).<br/>            Constructeur vide. |
## Properties
| Name | Description |
| :- | :- |
| set_debug_mode |  |
| set_debug_mode_save_directory |  |
## Methods
| Name | Description |
| :- | :- |
| recognize(images) | Reconnaît le texte sur les images / documents.<br/>            Prend en charge GIF, PNG, JPEG, BMP, TIFF, JFIF, flux, répertoire, tableaux, archives. |
| recognize(images, preset) |  |
| recognize(images, settings) | Reconnaît le texte sur les images / documents.<br/>            Prend en charge GIF, PNG, JPEG, BMP, TIFF, JFIF, flux, répertoire, tableaux, archives. |
| recognize_receipt(images) | Reconnaît le texte sur les reçus. |
| recognize_receipt(images, settings) | Reconnaît le texte sur les reçus. |
| recognize_invoice(images) | Reconnaît le texte sur les factures. |
| recognize_invoice(images, settings) | Reconnaît le texte sur les factures. |
| recognize_id_card(images) | Reconnaît le texte sur la carte d'identité. |
| recognize_id_card(images, settings) | Reconnaît le texte sur la carte d'identité. |
| recognize_car_plate(images) | Reconnaît le texte sur la plaque d'immatriculation. |
| recognize_car_plate(images, settings) | Reconnaît le texte sur la plaque d'immatriculation. |
| recognize_passport(images) | Reconnaît le texte sur le passeport. |
| recognize_passport(images, settings) | Reconnaît le texte sur le passeport. |
| recognize_lines(images) | Reconnaît les images contenant une seule ligne de texte.<br/>            Prend en charge GIF, PNG, JPEG, BMP, TIFF, JFIF, flux, dossier, tableaux, archives. |
| recognize_lines(images, settings) | Reconnaît les images contenant une seule ligne de texte.<br/>            Prend en charge GIF, PNG, JPEG, BMP, TIFF, JFIF, flux, dossier, tableaux, archives. |
| detect_rectangles(images) | Détecte les zones de texte sur les images.<br/>            Prend en charge GIF, PNG, JPEG, BMP, TIFF, JFIF, flux, dossier, tableaux, archives. |
| detect_rectangles(images, areas_type, detect_areas) | Détecte les zones de texte sur les images.<br/>            Prend en charge GIF, PNG, JPEG, BMP, TIFF, JFIF, flux, dossier, tableaux, archives. |
| recognize_characters(images) | Détecte les symboles sur les images.<br/>            Prend en charge GIF, PNG, JPEG, BMP, TIFF, JFIF, flux, dossier, tableaux, archives. |
| recognize_characters(images, detect_areas_mode, language) | Détecte les symboles sur les images.<br/>            Prend en charge GIF, PNG, JPEG, BMP, TIFF, JFIF, flux, dossier, tableaux, archives. |
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
| recognize_fast(images) | Reconnaît le texte sur les images / documents.<br/>            Prend en charge GIF, PNG, JPEG, BMP, TIFF, JFIF, flux, répertoire, tableaux, archives. |
| recognize_handwritten_text(images) | Reconnaît le texte manuscrit sur les images. |
| detect_document_layout(images) |  |
| recognize_formula(images, detect_areas) |  |
| recognize_formula_ai(images) |  |
| recognize_tables(images, language) |  |
| detect_tables(images) |  |
| calculate_skew(images) | Calcule les angles d'inclinaison d'une image.<br/>            Prend en charge GIF, PNG, JPEG, BMP, TIFF, JFIF, flux, dossier, tableaux, archives. |
| detect_defects(images, defect_type) | Trouve automatiquement les zones problématiques d'une image pouvant affecter significativement la précision de l'OCR.<br/>            Prend en charge les images PNG, JPEG, BMP, TIFF, JFIF et GIF fournies sous forme de fichier, flux ou tableau de pixels. Prend en charge la reconnaissance en masse. |
| detect_languages(images) |  |
| image_has_text(full_path, text, settings, ignore_case, auto_skew) | Vérifie si l'image contient le fragment de texte fourni. |
| compare_image_texts(full_path1, full_path2, settings, ignore_case) | Vérifie si deux images contiennent le même texte. |
| image_text_diff(full_path1, full_path2, settings, ignore_case, auto_skew) | Compare les textes des deux images et renvoie un nombre représentant leur degré de similarité (de 0 à 1). |
| correct_spelling(text, language, dictionary_path) | Corrige le texte (remplace les mots mal orthographiés). |

### See Also

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

