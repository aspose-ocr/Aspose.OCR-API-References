---
title: "RecognitionResult"
second_title: "مرجع API لـ Aspose.OCR للبايثون عبر جافا"
description: 
type: docs
weight: 171
url: /ar/python-java/aspose/recognitionresult/
---

الوحدة recognitionresult
========================

الفئات
-------

`LinesResult(javaClass)`
:

### الأسلاف (في MRO)

    * aspose.helper.BaseJavaClass

### طرق

`initParams(self)`
:

`RecognitionResult(javaClass)`
:
نتائج التعرف على الصورة. يحتوي على عناصر مع التعرف
معلومات وطرق لتصدير النتيجة.

### طرق ثابتة

`save_multipage_document(self, fullPath: str)`
:
خاص

### المتغيرات المثيلة

`recognition_areas_text`
:   قائمة نتائج التعرف لقائمة من المناطق (مستطيلات).

`recognition_lines_result`
:   يحصل على قائمة نتائج التعرف مع قائمة من الصفوف (مستطيلات).

### طرق

`getJavaClass(self)`
:

`get_json(self)`
:
شكل سلسلة JSON مع نتائج التعرف.
@return: نتائج التعرف كسلسلة JSON.

`get_spell_check_corrected_text(self, language: aspose.models.SpellCheckLanguage) ‑> str`
:
يصحح النص (يستبدل الكلمات المكتوبة خطأ).
@param language: القاموس للاستخدام.
@return: سلسلة نتائج التعرف المصححة.

`get_spell_check_error_list(self, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
ابحث عن الكلمات المكتوبة بشكل خاطئ مع الاقتراحات الإملائية لنص الإدخال المعطى.
@param language: القاموس للاستخدام.
@return: قائمة من كائن SpellCheckError تمثل الكلمات المكتوبة بشكل خاطئ مع قوائم الاقتراحات الصحيحة لكل كلمة مكتوبة بشكل خاطئ،
ومع مسافة التحرير.

`get_xml(self)`
:
شكل سلسلة JSON مع نتائج التعرف.
@return: نتائج التعرف كسلسلة XML.

`init(self)`
:

`save(self, fullFileName: str, format: aspose.models.Format)`
:
يحفظ المستند كنص عادي أو بأي تنسيق مستند آخر.
@param fullFileName: اسم الملف مع المسار لحفظ نتيجة التعرف.
@param format: نوع تعداد تنسيق المستند من Format.

`save_spell_check_corrected_text(self, fullFileName: str, format: aspose.models.Format, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
يصحح النص (يستبدل الكلمات المكتوبة خطأ).
يحفظ النص المصحح في المستند كنص عادي أو بأي تنسيق آخر.
@param fullFileName: اسم الملف مع المسار لحفظ نتيجة التعرف
@param format: نوع تعداد تنسيق المستند من Format.
@param language: القاموس لتصحيح الإملاء.

`use_user_dictionary(self, dictionaryPath: str)`
:
يسمح باستخدام القاموس الخاص لتصحيح الأخطاء الإملائية.
@param dictionaryPath: المسار الكامل إلى القاموس المستخدم (قاموس التردد).
تنسيق ملف القاموس:
ملف نص عادي بترميز UTF-8.
الكلمة وتردد الكلمة مفصولان بفاصلة، من المتوقع أن تكون الكلمة في العمود الأول والتردد في العمود الثاني.
كل زوج كلمة‑تردد في سطر منفصل. يُعرّف السطر على أنه تسلسل من الأحرف يتبعه إشارة سطر جديد ("
"), إشارة عودة السطر ("
\"),
أو عودة سطر متبوعة مباشرةً بانتقال سطر(\"

\").
من المتوقع أن تكون كل كلمة بأحرف صغيرة.
مثال:
\code
كلمة,5984819
مرحبا,5761742
أسفل,5582768
\endcode

`RectangleOutput(javaClass)`
:
بيانات حول مناطق النص أو السطور المكتشفة.
\code
source - المسار الكامل للملف أو URL، إن وجد. فارغ للمُدَخلات، مصفوفات البايت، base64.
page - رقم الصفحة.
image_index - رقم تسلسل الصورة في الصفحة.
rectangles - قائمة المناطق النصية المكتشفة أو الخطوط.
\endcode

### الأسلاف (في MRO)

    * aspose.helper.BaseJavaClass

### طرق

`initParams(self)`
:

`SkewOutput(javaClass)`
:
بيانات حول زاوية الانحراف بالدرجات واسم الملف.
\code
source - المسار الكامل للملف أو URL، إن وجد. فارغ للمُدَخلات، مصفوفات البايت، base64.
page - رقم الصفحة.
image_index - رقم تسلسل الصورة في الصفحة.
angle - زاوية الانحراف بالدرجات.
\endcode

### الأسلاف (في MRO)

    * aspose.helper.BaseJavaClass

### طرق

`initParams(self)`
:


### انظر أيضًا

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)