---
title: "Save"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "احفظ جميع نتائج التعرف إلى ملف."
type: docs
weight: 50
url: /ar/net/aspose.ocr/ocroutput/save/
---
## Save(string, SaveFormat, string, PdfOptimizationMode) {#save_1}

احفظ جميع نتائج التعرف إلى ملف.

```csharp
public void Save(string fullFileName, SaveFormat saveFormat = SaveFormat.Text, 
    string embeddedFontPath = null, 
    PdfOptimizationMode optimizePdf = PdfOptimizationMode.MAXIMUM_QUALITY)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fullFileName | String | اسم الملف مع مسار لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | SaveFormat | تنسيق المستند (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | String | اختياريًا. المسار الكامل إلى خط المستخدم. |
| optimizePdf | PdfOptimizationMode | تقليل حجم ملف PDF عن طريق خفض جودة الصور الخلفية. بشكل افتراضي، يتم الحفاظ على جودة الصورة الأصلية. |

### انظر أيضًا

* enum [SaveFormat](../../saveformat)
* enum [PdfOptimizationMode](../../pdfoptimizationmode)
* class [OcrOutput](../../ocroutput)
* namespace [Aspose.OCR](../../ocroutput)
* assembly [Aspose.OCR](../../../)

---

## Save(MemoryStream, SaveFormat, string, PdfOptimizationMode) {#save}

احفظ جميع نتائج التعرف إلى تدفق الذاكرة بالتنسيق المحدد.

```csharp
public void Save(MemoryStream stream, SaveFormat saveFormat = SaveFormat.Text, 
    string embeddedFontPath = null, 
    PdfOptimizationMode optimizePdf = PdfOptimizationMode.MAXIMUM_QUALITY)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | MemoryStream | MemoryStream لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | SaveFormat | تنسيق المستند (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | String | اختياريًا. المسار الكامل إلى خط المستخدم. |
| optimizePdf | PdfOptimizationMode | تقليل حجم ملف PDF عن طريق خفض جودة الصور الخلفية. بشكل افتراضي، يتم الحفاظ على جودة الصورة الأصلية. |

### انظر أيضًا

* enum [SaveFormat](../../saveformat)
* enum [PdfOptimizationMode](../../pdfoptimizationmode)
* class [OcrOutput](../../ocroutput)
* namespace [Aspose.OCR](../../ocroutput)
* assembly [Aspose.OCR](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
