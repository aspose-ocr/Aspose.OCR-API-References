---
title: "PreprocessingFilter"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "الفئة الأساسية لأوامر معالجة الصورة."
type: docs
weight: 530
url: /ar/net/aspose.ocr.models.preprocessingfilters/preprocessingfilter/
---
## PreprocessingFilter class

الفئة الأساسية لأوامر معالجة الصورة.

الفئة الأساسية لأوامر معالجة الصورة.

```csharp
public class PreprocessingFilter : IEnumerable
```

## Constructors

| Name | الوصف |
| --- | --- |
| [PreprocessingFilter](preprocessingfilter)() | المُنشئ الافتراضي. |

## Properties

| Name | الوصف |
| --- | --- |
| static [Default](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/default) { get; } | مجموعة الفلاتر الافتراضية تحتوي على مرشح AutoSkew |
| static [Empty](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/empty) { get; } | مجموعة الفلاتر فارغة |

## Methods

| Name | الوصف |
| --- | --- |
| static [AutoDenoising](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/autodenoising#autodenoising)() | يفعل استخدام شبكة عصبية إضافية لتحسين الصورة - تقليل الضوضاء. مفيد للصور التي تحتوي على عيوب مسح، تشوهات، بقع، توهجات، تدرجات، عناصر غريبة. |
| static [AutoDenoising](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/autodenoising#autodenoising_1)(Rectangle) | يمكّن من استخدام شبكة عصبية إضافية لتحسين جزء الصورة - تقليل الضوضاء. مفيد للصور التي تحتوي على عيوب المسح، التشوه، البقع، الوهج، التدرجات، العناصر الغريبة. |
| static [AutoDewarping](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/autodewarping)() | يصحح تلقائيًا التشوهات الهندسية في الصورة. يتطلب موارد عالية جدًا! |
| static [AutoSkew](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/autoskew#autoskew)() | يفعل تصحيح الميل التلقائي للصورة. |
| static [AutoSkew](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/autoskew#autoskew_1)(Rectangle) | يمكّن من تصحيح الانحراف التلقائي لجزء الصورة. |
| static [Binarize](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/binarize#binarize)() | يحوّل الصورة إلى صورة بالأبيض والأسود. الصور الثنائية هي صور تكون بكسلاتها ذات قيمتين سطوع فقط. عادةً ما تُعرض باللونين الأسود والأبيض. عدديًا، القيمتان غالبًا ما تكون 0 للون الأسود و255 للأبيض. تُنتج الصور الثنائية عبر تطبيق عتبة تلقائية على الصورة. |
| static [Binarize](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/binarize#binarize_1)(Rectangle) | يحوّل جزءًا من الصورة إلى صورة بالأبيض والأسود. الصور الثنائية هي صور تكون بكسلاتها ذات قيمتين سطوع فقط. عادةً ما تُعرض باللونين الأسود والأبيض. عدديًا، القيمتان غالبًا ما تكون 0 للون الأسود و255 للأبيض. تُنتج الصور الثنائية عبر تطبيق عتبة تلقائية على الصورة. |
| static [ContrastCorrectionFilter](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/contrastcorrectionfilter#contrastcorrectionfilter)() | مرشح تصحيح التباين. |
| static [ContrastCorrectionFilter](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/contrastcorrectionfilter#contrastcorrectionfilter_1)(Rectangle) | مرشح تصحيح التباين لجزء الصورة. |
| static [Dilate](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/dilate#dilate)() | الإنتشار يضيف بكسلات إلى حدود الكائنات في الصورة. |
| static [Dilate](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/dilate#dilate_1)(Rectangle) | يضيف التوسيع بكسلات إلى حدود الكائنات في جزء من الصورة. |
| static [Invert](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/invert#invert)() | يقلب الألوان تلقائيًا في صورة مستند. |
| static [Invert](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/invert#invert_1)(Rectangle) | يقلب الألوان تلقائيًا في جزء من الصورة. |
| static [Median](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/median#median)() | يقوم مرشح الوسيط بالتمرير عبر كل عنصر من الصورة ويستبدل كل بكسل بوسيط بكسلاته المجاورة. |
| static [Median](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/median#median_1)(Rectangle) | يقوم مرشح الوسيط بالتمرير عبر كل عنصر من جزء الصورة ويستبدل كل بكسل بوسيط بكسلاته المجاورة. |
| static [Resize](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/resize#resize)(int, int) | إعادة تحجيم الصورة - تكبير أو تصغير دقة الصورة. InterpolationFilterType = Lanczos8 |
| static [Resize](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/resize#resize_1)(int, int, InterpolationFilterType) | إعادة تحجيم الصورة - تكبير أو تصغير دقة الصورة. |
| static [Rotate](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/rotate#rotate)(float) | تدوير الصورة الأصلية. |
| static [Rotate](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/rotate#rotate_1)(float, Rectangle) | تدوير جزء من الصورة. |
| static [Scale](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/scale#scale)(float) | إعادة تحجيم الصورة - تكبير أو تصغير دقة الصورة. InterpolationFilterType = Lanczos8 |
| static [Scale](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/scale#scale_1)(float, InterpolationFilterType) | إعادة تحجيم الصورة - تكبير أو تصغير دقة الصورة. |
| static [Threshold](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/threshold#threshold)(int) | إنشاء صورة ثنائية بناءً على ضبط قيمة العتبة لشدة بكسل الصورة الأصلية. |
| static [Threshold](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/threshold#threshold_1)(int, Rectangle) | إنشاء جزء ثنائي من الصورة بناءً على ضبط قيمة العتبة لشدة بكسل جزء الصورة الأصلية. |
| static [ToGrayscale](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/tograyscale)() | يحوّل الصورة إلى صورة رمادية. الصورة الرمادية تحتوي على 256 مستوى إضاءة في الصورة (من 0 إلى 255). |
| [Add](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/add)(PreprocessingFilter) | أضف المرشح الجديد إلى المجموعة لتشغيل جميع العمليات لاحقًا. التناسق في المجموعة مهم. |
| [GetEnumerator](../../aspose.ocr.models.preprocessingfilters/preprocessingfilter/getenumerator)() | لتحقيق واجهة IEnumarable. |

### انظر أيضًا

* namespace [Aspose.OCR.Models.PreprocessingFilters](../../aspose.ocr.models.preprocessingfilters)
* assembly [Aspose.OCR](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
