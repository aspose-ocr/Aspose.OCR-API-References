---
title: "DocumentRecognitionSettings"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "إعدادات التعرف على ملفات PDF. يحتوي على عناصر تسمح بتخصيص عملية التعرف."
type: docs
weight: 140
url: /ar/net/aspose.ocr/documentrecognitionsettings/
---
## DocumentRecognitionSettings class

إعدادات التعرف على ملفات PDF. يحتوي على عناصر تسمح بتخصيص عملية التعرف.

```csharp
public class DocumentRecognitionSettings : BaseRecognitionSettings
```

## Constructors

| Name | الوصف |
| --- | --- |
| [DocumentRecognitionSettings](documentrecognitionsettings#constructor)(int, int) | يُنشئ نسخة جديدة من الفئة [`DocumentRecognitionSettings`](../documentrecognitionsettings) مع مجموعة مختصرة من الخصائص. |
| [DocumentRecognitionSettings](documentrecognitionsettings#constructor_1)(int, int, Language, bool, bool, int) | يُنشئ نسخة جديدة من الفئة [`DocumentRecognitionSettings`](../documentrecognitionsettings) مع مجموعة كاملة من الخصائص. |

## Properties

| Name | الوصف |
| --- | --- |
| [AllowedCharacters](../../aspose.ocr/baserecognitionsettings/allowedcharacters) { get; set; } | مجموعة الأحرف المسموح بها. تحدد نوع الأحرف المسموح بها لنتيجة التعرف. |
| [AutoContrast](../../aspose.ocr/baserecognitionsettings/autocontrast) { get; set; } | يسمح باستخدام خوارزمية تصحيح التباين الإضافية للصورة قبل عملية التعرف. |
| [AutoDenoising](../../aspose.ocr/baserecognitionsettings/autodenoising) { get; set; } | يفعل استخدام شبكة عصبية إضافية لتحسين الصورة - تقليل الضوضاء. مفيد للصور التي تحتوي على عيوب مسح، تشوهات، بقع، توهجات، تدرجات، عناصر غريبة. |
| [AutoSkew](../../aspose.ocr/baserecognitionsettings/autoskew) { set; } | يحصل أو يضبط علامة تشير إلى ما إذا كان يجب تمكين تصحيح الميل التلقائي للصورة. مفعَّل (true) بشكل افتراضي. |
| [DetectAreasMode](../../aspose.ocr/baserecognitionsettings/detectareasmode) { get; set; } | يسمح باختيار الوضع الأمثل لمناطق نوع المستند: مستند، صورة، نص عادي، عمود، صورة. |
| [IgnoredCharacters](../../aspose.ocr/baserecognitionsettings/ignoredcharacters) { get; set; } | يضبط القائمة السوداء لرموز التعرف. |
| [Language](../../aspose.ocr/baserecognitionsettings/language) { set; } | يحصل أو يضبط اللغة المستخدمة في OCR. تحدد الأبجدية المستخدمة أثناء التعرف. متعددة اللغات بشكل افتراضي. |
| [LinesFiltration](../../aspose.ocr/baserecognitionsettings/linesfiltration) { get; set; } | يسمح بالتعرف على النص داخل الجداول (المناطق المحاطة بخطوط). |
| [PagesNumber](../../aspose.ocr/documentrecognitionsettings/pagesnumber) { get; set; } | حدد عدد الصفحات للتعرف على ملف PDF متعدد الصفحات. |
| [PreprocessingFilters](../../aspose.ocr/baserecognitionsettings/preprocessingfilters) { get; set; } | يسمح بتحضير الصورة لـ OCR عن طريق تعديل طرق المعالجة المسبقة. |
| [SkewAngle](../../aspose.ocr/baserecognitionsettings/skewangle) { set; } | يحصل أو يضبط الزاوية بالدرجات لتدوير الصورة. ضبط هذه القيمة سيعطل الخاصية [`AutoSkew`](../baserecognitionsettings/autoskew)، بحيث لا يتم تطبيق تصحيح الميل التلقائي. الصفر بشكل افتراضي. |
| [StartPage](../../aspose.ocr/documentrecognitionsettings/startpage) { get; set; } | حدد الصفحة الأولى للتعرف. |
| [ThreadsCount](../../aspose.ocr/baserecognitionsettings/threadscount) { set; } | يحصل أو يضبط عدد الخيوط للمعالجة. بشكل افتراضي، 0 يعني أن الصورة ستُعالج بعدد خيوط يساوي عدد المعالجات لديك. ThreadsCount = 1 يعني أن الصورة ستُعالج في الخيط الرئيسي. |
| [ThresholdValue](../../aspose.ocr/baserecognitionsettings/thresholdvalue) { set; } | يحصل أو يعيّن قيمة العتبة المخصصة لتصوير الصورة ثنائية. النطاق من 1 إلى 255. |
| [UpscaleSmallFont](../../aspose.ocr/baserecognitionsettings/upscalesmallfont) { get; set; } | يتيح لك استخدام خوارزميات إضافية مخصصة للتعرف على الخطوط الصغيرة. مفيد للصور التي تحتوي على أحرف صغيرة الحجم. |

### انظر أيضًا

* class [BaseRecognitionSettings](../baserecognitionsettings)
* namespace [Aspose.OCR](../../aspose.ocr)
* assembly [Aspose.OCR](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
