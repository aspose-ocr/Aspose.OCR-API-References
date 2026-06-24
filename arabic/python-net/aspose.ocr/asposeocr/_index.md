---
title: "AsposeOcr"
second_title: "مرجع API لـ Aspose.OCR للبايثون عبر .NET"
description: 
type: docs
weight: 10
url: /ar/python-net/aspose.ocr/asposeocr/
---

## AsposeOcr class

واجهة برمجة التطبيقات الرئيسية لمكتبة Aspose OCR

يعرض نوع AsposeOcr الأعضاء التالية:
## المنشئات
| الاسم | الوصف |
| :- | :- |
| AsposeOcr() | ينشئ مثيلاً جديدًا من الفئة [AsposeOcr](/ocr/python-net/aspose.ocr/asposeocr/) .<br/>            مُنشئ فارغ. |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| set_debug_mode |  |
| set_debug_mode_save_directory |  |
## Methods
| الاسم | الوصف |
| :- | :- |
| recognize(images) | يتعرف على النص في الصور / المستندات.<br/>            يدعم GIF, PNG, JPEG, BMP, TIFF, JFIF, التدفق, الدليل, المصفوفات, الأرشيفات. |
| recognize(images, preset) |  |
| recognize(images, settings) | يتعرف على النص في الصور / المستندات.<br/>            يدعم GIF, PNG, JPEG, BMP, TIFF, JFIF, التدفق, الدليل, المصفوفات, الأرشيفات. |
| recognize_receipt(images) | يتعرف على النص في الإيصالات. |
| recognize_receipt(images, settings) | يتعرف على النص في الإيصالات. |
| recognize_invoice(images) | يتعرف على النص في الفواتير. |
| recognize_invoice(images, settings) | يتعرف على النص في الفواتير. |
| recognize_id_card(images) | يتعرف على النص في بطاقة الهوية. |
| recognize_id_card(images, settings) | يتعرف على النص في بطاقة الهوية. |
| recognize_car_plate(images) | يتعرف على النص في لوحة السيارة. |
| recognize_car_plate(images, settings) | يتعرف على النص في لوحة السيارة. |
| recognize_passport(images) | يتعرف على النص في جواز السفر. |
| recognize_passport(images, settings) | يتعرف على النص في جواز السفر. |
| recognize_lines(images) | يتعرف على الصور التي تحتوي على سطر واحد من النص.<br/>            يدعم GIF و PNG و JPEG و BMP و TIFF و JFIF، التدفق، المجلد، المصفوفات، الأرشيفات. |
| recognize_lines(images, settings) | يتعرف على الصور التي تحتوي على سطر واحد من النص.<br/>            يدعم GIF و PNG و JPEG و BMP و TIFF و JFIF، التدفق، المجلد، المصفوفات، الأرشيفات. |
| detect_rectangles(images) | يكشف عن مناطق النص في الصور.<br/>            يدعم GIF و PNG و JPEG و BMP و TIFF و JFIF، التدفق، المجلد، المصفوفات، الأرشيفات. |
| detect_rectangles(images, areas_type, detect_areas) | يكشف عن مناطق النص في الصور.<br/>            يدعم GIF و PNG و JPEG و BMP و TIFF و JFIF، التدفق، المجلد، المصفوفات، الأرشيفات. |
| recognize_characters(images) | يكشف عن الرموز في الصور.<br/>            يدعم GIF و PNG و JPEG و BMP و TIFF و JFIF، التدفق، المجلد، المصفوفات، الأرشيفات. |
| recognize_characters(images, detect_areas_mode, language) | يكشف عن الرموز في الصور.<br/>            يدعم GIF و PNG و JPEG و BMP و TIFF و JFIF، التدفق، المجلد، المصفوفات، الأرشيفات. |
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
| recognize_fast(images) | يتعرف على النص في الصور / المستندات.<br/>            يدعم GIF, PNG, JPEG, BMP, TIFF, JFIF, التدفق, الدليل, المصفوفات, الأرشيفات. |
| recognize_handwritten_text(images) | يتعرف على النص المكتوب يدويًا في الصور. |
| detect_document_layout(images) |  |
| recognize_formula(images, detect_areas) |  |
| recognize_formula_ai(images) |  |
| recognize_tables(images, language) |  |
| detect_tables(images) |  |
| calculate_skew(images) | يحسب زوايا الانحراف في الصور.<br/>            يدعم GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
| detect_defects(images, defect_type) | يحدد تلقائيًا المناطق المشكلة في الصورة التي يمكن أن تؤثر بشكل كبير على دقة OCR.<br/>            يدعم صور PNG, JPEG, BMP, TIFF, JFIF, و GIF المقدمة كملف أو تدفق أو مصفوفة بكسلات. يدعم التعرف الجماعي. |
| detect_languages(images) |  |
| image_has_text(full_path, text, settings, ignore_case, auto_skew) | تحقق مما إذا كانت الصورة تحتوي على الجزء النصي المقدم. |
| compare_image_texts(full_path1, full_path2, settings, ignore_case) | تحقق مما إذا كانت صورتان تحتويان على نفس النص. |
| image_text_diff(full_path1, full_path2, settings, ignore_case, auto_skew) | قارن النصوص في الصورتين وأرجع رقمًا يمثل مدى تشابههما (من 0 إلى 1). |
| correct_spelling(text, language, dictionary_path) | يصحح النص (يستبدل الكلمات المكتوبة بشكل خاطئ). |

### انظر أيضًا

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

