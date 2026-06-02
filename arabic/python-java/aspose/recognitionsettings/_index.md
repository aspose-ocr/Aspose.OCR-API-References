---
title: "RecognitionSettings"
second_title: "مرجع API لـ Aspose.OCR للبايثون عبر جافا"
description: 
type: docs
weight: 191
url: /ar/python-java/aspose/recognitionsettings/
---

Module recognitionsettings
==========================

الفئات
-------

`CarPlateRecognitionSettings()`
:

### متغيرات الفئة

`JAVA_CLASS_NAME`
:

### طرق

`set_allowed_characters(self, allowedCharacters: str)`
:
مجموعة الأحرف المسموح بها. تحدد مصفوفة الأحرف المسموح بها لنتيجة التعرف.
@param allowedCharacters: يحتوي على سلسلة من الأحرف.

`set_ignored_characters(self, ignoredCharacters: str)`
:
يضبط القائمة السوداء لرموز التعرف.
@param ignoredCharacters: الأحرف المستبعدة من التعرف.

`set_language(self, language: aspose.models.Language)`
:
يضبط اللغة المستخدمة للتعرف الضوئي على الأحرف.
متعدد اللغات (بدون) بشكل افتراضي.
@param language: يحتوي على قيمة تعداد Language.

`set_threads_count(self, threadsCount: int)`
:
يحصل أو يضبط عدد الخيوط للمعالجة.
بشكل افتراضي، 0 يعني أن الصورة ستُعالج بعدد الخيوط المساوي لعدد المعالجات لديك.
ThreadsCount = 1 يعني أن الصورة ستُعالج في الخيط الرئيسي.
@param threadsCount: عدد الخيوط التي سيتم إنشاؤها للتعرف المتوازي على أجزاء الصورة.

`IDCardRecognitionSettings()`
:

### متغيرات الفئة

`JAVA_CLASS_NAME`
:

### طرق

`set_allowed_characters(self, allowedCharacters: str)`
:
مجموعة الأحرف المسموح بها. تحدد مصفوفة الأحرف المسموح بها لنتيجة التعرف.
@param allowedCharacters: يحتوي على سلسلة من الأحرف.

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
يكشف عن الصور التي تحتوي على نص أبيض على خلفية داكنة/سوداء ويختار تلقائيًا خوارزمية OCR خاصة لها.
@param automaticColorInversion: يحتوي على قيمة منطقية - تم تعيين automaticColorInversion. صحيح بشكل افتراضي.

`set_ignored_characters(self, ignoredCharacters: str)`
:
يضبط القائمة السوداء لرموز التعرف.
@param ignoredCharacters: الأحرف المستبعدة من التعرف.

`set_language(self, language: aspose.models.Language)`
:
يضبط اللغة المستخدمة للتعرف الضوئي على الأحرف.
متعدد اللغات (بدون) بشكل افتراضي.
@param language: يحتوي على قيمة تعداد Language.

`set_threads_count(self, threadsCount: int)`
:
يحصل أو يضبط عدد الخيوط للمعالجة.
بشكل افتراضي، 0 يعني أن الصورة ستُعالج بعدد الخيوط المساوي لعدد المعالجات لديك.
ThreadsCount = 1 يعني أن الصورة ستُعالج في الخيط الرئيسي.
@param threadsCount: عدد الخيوط التي سيتم إنشاؤها للتعرف المتوازي على أجزاء الصورة.

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
يسمح لك باستخدام خوارزميات إضافية مخصصة لتعرف الخط الصغير.
مفيد للصور التي تحتوي على أحرف صغيرة الحجم.
@param upscaleSmallFont: يحتوي على قيمة منطقية - تم تعيين upscaleSmallFont.

`InvoiceRecognitionSettings()`
:

### متغيرات الفئة

`JAVA_CLASS_NAME`
:

### طرق

`set_allowed_characters(self, allowedCharacters: str)`
:
مجموعة الأحرف المسموح بها. تحدد مصفوفة الأحرف المسموح بها لنتيجة التعرف.
@param allowedCharacters: يحتوي على سلسلة من الأحرف.

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
يكشف عن الصور التي تحتوي على نص أبيض على خلفية داكنة/سوداء ويختار تلقائيًا خوارزمية OCR خاصة لها.
@param automaticColorInversion: يحتوي على قيمة منطقية - تم تعيين automaticColorInversion. صحيح بشكل افتراضي.

`set_ignored_characters(self, ignoredCharacters: str)`
:
يضبط القائمة السوداء لرموز التعرف.
@param ignoredCharacters: الأحرف المستبعدة من التعرف.

`set_language(self, language: aspose.models.Language)`
:
يضبط اللغة المستخدمة للتعرف الضوئي على الأحرف.
متعدد اللغات (بدون) بشكل افتراضي.
@param language: يحتوي على قيمة تعداد Language.

`set_threads_count(self, threadsCount: int)`
:
يحصل أو يضبط عدد الخيوط للمعالجة.
بشكل افتراضي، 0 يعني أن الصورة ستُعالج بعدد الخيوط المساوي لعدد المعالجات لديك.
ThreadsCount = 1 يعني أن الصورة ستُعالج في الخيط الرئيسي.
@param threadsCount: عدد الخيوط التي سيتم إنشاؤها للتعرف المتوازي على أجزاء الصورة.

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
يسمح لك باستخدام خوارزميات إضافية مخصصة لتعرف الخط الصغير.
مفيد للصور التي تحتوي على أحرف صغيرة الحجم.
@param upscaleSmallFont: يحتوي على قيمة منطقية - تم تعيين upscaleSmallFont.

`PassportRecognitionSettings()`
:

### متغيرات الفئة

`JAVA_CLASS_NAME`
:

### طرق

`set_allowed_characters(self, allowedCharacters: str)`
:
مجموعة الأحرف المسموح بها. تحدد مصفوفة الأحرف المسموح بها لنتيجة التعرف.
@param allowedCharacters: يحتوي على سلسلة من الأحرف.

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
يكشف عن الصور التي تحتوي على نص أبيض على خلفية داكنة/سوداء ويختار تلقائيًا خوارزمية OCR خاصة لها.
@param automaticColorInversion: يحتوي على قيمة منطقية - تم تعيين automaticColorInversion. صحيح بشكل افتراضي.

`set_ignored_characters(self, ignoredCharacters: str)`
:
يضبط القائمة السوداء لرموز التعرف.
@param ignoredCharacters: الأحرف المستبعدة من التعرف.

`set_language(self, language: aspose.models.Language)`
:
يضبط اللغة المستخدمة للتعرف الضوئي على الأحرف.
متعدد اللغات (بدون) بشكل افتراضي.
@param language: يحتوي على قيمة تعداد Language.

`set_threads_count(self, threadsCount: int)`
:
يحصل أو يضبط عدد الخيوط للمعالجة.
بشكل افتراضي، 0 يعني أن الصورة ستُعالج بعدد الخيوط المساوي لعدد المعالجات لديك.
ThreadsCount = 1 يعني أن الصورة ستُعالج في الخيط الرئيسي.
@param threadsCount: عدد الخيوط التي سيتم إنشاؤها للتعرف المتوازي على أجزاء الصورة.

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
يسمح لك باستخدام خوارزميات إضافية مخصصة لتعرف الخط الصغير.
مفيد للصور التي تحتوي على أحرف صغيرة الحجم.
@param upscaleSmallFont: يحتوي على قيمة منطقية - تم تعيين upscaleSmallFont.

`ReceiptRecognitionSettings()`
:

### متغيرات الفئة

`JAVA_CLASS_NAME`
:

### طرق

`set_allowed_characters(self, allowedCharacters: str)`
:
مجموعة الأحرف المسموح بها. تحدد مصفوفة الأحرف المسموح بها لنتيجة التعرف.
@param allowedCharacters: يحتوي على سلسلة من الأحرف.

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
يكشف عن الصور التي تحتوي على نص أبيض على خلفية داكنة/سوداء ويختار تلقائيًا خوارزمية OCR خاصة لها.
@param automaticColorInversion: يحتوي على قيمة منطقية - تم تعيين automaticColorInversion. صحيح بشكل افتراضي.

`set_ignored_characters(self, ignoredCharacters: str)`
:
يضبط القائمة السوداء لرموز التعرف.
@param ignoredCharacters: الأحرف المستبعدة من التعرف.

`set_language(self, language: aspose.models.Language)`
:
يضبط اللغة المستخدمة للتعرف الضوئي على الأحرف.
متعدد اللغات (بدون) بشكل افتراضي.
@param language: يحتوي على قيمة تعداد Language.

`set_threads_count(self, threadsCount: int)`
:
يحصل أو يضبط عدد الخيوط للمعالجة.
بشكل افتراضي، 0 يعني أن الصورة ستُعالج بعدد الخيوط المساوي لعدد المعالجات لديك.
ThreadsCount = 1 يعني أن الصورة ستُعالج في الخيط الرئيسي.
@param threadsCount: عدد الخيوط التي سيتم إنشاؤها للتعرف المتوازي على أجزاء الصورة.

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
يسمح لك باستخدام خوارزميات إضافية مخصصة لتعرف الخط الصغير.
مفيد للصور التي تحتوي على أحرف صغيرة الحجم.
@param upscaleSmallFont: يحتوي على قيمة منطقية - تم تعيين upscaleSmallFont.

`RecognitionSettings()`
:
إعدادات التعرف على الصورة.
يحتوي على عناصر تسمح بتخصيص عملية التعرف.
    
    
المُنشئ الافتراضي: تعيين recognitionAreas إلى null، linesFiltration إلى false، autoSkew إلى false، recognizeSingleLine إلى false.

### متغيرات الفئة

`JAVA_CLASS_NAME`
:

### طرق

`set_allowed_characters(self, allowedCharacters: str)`
:
مجموعة الأحرف المسموح بها. تحدد مصفوفة الأحرف المسموح بها لنتيجة التعرف.
@param allowedCharacters: يحتوي على سلسلة من الأحرف.

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
يكشف عن الصور التي تحتوي على نص أبيض على خلفية داكنة/سوداء ويختار تلقائيًا خوارزمية OCR خاصة لها.
@param automaticColorInversion: يحتوي على قيمة منطقية - تم تعيين automaticColorInversion. صحيح بشكل افتراضي.

`set_detect_areas_mode(self, detectAreasMode: aspose.models.DetectAreasMode)`
:
يحدد نوع الشبكة العصبية المستخدمة لاكتشاف المناطق.
@param detectAreasMode: يحتوي على قيمة enum DetectAreasMode.

`set_ignored_characters(self, ignoredCharacters: str)`
:
يضبط القائمة السوداء لرموز التعرف.
@param ignoredCharacters: الأحرف المستبعدة من التعرف.

`set_language(self, language: aspose.models.Language)`
:
يضبط اللغة المستخدمة للتعرف الضوئي على الأحرف.
متعدد اللغات (بدون) بشكل افتراضي.
@param language: يحتوي على قيمة تعداد Language.

`set_recognize_single_line(self, recognizeSingleLine: bool)`
:
يضبط التعرف على الصورة ذات السطر الواحد.
معطل (false) بشكل افتراضي.
تعطيل جميع خطوات المعالجة المرتبطة بتقسيم الصورة إلى أسطر.
عيّن هذا المعامل إلى true إذا كانت صورتك تحتوي على سطر واحد فقط. يعطل إعدادات set_recognition_areas، لذا سيتم تجاهل جميع إعدادات المناطق.
@param recognizeSingleLine: True لصورة سطر واحد

`set_threads_count(self, threadsCount: int)`
:
يحصل أو يضبط عدد الخيوط للمعالجة.
بشكل افتراضي، 0 يعني أن الصورة ستُعالج بعدد الخيوط المساوي لعدد المعالجات لديك.
ThreadsCount = 1 يعني أن الصورة ستُعالج في الخيط الرئيسي.
@param threadsCount: عدد الخيوط التي سيتم إنشاؤها للتعرف المتوازي على أجزاء الصورة.

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
يسمح لك باستخدام خوارزميات إضافية مخصصة لتعرف الخط الصغير.
مفيد للصور التي تحتوي على أحرف صغيرة الحجم.
@param upscaleSmallFont: يحتوي على قيمة منطقية - تم تعيين upscaleSmallFont.



### انظر أيضًا

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)