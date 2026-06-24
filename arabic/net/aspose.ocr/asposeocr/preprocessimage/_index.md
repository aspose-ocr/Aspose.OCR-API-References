---
title: "PreprocessImage"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "استخدم ما قبل معالجة الصورة لتحسين دقة OCR. أنشئ قائمة من الفلاتر التي سيتم تطبيقها على الصورة المدخلة بالترتيب الذي تحدده. مثال لإنشاء الفلاتر PreprocessingFilter filters  new PreprocessingFilter  PreprocessingFilter.Invert PreprocessingFilter.Threshold150 PreprocessingFilter.Binarize PreprocessingFilter.Rotate180 PreprocessingFilter.Resize30003000 Aspose.OCR.Filters.InterpolationFilterType.Box PreprocessingFilter.Scale6f PreprocessingFilter.Dilate  لا تحتاج إلى جميعها. اضبط فقط ما تحتاجه."
type: docs
weight: 100
url: /ar/net/aspose.ocr/asposeocr/preprocessimage/
---
## PreprocessImage(string, PreprocessingFilter) {#preprocessimage_1}

استخدم ما قبل معالجة الصورة لتحسين دقة OCR. أنشئ قائمة من الفلاتر التي سيتم تطبيقها على الصورة المدخلة بالترتيب الذي تحدده. مثال لإنشاء الفلاتر: PreprocessingFilter filters = new PreprocessingFilter { PreprocessingFilter.Invert(), PreprocessingFilter.Threshold(150), PreprocessingFilter.Binarize(), PreprocessingFilter.Rotate(180), PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box), PreprocessingFilter.Scale(6f), PreprocessingFilter.Dilate() }; لا تحتاج إلى جميعها. اضبط فقط ما تحتاجه.

```csharp
public MemoryStream PreprocessImage(string fullPath, PreprocessingFilter filters)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath | String | المسار الكامل للصورة. |
| filters | PreprocessingFilter | فلاتر تحسين الصورة[`PreprocessingFilter`](../../../aspose.ocr.models.preprocessingfilters/preprocessingfilter). |

### قيمة الإرجاع

تيار يحتوي على صورة معدلة حتى تتمكن من حفظها أو التعرف عليها.

### انظر أيضًا

* class [PreprocessingFilter](../../../aspose.ocr.models.preprocessingfilters/preprocessingfilter)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

---

## PreprocessImage(MemoryStream, PreprocessingFilter) {#preprocessimage}

استخدم ما قبل معالجة الصورة لتحسين دقة OCR. أنشئ قائمة من الفلاتر التي سيتم تطبيقها على الصورة المدخلة بالترتيب الذي تحدده. مثال لإنشاء الفلاتر: PreprocessingFilter filters = new PreprocessingFilter { PreprocessingFilter.Invert(), PreprocessingFilter.Threshold(150), PreprocessingFilter.Binarize(), PreprocessingFilter.Rotate(180), PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box), PreprocessingFilter.Scale(6f), PreprocessingFilter.Dilate() }; لا تحتاج إلى جميعها. اضبط فقط ما تحتاجه.

```csharp
public MemoryStream PreprocessImage(MemoryStream stream, PreprocessingFilter filters)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | MemoryStream | دفق الذاكرة الذي يحتوي على الصورة. |
| filters | PreprocessingFilter | فلاتر تحسين الصورة[`PreprocessingFilter`](../../../aspose.ocr.models.preprocessingfilters/preprocessingfilter). |

### قيمة الإرجاع

تيار يحتوي على صورة معدلة حتى تتمكن من حفظها أو التعرف عليها.

### انظر أيضًا

* class [PreprocessingFilter](../../../aspose.ocr.models.preprocessingfilters/preprocessingfilter)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
