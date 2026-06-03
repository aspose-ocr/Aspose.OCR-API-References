---
title: "RecognitionResult"
second_title: "مرجع API لـ Aspose.OCR للبايثون عبر .NET"
description: 
type: docs
weight: 290
url: /ar/python-net/aspose.ocr/recognitionresult/
---

## RecognitionResult class

نتائج التعرف على الصورة.<br/>            يحتوي على عناصر بمعلومات التعرف وطرق لتصدير النتائج.

يعرض نوع RecognitionResult الأعضاء التالية:


## الخصائص
| الاسم | الوصف |
| :- | :- |
| recognition_regions_result | يحصل على قائمة بنتائج التعرف مع قائمة بالمناطق (مستطيلات). |
| recognition_lines_result | يحصل على قائمة من نتائج التعرف مع قائمة من الصفوف (المستطيلات). |
| recognition_characters_list | مجموعة من الأحرف التي وجدها خوارزمية التعرف وتم ترتيبها بترتيب تنازلي حسب الاحتمال. |
| recognition_text | يحصل على نتيجة التعرف في سلسلة واحدة. |
| file_name | المسار الكامل للملف. |
| warnings | يحصل على قائمة رسائل التحذير التي تصف الأخطاء غير الحرجة التي ظهرت أثناء الإنشاء. |
| serializable_image |  |
## Methods
| الاسم | الوصف |
| :- | :- |
| save(full_file_name, save_format, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) | يحفظ المستند كنص عادي أو PDF أو مستند Microsoft Word. |
| save(full_file_name, save_format, embedded_font_path, optimize_pdf) | يحفظ المستند كنص عادي أو PDF أو مستند Microsoft Word. |
| save(full_file_name, save_format, optimize_pdf) | يحفظ المستند كنص عادي أو PDF أو مستند Microsoft Word. |
| save(stream, save_format, optimize_pdf) | يحفظ المستند كنص عادي أو PDF أو مستند Microsoft Word. |
| save(stream, save_format, apply_spelling_correction, language, dictionary_path) | يحفظ المستند كنص عادي أو PDF أو مستند Microsoft Word. |
| get_spell_check_corrected_text(language, dictionary_path) | يصحح النص (يستبدل الكلمات المكتوبة بشكل خاطئ). |
| get_spell_check_error_list(language, dictionary_path) | ابحث عن الكلمات المكتوبة خطأ مع الاقتراحات الإملائية لنص مدخل معين. |
| get_json(is_readable) | كوّن سلسلة JSON مع نتائج التعرف. |
| get_xml() | كوّن سلسلة XML مع نتائج التعرف. |
| get_keywords() | احصل على الكلمات المفتاحية من جواز السفر (وضع الاختبار. يعمل فقط لجوازات السفر الأمريكية ومدغشقر). |

### انظر أيضاً

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

