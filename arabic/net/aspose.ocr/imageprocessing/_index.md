---
title: "معالجة الصور"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "فئة مساعدة لمكتبة Aspose OCR. تسمح بمعالجة الصور مسبقًا وحفظها."
type: docs
weight: 310
url: /ar/net/aspose.ocr/imageprocessing/
---
## ImageProcessing class

فئة مساعدة لمكتبة Aspose OCR. تسمح بمعالجة الصور مسبقًا وحفظها.

```csharp
public static class ImageProcessing
```

## Methods

| Name | الوصف |
| --- | --- |
| static [Render](../../aspose.ocr/imageprocessing/render)(OcrInput) | استخدم معالجة الصور لتحسين دقة OCR. أنشئ قائمة من المرشحات التي سيتم تطبيقها على الصورة المدخلة بالترتيب الذي تحدده. مثال لإنشاء المرشحات: PreprocessingFilter filters = new PreprocessingFilter { PreprocessingFilter.Invert(), PreprocessingFilter.Threshold(150), PreprocessingFilter.Binarize(), PreprocessingFilter.Rotate(180), PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box), PreprocessingFilter.Scale(6f), PreprocessingFilter.Dilate() }; لا تحتاج إلى جميعها. عيّن فقط ما تحتاجه. |
| static [Save](../../aspose.ocr/imageprocessing/save)(OcrInput, string) | استخدم معالجة الصور لتحسين دقة OCR. أنشئ قائمة من المرشحات التي سيتم تطبيقها على الصورة المدخلة بالترتيب الذي تحدده. مثال لإنشاء المرشحات: PreprocessingFilter filters = new PreprocessingFilter { PreprocessingFilter.Invert(), PreprocessingFilter.Threshold(150), PreprocessingFilter.Binarize(), PreprocessingFilter.Rotate(180), PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box), PreprocessingFilter.Scale(6f), PreprocessingFilter.Dilate() }; لا تحتاج إلى جميعها. عيّن فقط ما تحتاجه. |

### انظر أيضًا

* namespace [Aspose.OCR](../../aspose.ocr)
* assembly [Aspose.OCR](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
