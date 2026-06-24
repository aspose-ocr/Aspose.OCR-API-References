---
title: "إعدادات التعرف على الإيصالات"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "إعدادات التعرف على الإيصال. تحتوي على عناصر تسمح بتخصيص عملية التعرف."
type: docs
weight: 280
url: /ar/net/aspose.ocr/receiptrecognitionsettings/
---
## ReceiptRecognitionSettings class

إعدادات التعرف على الإيصال. تحتوي على عناصر تسمح بتخصيص عملية التعرف.

```csharp
public class ReceiptRecognitionSettings : BaseRecognitionSettings
```

## Constructors

| Name | الوصف |
| --- | --- |
| [ReceiptRecognitionSettings](receiptrecognitionsettings#constructor)() | يُنشئ مثيلاً جديدًا من الفئة [`ReceiptRecognitionSettings`](../receiptrecognitionsettings) مع مجموعة الخصائص الافتراضية. |
| [ReceiptRecognitionSettings](receiptrecognitionsettings#constructor_1)(Language) | يُنشئ مثيلاً جديدًا من الفئة [`ReceiptRecognitionSettings`](../receiptrecognitionsettings) مع مجموعة كاملة من الخصائص. |

## Properties

| Name | الوصف |
| --- | --- |
| [AllowedCharacters](../../aspose.ocr/baserecognitionsettings/allowedcharacters) { get; set; } | مجموعة الأحرف المسموح بها. تحدد نوع الأحرف المسموح بها لنتيجة التعرف. |
| [AllowedSymbols](../../aspose.ocr/baserecognitionsettings/allowedsymbols) { get; set; } | حدد الأحرف المسموح بها باستخدام خاصية alphabet. |
| [AutomaticColorInversion](../../aspose.ocr/baserecognitionsettings/automaticcolorinversion) { get; set; } | اكتشف الصور التي تحتوي على نص أبيض على خلفية داكنة/سوداء واختر تلقائيًا خوارزمية OCR خاصة لها. |
| [IgnoredSymbols](../../aspose.ocr/baserecognitionsettings/ignoredsymbols) { get; set; } | يضبط القائمة السوداء لرموز التعرف. |
| [Language](../../aspose.ocr/baserecognitionsettings/language) { get; set; } | يحصل أو يضبط اللغة المستخدمة في OCR. تحدد الأبجدية المستخدمة أثناء التعرف. متعددة اللغات بشكل افتراضي. |
| [RecognizeVerticalLines](../../aspose.ocr/baserecognitionsettings/recognizeverticallines) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اكتشاف وتعرف خطوط النص العمودية بالإضافة إلى الأفقية. القيمة الافتراضية هي `false`. |
| [ThreadsCount](../../aspose.ocr/baserecognitionsettings/threadscount) { get; set; } | يحصل أو يضبط عدد الخيوط للمعالجة. بشكل افتراضي، 0 يعني أن الصورة ستُعالج بعدد خيوط يساوي عدد المعالجات لديك. ThreadsCount = 1 يعني أن الصورة ستُعالج في الخيط الرئيسي. |

### انظر أيضًا

* class [BaseRecognitionSettings](../baserecognitionsettings)
* namespace [Aspose.OCR](../../aspose.ocr)
* assembly [Aspose.OCR](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
