---
title: "Save"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "استخدم معالجة الصور لتحسين دقة OCR. أنشئ قائمة بالمرشحات التي سيتم تطبيقها على صورة الإدخال بالترتيب الذي تحدده. مثال لإنشاء مرشحات PreprocessingFilter filters new PreprocessingFilter PreprocessingFilter.Invert PreprocessingFilter.Threshold150 PreprocessingFilter.Binarize PreprocessingFilter.Rotate180 PreprocessingFilter.Resize30003000 Aspose.OCR.Filters.InterpolationFilterType.Box PreprocessingFilter.Scale6f PreprocessingFilter.Dilate لا تحتاج إلى جميعها. اضبط فقط ما تحتاجه."
type: docs
weight: 20
url: /ar/net/aspose.ocr/imageprocessing/save/
---
## ImageProcessing.Save method

استخدم معالجة الصور لتحسين دقة OCR. أنشئ قائمة من المرشحات التي سيتم تطبيقها على الصورة المدخلة بالترتيب الذي تحدده. مثال لإنشاء المرشحات: PreprocessingFilter filters = new PreprocessingFilter { PreprocessingFilter.Invert(), PreprocessingFilter.Threshold(150), PreprocessingFilter.Binarize(), PreprocessingFilter.Rotate(180), PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box), PreprocessingFilter.Scale(6f), PreprocessingFilter.Dilate() }; لا تحتاج إلى جميعها. عيّن فقط ما تحتاجه.

```csharp
public static OcrInput Save(OcrInput images, string folderPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| images | OcrInput | كائن OcrInput يحتوي على صور مختلفة [`OcrInput`](../../ocrinput). |
| folderPath | String | المسار بدون أسماء الصور لحفظ الصور المعالجة. |

### قيمة الإرجاع

كائن OcrInput يحتوي على الصور المعالجة الناتجة [`OcrInput`](../../ocrinput).

### انظر أيضًا

* class [OcrInput](../../ocrinput)
* class [ImageProcessing](../../imageprocessing)
* namespace [Aspose.OCR](../../imageprocessing)
* assembly [Aspose.OCR](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
