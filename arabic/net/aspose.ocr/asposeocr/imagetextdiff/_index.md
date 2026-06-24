---
title: "ImageTextDiff"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "قارن النصوص على الصورتين وأعد رقمًا يمثل مدى تشابههما من 0 إلى 1."
type: docs
weight: 130
url: /ar/net/aspose.ocr/asposeocr/imagetextdiff/
---
## AsposeOcr.ImageTextDiff method

قارن النصوص على الصورتين وأرجع رقمًا يمثل مدى تشابههما (من 0 إلى 1).

```csharp
public float ImageTextDiff(string fullPath1, string fullPath2, RecognitionSettings settings = null, 
    bool ignoreCase = true, bool autoSkew = true)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath1 | String | المسار إلى الصورة الأولى. |
| fullPath2 | String | المسار إلى الصورة الثانية. |
| الإعدادات | RecognitionSettings | إعدادات التعرف. |
| ignoreCase | Boolean | True - يعني بحث غير حساس لحالة الأحرف. |
| autoSkew | Boolean | يفعل تصحيح الميل التلقائي للصورة. |

### قيمة الإرجاع

0 يعني أن النصوص مختلفة تمامًا؛ 1 يعني أن النصوص متطابقة.

### انظر أيضًا

* class [RecognitionSettings](../../recognitionsettings)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
