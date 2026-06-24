---
title: "عرض"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "استخدم معالجة الصور لتحسين دقة OCR. أنشئ قائمة من الفلاتر التي سيتم تطبيقها على الصورة المدخلة بالترتيب الذي تحدده. مثال لإنشاء الفلاتر PreprocessingFilter filters  new PreprocessingFilter  PreprocessingFilter.Invert PreprocessingFilter.Threshold150 PreprocessingFilter.Binarize PreprocessingFilter.Rotate180 PreprocessingFilter.Resize30003000 Aspose.OCR.Filters.InterpolationFilterType.Box PreprocessingFilter.Scale6f PreprocessingFilter.Dilate  لا تحتاج إلى جميعها. قم بتعيين ما تحتاجه فقط."
type: docs
weight: 10
url: /ar/net/aspose.ocr/imageprocessing/render/
---
## ImageProcessing.Render method

استخدم معالجة الصور لتحسين دقة OCR. أنشئ قائمة من المرشحات التي سيتم تطبيقها على الصورة المدخلة بالترتيب الذي تحدده. مثال لإنشاء المرشحات: PreprocessingFilter filters = new PreprocessingFilter { PreprocessingFilter.Invert(), PreprocessingFilter.Threshold(150), PreprocessingFilter.Binarize(), PreprocessingFilter.Rotate(180), PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box), PreprocessingFilter.Scale(6f), PreprocessingFilter.Dilate() }; لا تحتاج إلى جميعها. عيّن فقط ما تحتاجه.

```csharp
public static OcrInput Render(OcrInput images)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| images | OcrInput | كائن OcrInput يحتوي على صور مختلفة [`OcrInput`](../../ocrinput). |

### قيمة الإرجاع

كائن OcrInput يحتوي على صور معالجة نتيجة في حقل التدفق [`OcrInput`](../../ocrinput).

### انظر أيضًا

* class [OcrInput](../../ocrinput)
* class [ImageProcessing](../../imageprocessing)
* namespace [Aspose.OCR](../../imageprocessing)
* assembly [Aspose.OCR](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
