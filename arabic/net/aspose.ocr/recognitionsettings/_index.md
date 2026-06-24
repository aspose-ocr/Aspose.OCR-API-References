---
title: "RecognitionSettings"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "إعدادات التعرف على الصور. تحتوي على عناصر تتيح تخصيص عملية التعرف."
type: docs
weight: 290
url: /ar/net/aspose.ocr/recognitionsettings/
---
## RecognitionSettings class

إعدادات التعرف على الصور. تحتوي على عناصر تتيح تخصيص عملية التعرف.

```csharp
public class RecognitionSettings : BaseRecognitionSettings
```

## Constructors

| Name | الوصف |
| --- | --- |
| [RecognitionSettings](recognitionsettings#constructor)() | ينشئ نسخة جديدة من الفئة [`RecognitionSettings`](../recognitionsettings) مع auto skew = true. |
| [RecognitionSettings](recognitionsettings#constructor_1)(Language, List&lt;Rectangle&gt;, bool) | ينشئ نسخة جديدة من الفئة [`RecognitionSettings`](../recognitionsettings) مع مجموعة كاملة من الخصائص. |

## Properties

| Name | الوصف |
| --- | --- |
| [AllowedCharacters](../../aspose.ocr/baserecognitionsettings/allowedcharacters) { get; set; } | مجموعة الأحرف المسموح بها. تحدد نوع الأحرف المسموح بها لنتيجة التعرف. |
| [AllowedSymbols](../../aspose.ocr/baserecognitionsettings/allowedsymbols) { get; set; } | حدد الأحرف المسموح بها باستخدام خاصية alphabet. |
| [AutomaticColorInversion](../../aspose.ocr/baserecognitionsettings/automaticcolorinversion) { get; set; } | اكتشف الصور التي تحتوي على نص أبيض على خلفية داكنة/سوداء واختر تلقائيًا خوارزمية OCR خاصة لها. |
| [DetectAreasMode](../../aspose.ocr/recognitionsettings/detectareasmode) { get; set; } | يسمح باختيار الوضع الأمثل لمناطق نوع المستند: مستند، صورة، نص عادي، عمود، صورة. |
| [IgnoredSymbols](../../aspose.ocr/baserecognitionsettings/ignoredsymbols) { get; set; } | يضبط القائمة السوداء لرموز التعرف. |
| [Language](../../aspose.ocr/baserecognitionsettings/language) { get; set; } | يحصل أو يضبط اللغة المستخدمة في OCR. تحدد الأبجدية المستخدمة أثناء التعرف. متعددة اللغات بشكل افتراضي. |
| [LanguageDetectionLevel](../../aspose.ocr/recognitionsettings/languagedetectionlevel) { get; set; } | يحدد مستوى اكتشاف اللغة للتعرف على النص. يعمل فقط إذا كانت اللغة المحددة هي Multilanguage أو Auto أو Universal. هذه العملية تستغرق وقتًا طويلاً وتبطئ بشكل كبير عملية التعرف العامة. |
| [LinesFiltration](../../aspose.ocr/recognitionsettings/linesfiltration) { get; set; } | يسمح بالتعرف على النص داخل الجداول (المناطق المحاطة بخطوط). |
| [RecognitionAreas](../../aspose.ocr/recognitionsettings/recognitionareas) { get; set; } | يحصل أو يعيّن قائمة مناطق النص للمعالجة. يسمح بتحديد المناطق التي تحتوي على نص يدويًا للحصول على تعرف أكثر دقة. يعطل AutoSkew. |
| [RecognizeSingleLine](../../aspose.ocr/recognitionsettings/recognizesingleline) { get; set; } | يضبط التعرف على الصور ذات السطر الواحد. يكون معطلاً (false) بشكل افتراضي. يعطل جميع خطوات المعالجة المرتبطة بتقسيم الصورة إلى أسطر. اضبط هذه المعلمة إلى true إذا كانت صورتك تحتوي على سطر واحد فقط. يعطل إعدادات RecognitionAreas، وبالتالي سيتم تجاهل جميع إعدادات المناطق. |
| [RecognizeVerticalLines](../../aspose.ocr/baserecognitionsettings/recognizeverticallines) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اكتشاف وتعرف خطوط النص العمودية بالإضافة إلى الأفقية. القيمة الافتراضية هي `false`. |
| [ThreadsCount](../../aspose.ocr/baserecognitionsettings/threadscount) { get; set; } | يحصل أو يضبط عدد الخيوط للمعالجة. بشكل افتراضي، 0 يعني أن الصورة ستُعالج بعدد خيوط يساوي عدد المعالجات لديك. ThreadsCount = 1 يعني أن الصورة ستُعالج في الخيط الرئيسي. |
| [UpscaleSmallFont](../../aspose.ocr/recognitionsettings/upscalesmallfont) { get; set; } | يتيح لك استخدام خوارزميات إضافية مخصصة للتعرف على الخطوط الصغيرة. مفيد للصور التي تحتوي على أحرف صغيرة الحجم. |

### انظر أيضًا

* class [BaseRecognitionSettings](../baserecognitionsettings)
* namespace [Aspose.OCR](../../aspose.ocr)
* assembly [Aspose.OCR](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
