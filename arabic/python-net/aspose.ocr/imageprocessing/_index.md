---
title: "ImageProcessing"
second_title: "مرجع API لـ Aspose.OCR للبايثون عبر .NET"
description: 
type: docs
weight: 120
url: /ar/python-net/aspose.ocr/imageprocessing/
---

## ImageProcessing class

فئة مساعدة لمكتبة Aspose OCR. تسمح بتهيئة مسبقة وحفظ الصور.

نوع ImageProcessing يعرض الأعضاء التالية:
## Methods
| الاسم | الوصف |
| :- | :- |
| save(images, folder_path) | استخدم معالجة الصور لتحسين دقة OCR.<br/>            أنشئ قائمة من المرشحات التي سيتم تطبيقها على الصورة المدخلة بالترتيب الذي تحدده.<br/>            مثال لإنشاء المرشحات:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            ليس عليك استخدام جميعها. اضبط فقط ما تحتاجه. |
| render(images) | استخدم معالجة الصور لتحسين دقة OCR.<br/>            أنشئ قائمة من المرشحات التي سيتم تطبيقها على الصورة المدخلة بالترتيب الذي تحدده.<br/>            مثال لإنشاء المرشحات:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            ليس عليك استخدام جميعها. اضبط فقط ما تحتاجه. |

### انظر أيضاً

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

