---
title: "OcrOutput"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "فئة حاوية لتخزين وإدارة نتائج عمليات OCR."
type: docs
weight: 430
url: /ar/net/aspose.ocr/ocroutput/
---
## OcrOutput class

فئة حاوية لتخزين وإدارة نتائج عمليات OCR.

```csharp
public class OcrOutput : List<RecognitionResult>
```

## Constructors

| Name | الوصف |
| --- | --- |
| [OcrOutput](ocroutput#constructor)() | إنشاء نسخة جديدة من الفئة [`OcrOutput`](../ocroutput) مع مجموعة فارغة. يستدعي هذا المُنشئ مُنشئ الفئة الأساسية لتهيئة قائمة فارغة من [`RecognitionResult`](../recognitionresult). |
| [OcrOutput](ocroutput#constructor_1)(int) | إنشاء نسخة جديدة من الفئة [`OcrOutput`](../ocroutput) بسعة أولية محددة. يُنشئ هذا المُنشئ كائنًا جديدًا من [`OcrOutput`](../ocroutput) مع عدد مسبق من العناصر المخصصة، مما يحسن الأداء عندما تكون الحجم معروفًا مسبقًا. |
| [OcrOutput](ocroutput#constructor_2)(IEnumerable&lt;RecognitionResult&gt;, OcrInput) | إنشاء نسخة جديدة من الفئة [`OcrOutput`](../ocroutput) بمجموعة محددة من [`RecognitionResult`](../recognitionresult). يُنشئ هذا المُنشئ كائنًا جديدًا من [`OcrOutput`](../ocroutput) بنسخ العناصر من المجموعة المقدمة. |

## Properties

| Name | الوصف |
| --- | --- |
| [IsReadOnly](../../aspose.ocr/ocroutput/isreadonly) { get; } | دائمًا ما تُعيد false لأن OcrOutput قابل للتغيير. |

## Methods

| Name | الوصف |
| --- | --- |
| [AddRange](../../aspose.ocr/ocroutput/addrange#addrange)(IEnumerable&lt;RecognitionResult&gt;) | يضيف عناصر المجموعة المحددة إلى نهاية قائمة [`OcrOutput`](../ocroutput). تُعيد هذه الطريقة كتابة سلوك AddRange الافتراضي لتنفيذ عمليات إضافية إذا لزم الأمر. |
| [GetTableData](../../aspose.ocr/ocroutput/gettabledata)() | تُعيد بيانات جدول مُنظمة مستخرجة من جميع الصفحات المعترف بها. مفيدة إذا كانت الصفحة بأكملها جدولًا واحدًا. |
| [Save](../../aspose.ocr/ocroutput/save#save)(MemoryStream, SaveFormat, string, PdfOptimizationMode) | احفظ جميع نتائج التعرف إلى تدفق الذاكرة بالتنسيق المحدد. |
| [Save](../../aspose.ocr/ocroutput/save#save_1)(string, SaveFormat, string, PdfOptimizationMode) | احفظ جميع نتائج التعرف إلى ملف. |
| [SavePdf](../../aspose.ocr/ocroutput/savepdf#savepdf)(MemoryStream, string, PdfOptimizationMode) | احفظ جميع نتائج التعرف في مستند PDF قابل للبحث داخل الذاكرة، مع تضمين الصور الأصلية كخلفية. |
| [SavePdf](../../aspose.ocr/ocroutput/savepdf#savepdf_1)(string, string, PdfOptimizationMode) | احفظ جميع نتائج التعرف في ملف PDF قابل للبحث، مع تعيين الصور الأصلية كخلفية. |

### انظر أيضًا

* class [RecognitionResult](../recognitionresult)
* namespace [Aspose.OCR](../../aspose.ocr)
* assembly [Aspose.OCR](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
