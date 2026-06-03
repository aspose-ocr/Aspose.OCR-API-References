---
title: "AsposeOcr"
second_title: "Справочник API Aspose.OCR для Python через .NET"
description: 
type: docs
weight: 10
url: /ru/python-net/aspose.ocr/asposeocr/
---

## AsposeOcr class

Основной API для библиотеки Aspose OCR

Тип AsposeOcr раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| AsposeOcr() | Инициализирует новый экземпляр класса [AsposeOcr](/ocr/python-net/aspose.ocr/asposeocr/).<br/>            Пустой конструктор. |
## Свойства
| Имя | Описание |
| :- | :- |
| set_debug_mode |  |
| set_debug_mode_save_directory |  |
## Методы
| Имя | Описание |
| :- | :- |
| recognize(images) | Распознаёт текст на изображениях / документах.<br/>            Поддерживает GIF, PNG, JPEG, BMP, TIFF, JFIF, поток, каталог, массивы, архивы. |
| recognize(images, preset) |  |
| recognize(images, settings) | Распознаёт текст на изображениях / документах.<br/>            Поддерживает GIF, PNG, JPEG, BMP, TIFF, JFIF, поток, каталог, массивы, архивы. |
| recognize_receipt(images) | Распознаёт текст на чеках. |
| recognize_receipt(images, settings) | Распознаёт текст на чеках. |
| recognize_invoice(images) | Распознаёт текст на счетах-фактурах. |
| recognize_invoice(images, settings) | Распознаёт текст на счетах-фактурах. |
| recognize_id_card(images) | Распознаёт текст на удостоверении личности. |
| recognize_id_card(images, settings) | Распознаёт текст на удостоверении личности. |
| recognize_car_plate(images) | Распознаёт текст на автомобильном номере. |
| recognize_car_plate(images, settings) | Распознаёт текст на автомобильном номере. |
| recognize_passport(images) | Распознаёт текст в паспорте. |
| recognize_passport(images, settings) | Распознаёт текст в паспорте. |
| recognize_lines(images) | Распознаёт изображения, содержащие одну строку текста.<br/>            Поддерживает GIF, PNG, JPEG, BMP, TIFF, JFIF, поток, папку, массивы, архивы. |
| recognize_lines(images, settings) | Распознаёт изображения, содержащие одну строку текста.<br/>            Поддерживает GIF, PNG, JPEG, BMP, TIFF, JFIF, поток, папку, массивы, архивы. |
| detect_rectangles(images) | Обнаруживает текстовые области на изображениях.<br/>            Поддерживает GIF, PNG, JPEG, BMP, TIFF, JFIF, поток, папку, массивы, архивы. |
| detect_rectangles(images, areas_type, detect_areas) | Обнаруживает текстовые области на изображениях.<br/>            Поддерживает GIF, PNG, JPEG, BMP, TIFF, JFIF, поток, папку, массивы, архивы. |
| recognize_characters(images) | Обнаруживает символы на изображениях.<br/>            Поддерживает GIF, PNG, JPEG, BMP, TIFF, JFIF, поток, папку, массивы, архивы. |
| recognize_characters(images, detect_areas_mode, language) | Обнаруживает символы на изображениях.<br/>            Поддерживает GIF, PNG, JPEG, BMP, TIFF, JFIF, поток, папку, массивы, архивы. |
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
| recognize_fast(images) | Распознаёт текст на изображениях / документах.<br/>            Поддерживает GIF, PNG, JPEG, BMP, TIFF, JFIF, поток, каталог, массивы, архивы. |
| recognize_handwritten_text(images) | Распознаёт рукописный текст на изображениях. |
| detect_document_layout(images) |  |
| recognize_formula(images, detect_areas) |  |
| recognize_formula_ai(images) |  |
| recognize_tables(images, language) |  |
| detect_tables(images) |  |
| calculate_skew(images) | Вычисляет углы наклона изображений.<br/>            Поддерживает GIF, PNG, JPEG, BMP, TIFF, JFIF, поток, папку, массивы, архивы. |
| detect_defects(images, defect_type) | Автоматически находит проблемные области изображения, которые могут существенно влиять на точность OCR.<br/>            Поддерживает PNG, JPEG, BMP, TIFF, JFIF и GIF изображения, предоставляемые как файл, поток или массив пикселей. Поддерживает пакетное распознавание. |
| detect_languages(images) |  |
| image_has_text(full_path, text, settings, ignore_case, auto_skew) | Проверьте, содержит ли изображение предоставленный фрагмент текста. |
| compare_image_texts(full_path1, full_path2, settings, ignore_case) | Проверьте, содержат ли два изображения один и тот же текст. |
| image_text_diff(full_path1, full_path2, settings, ignore_case, auto_skew) | Сравните тексты на двух изображениях и верните число, представляющее степень их схожести (от 0 до 1). |
| correct_spelling(text, language, dictionary_path) | Исправляет текст (заменяет ошибочно написанные слова). |

### См. также

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

