---
title: "RecognitionResult"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "نتائج التعرف على الصورة. تحتوي على عناصر بمعلومات التعرف وطرق لتصدير النتائج."
type: docs
weight: 140
url: /ar/net/aspose.ocr/recognitionresult/
---
## RecognitionResult class

نتائج التعرف على الصورة. تحتوي على عناصر بمعلومات التعرف وطرق لتصدير النتائج.

```csharp
public class RecognitionResult
```

## Constructors

| Name | الوصف |
| --- | --- |
| [RecognitionResult](recognitionresult)() | يُنشئ مثيلاً جديدًا من الفئة [`RecognitionResult`](../recognitionresult). |

## Properties

| Name | الوصف |
| --- | --- |
| [FileName](../../aspose.ocr/recognitionresult/filename) { get; set; } | المسار الكامل للملف. |
| [Image](../../aspose.ocr/recognitionresult/image) { get; set; } | يحصل أو يعيّن الصورة لإنشاء PDF. |
| [RecognitionCharactersList](../../aspose.ocr/recognitionresult/recognitioncharacterslist) { get; } | مجموعة من الأحرف التي وجدها خوارزمية التعرف وتم ترتيبها بترتيب تنازلي لاحتمالية ظهورها. |
| [RecognitionLinesResult](../../aspose.ocr/recognitionresult/recognitionlinesresult) { get; } | يحصل على قائمة من نتائج التعرف مع قائمة من الصفوف (Rectangles). |
| [RecognitionRegionsResult](../../aspose.ocr/recognitionresult/recognitionregionsresult) { get; } | يحصل على قائمة من نتائج التعرف مع قائمة من المناطق (Rectangles). |
| [RecognitionText](../../aspose.ocr/recognitionresult/recognitiontext) { get; set; } | يحصل على نتيجة التعرف كسلسلة واحدة. |
| [SerializableImage](../../aspose.ocr/recognitionresult/serializableimage) { get; set; } | حمولة صورة مسلسلة تُستخدم لتسلسل JSON/ثنائي لـ RecognitionResult. تخزن نفس بيانات الصورة كما في [`Image`](./image)، ولكن بصيغة أحادية البعد. |
| [Warnings](../../aspose.ocr/recognitionresult/warnings) { get; } | يحصل على قائمة رسائل التحذير التي تصف الأخطاء غير الحرجة التي ظهرت أثناء الإنشاء. |

## Methods

| Name | الوصف |
| --- | --- |
| [GetJson](../../aspose.ocr/recognitionresult/getjson)(bool) | تكوين سلسلة JSON مع نتائج التعرف. |
| [GetKeywords](../../aspose.ocr/recognitionresult/getkeywords)() | احصل على الكلمات المفتاحية من جواز السفر (وضع الاختبار. يعمل فقط لجوازات السفر الأمريكية وماداغاسكار). |
| [GetSpellCheckCorrectedText](../../aspose.ocr/recognitionresult/getspellcheckcorrectedtext)(SpellCheckLanguage, string) | يصحح النص (يستبدل الكلمات المكتوبة خطأ). |
| [GetSpellCheckErrorList](../../aspose.ocr/recognitionresult/getspellcheckerrorlist)(SpellCheckLanguage, string) | ابحث عن الكلمات المكتوبة بشكل خاطئ مع اقتراحات التصحيح للنص المدخل. |
| [GetXml](../../aspose.ocr/recognitionresult/getxml)() | تكوين سلسلة XML مع نتائج التعرف. |
| [Save](../../aspose.ocr/recognitionresult/save#save_1)(MemoryStream, SaveFormat, string, PdfOptimizationMode) | يحفظ المستند كنص عادي أو PDF أو مستند Microsoft Word. |
| [Save](../../aspose.ocr/recognitionresult/save#save_3)(string, SaveFormat, string, PdfOptimizationMode) | يحفظ المستند كنص عادي أو PDF أو مستند Microsoft Word. |
| [Save](../../aspose.ocr/recognitionresult/save#save)(MemoryStream, SaveFormat, bool, SpellCheckLanguage, string, string, PdfOptimizationMode) | يحفظ المستند كنص عادي أو PDF أو مستند Microsoft Word. |
| [Save](../../aspose.ocr/recognitionresult/save#save_2)(string, SaveFormat, bool, SpellCheckLanguage, string, string, PdfOptimizationMode) | يحفظ المستند كنص عادي أو PDF أو مستند Microsoft Word. |
| [operator +](../../aspose.ocr/recognitionresult/op_addition) | لإكمال النتيجة الكاملة من القطع المعترف بها (الخطوط). |

## الأعضاء الآخرين

| Name | الوصف |
| --- | --- |
| class [LinesResult](recognitionresult.linesresult) | النص المعترف به من الصف مع إحداثيات الصف. |
| class [RegionResult](recognitionresult.regionresult) | النص المعترف به من المنطقة مع إحداثيات المنطقة. |

### انظر أيضًا

* namespace [Aspose.OCR](../../aspose.ocr)
* assembly [Aspose.OCR](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
