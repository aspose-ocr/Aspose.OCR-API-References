---
title: "DetectRectangles"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "يكتشف مناطق النص على الصور. يدعم GIF PNG JPEG BMP TIFF JFIF تدفق ومجلد ومصفوفات وأرشيفات."
type: docs
weight: 90
url: /ar/net/aspose.ocr/asposeocr/detectrectangles/
---
## DetectRectangles(OcrInput) {#detectrectangles}

يكتشف مناطق النص على الصور. يدعم GIF، PNG، JPEG، BMP، TIFF، JFIF، التدفق، المجلد، المصفوفات، الأرشيفات.

```csharp
public List<RectangleOutput> DetectRectangles(OcrInput images)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| images | OcrInput | الحاوية التي تحتوي على المصادر.[`OcrInput`](../../ocrinput) |

### قيمة الإرجاع

قائمة من [`RectangleOutput`](../../rectangleoutput) مع مناطق النص المكتشفة أو السطور.

### انظر أيضًا

* class [RectangleOutput](../../rectangleoutput)
* class [OcrInput](../../ocrinput)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

---

## DetectRectangles(OcrInput, AreasType, bool) {#detectrectangles_1}

يكتشف مناطق النص على الصور. يدعم GIF، PNG، JPEG، BMP، TIFF، JFIF، التدفق، المجلد، المصفوفات، الأرشيفات.

```csharp
public List<RectangleOutput> DetectRectangles(OcrInput images, AreasType areasType, 
    bool detectAreas = true)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| images | OcrInput | الحاوية التي تحتوي على المصادر.[`OcrInput`](../../ocrinput) |
| areasType | AreasType | يحدد أي المستطيلات تُرجع - سطر أو فقرات. |
| detectAreas | Boolean | تمكين الكشف التلقائي عن مناطق النص. |

### قيمة الإرجاع

قائمة من [`RectangleOutput`](../../rectangleoutput) مع مناطق النص المكتشفة أو السطور.

### انظر أيضًا

* class [RectangleOutput](../../rectangleoutput)
* class [OcrInput](../../ocrinput)
* enum [AreasType](../../areastype)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
