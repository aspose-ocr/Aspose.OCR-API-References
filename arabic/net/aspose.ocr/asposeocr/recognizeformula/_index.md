---
title: "RecognizeFormula"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "يتعرف على الصيغ الرياضية من صور الإدخال المقدمة."
type: docs
weight: 180
url: /ar/net/aspose.ocr/asposeocr/recognizeformula/
---
## AsposeOcr.RecognizeFormula method

يتعرف على الصيغ الرياضية من صور الإدخال المقدمة.

```csharp
public OcrOutput RecognizeFormula(OcrInput images, bool detectAreas = true)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| صور | OcrInput | الصور المدخلة التي تحتوي على تعبير رياضي واحد أو أكثر للتعرف عليها. يدعم إدخال OCR متعدد الصفحات أو متعدد الإطارات. |
| detectAreas | Boolean | إذا تم تعيينه إلى `true`، يتم اكتشاف مناطق الصيغة وعزلها تلقائيًا قبل إجراء التعرف. إذا كان `false`، يتم معالجة الصورة بالكامل كصيغة. |

### قيمة الإرجاع

كائن [`OcrOutput`](../../ocroutput) يحتوي على نص الصيغة المعترف به، درجات ثقة الاكتشاف، ومعلومات الموقع.

### انظر أيضًا

* class [OcrOutput](../../ocroutput)
* class [OcrInput](../../ocrinput)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
