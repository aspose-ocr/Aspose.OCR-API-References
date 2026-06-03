---
title: "RecognitionSettings"
second_title: "مرجع API لـ Aspose.OCR للبايثون عبر .NET"
description: 
type: docs
weight: 330
url: /ar/python-net/aspose.ocr/recognitionsettings/
---

## RecognitionSettings class

إعدادات التعرف على الصورة.<br/>            يحتوي على عناصر تسمح بتخصيص عملية التعرف.

نوع RecognitionSettings يكشف عن الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| RecognitionSettings() | ينشئ مثيلاً جديداً لـ |
| RecognitionSettings(language, recognition_areas, recognize_single_line) | يقوم بإنشاء نسخة جديدة من فئة RecognitionSettings |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| recognize_vertical_lines |  |
| threads_count | يحصل أو يضبط عدد الخيوط للمعالجة. |
| language | يحصل أو يضبط اللغة المستخدمة في OCR. |
| ignored_symbols | يضبط القائمة السوداء لرموز التعرف. |
| allowed_symbols | يضبط الأحرف المسموح بها باستخدام خاصية alphabet. |
| allowed_characters | مجموعة الأحرف المسموح بها. تحدد نوع الأحرف المسموح بها لنتيجة التعرف. |
| automatic_color_inversion | اكتشاف الصور التي تحتوي على نص أبيض على خلفية داكنة/سوداء واختيار خوارزمية OCR خاصة لها تلقائياً. |
| recognition_areas | يحصل أو يعيّن قائمة مناطق النص للمعالجة. |
| recognize_single_line | يضبط التعرف على الصور ذات السطر الواحد. <br/>            معطل (false) بشكل افتراضي. <br/>            يعطل جميع خطوات المعالجة المرتبطة بالتقسيم إلى أسطر. <br/>            اضبط هذه المعلمة إلى true إذا كانت صورتك تحتوي على سطر واحد فقط. يعطل إعدادات RecognitionAreas، لذا سيتم تجاهل جميع إعدادات المناطق. |
| language_detection_level |  |
| lines_filtration | يسمح بالتعرف على النص في الجداول (المناطق المحاطة بالخطوط). |
| detect_areas_mode | يسمح باختيار الوضع الأمثل لمناطق نوع المستند: مستند، صورة، نص عادي، عمود، صورة. |
| upscale_small_font | يسمح لك باستخدام خوارزميات إضافية مخصصة للتعرف على الخطوط الصغيرة.<br/>            مفيد للصور التي تحتوي على أحرف صغيرة الحجم. |

### انظر أيضاً

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

