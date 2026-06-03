---
title: "AsposeOcr"
second_title: "Aspose.OCR Python için .NET API Referansı"
description: 
type: docs
weight: 10
url: /tr/python-net/aspose.ocr/asposeocr/
---

## AsposeOcr class

Aspose OCR kitaplığı için ana API

AsposeOcr türü aşağıdaki üyeleri gösterir:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| AsposeOcr() | Yeni bir [AsposeOcr](/ocr/python-net/aspose.ocr/asposeocr/) sınıf örneği başlatır.<br/>            Boş kurucu. |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| set_debug_mode |  |
| set_debug_mode_save_directory |  |
## Methods
| Ad | Açıklama |
| :- | :- |
| recognize(images) | Görüntüler / belgeler üzerindeki metni tanır.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, akış, dizin, diziler, arşivler desteklenir. |
| recognize(images, preset) |  |
| recognize(images, settings) | Görüntüler / belgeler üzerindeki metni tanır.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, akış, dizin, diziler, arşivler desteklenir. |
| recognize_receipt(images) | Fişlerdeki metni tanır. |
| recognize_receipt(images, settings) | Fişlerdeki metni tanır. |
| recognize_invoice(images) | Faturalardaki metni tanır. |
| recognize_invoice(images, settings) | Faturalardaki metni tanır. |
| recognize_id_card(images) | Kimlik kartındaki metni tanır. |
| recognize_id_card(images, settings) | Kimlik kartındaki metni tanır. |
| recognize_car_plate(images) | Araç plakasındaki metni tanır. |
| recognize_car_plate(images, settings) | Araç plakasındaki metni tanır. |
| recognize_passport(images) | Pasaporttaki metni tanır. |
| recognize_passport(images, settings) | Pasaporttaki metni tanır. |
| recognize_lines(images) | Tek satır metin içeren görüntüleri tanır.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, akış, klasör, diziler, arşivler desteklenir. |
| recognize_lines(images, settings) | Tek satır metin içeren görüntüleri tanır.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, akış, klasör, diziler, arşivler desteklenir. |
| detect_rectangles(images) | Görüntülerdeki metin alanlarını algılar.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, akış, klasör, diziler, arşivler desteklenir. |
| detect_rectangles(images, areas_type, detect_areas) | Görüntülerdeki metin alanlarını algılar.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, akış, klasör, diziler, arşivler desteklenir. |
| recognize_characters(images) | Görüntülerdeki sembolleri algılar.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, akış, klasör, diziler, arşivler desteklenir. |
| recognize_characters(images, detect_areas_mode, language) | Görüntülerdeki sembolleri algılar.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, akış, klasör, diziler, arşivler desteklenir. |
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
| recognize_fast(images) | Görüntüler / belgeler üzerindeki metni tanır.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, akış, dizin, diziler, arşivler desteklenir. |
| recognize_handwritten_text(images) | Görüntülerde el yazısı metni tanır. |
| detect_document_layout(images) |  |
| recognize_formula(images, detect_areas) |  |
| recognize_formula_ai(images) |  |
| recognize_tables(images, language) |  |
| detect_tables(images) |  |
| calculate_skew(images) | Bir görüntünün eğim açılarını hesaplar.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, akış, klasör, diziler, arşivler desteklenir. |
| detect_defects(images, defect_type) | Bir görüntünün OCR doğruluğunu önemli ölçüde etkileyebilecek sorunlu alanları otomatik olarak bulur.<br/>            Dosya, akış veya piksel dizisi olarak sağlanan PNG, JPEG, BMP, TIFF, JFIF ve GIF görüntüleri desteklenir. Toplu tanıma desteklenir. |
| detect_languages(images) |  |
| image_has_text(full_path, text, settings, ignore_case, auto_skew) | Görüntünün sağlanan metin parçacığını içerip içermediğini kontrol eder. |
| compare_image_texts(full_path1, full_path2, settings, ignore_case) | İki görüntünün aynı metni içerip içermediğini kontrol eder. |
| image_text_diff(full_path1, full_path2, settings, ignore_case, auto_skew) | İki görüntüdeki metinleri karşılaştırır ve benzerliklerini (0 ile 1 arasında) temsil eden bir sayı döndürür. |
| correct_spelling(text, language, dictionary_path) | Metni düzeltir (yanlış yazılmış kelimeleri değiştirir). |

### Ayrıca Bakınız

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

