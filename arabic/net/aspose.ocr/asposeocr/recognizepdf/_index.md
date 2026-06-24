---
title: "RecognizePdf"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "التعرف على النص من ملف PDF ممسوح ضوئياً واستخراج الصور. يتعرف على ملف PDF مع القدرة على تحديد DocumentRecognitionSettingsaspose.ocr/documentrecognitionsettings. يدعم PDF الممسوح ضوئياً فقط. لا يدعم PDF القابل للبحث."
type: docs
weight: 220
url: /ar/net/aspose.ocr/asposeocr/recognizepdf/
---
## RecognizePdf(string, DocumentRecognitionSettings) {#recognizepdf_1}

التعرف على النص من ملف PDF ممسوح ضوئياً (استخراج الصور). يتعرف على ملف PDF مع القدرة على تحديد [`DocumentRecognitionSettings`](../../documentrecognitionsettings). يدعم PDF الممسوح ضوئياً فقط. لا يدعم PDF القابل للبحث.

```csharp
public List<RecognitionResult> RecognizePdf(string fullPath, DocumentRecognitionSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath | String | المسار الكامل للصورة. |
| الإعدادات | DocumentRecognitionSettings | إعدادات التعرف. |

### قيمة الإرجاع

كائن [`RecognitionResult`](../../recognitionresult) مع نتائج التعرف على الصورة.

### انظر أيضًا

* class [RecognitionResult](../../recognitionresult)
* class [DocumentRecognitionSettings](../../documentrecognitionsettings)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

---

## RecognizePdf(MemoryStream, DocumentRecognitionSettings) {#recognizepdf}

التعرف على النص من ملف PDF ممسوح ضوئياً (استخراج الصور). يتعرف على ملف PDF مع القدرة على تحديد [`RecognitionSettings`](../../recognitionsettings). يدعم PDF الممسوح ضوئياً فقط. لا يدعم PDF القابل للبحث.

```csharp
public List<RecognitionResult> RecognizePdf(MemoryStream stream, 
    DocumentRecognitionSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | MemoryStream | دفق الذاكرة مع ملف PDF. |
| الإعدادات | DocumentRecognitionSettings | إعدادات التعرف. |

### قيمة الإرجاع

كائن [`RecognitionResult`](../../recognitionresult) مع نتائج التعرف على الصورة.

### انظر أيضًا

* class [RecognitionResult](../../recognitionresult)
* class [DocumentRecognitionSettings](../../documentrecognitionsettings)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
