---
title: "ImageHasText"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "تحقق مما إذا كانت الصورة تحتوي على الجزء النصي المقدم."
type: docs
weight: 120
url: /ar/net/aspose.ocr/asposeocr/imagehastext/
---
## ImageHasText(string, string, RecognitionSettings, bool, bool) {#imagehastext}

تحقق مما إذا كانت الصورة تحتوي على الجزء النصي المقدم.

```csharp
public bool ImageHasText(string fullPath, string text, RecognitionSettings settings = null, 
    bool ignoreCase = true, bool autoSkew = true)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath | String | المسار إلى الصورة. |
| نص | String | جزء النص للبحث على الصورة. |
| الإعدادات | RecognitionSettings | إعدادات التعرف. |
| ignoreCase | Boolean | True - يعني بحث غير حساس لحالة الأحرف. |
| autoSkew | Boolean | يفعل تصحيح الميل التلقائي للصورة. |

### قيمة الإرجاع

صحيح إذا كانت الصورة تحتوي على جزء نص. خطأ - الصورة لا تحتوي على جزء نص.

### ملاحظات

يتعرف على الصورة مع إمكانية تحديد [`RecognitionSettings`](../../recognitionsettings). يدعم GIF، PNG، JPEG، BMP، TIFF، JFIF.

### انظر أيضًا

* class [RecognitionSettings](../../recognitionsettings)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

---

## ImageHasText(string, Regex, RecognitionSettings, bool) {#imagehastext_1}

تحقق مما إذا كان نص الصورة يطابق التعبير النمطي المقدم.

```csharp
public bool ImageHasText(string fullPath, Regex regex, RecognitionSettings settings = null, 
    bool autoSkew = true)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath | String | المسار إلى الصورة. |
| regex | Regex | كائن System.Text.RegularExpressions مع النمط والخيارات المقدمة. |
| الإعدادات | RecognitionSettings | إعدادات التعرف. |
| autoSkew | Boolean | يفعل تصحيح الميل التلقائي للصورة. |

### قيمة الإرجاع

صحيح إذا كان نص الصورة يطابق التعبير النمطي المقدم.

### ملاحظات

يتعرف على الصورة مع إمكانية تحديد [`RecognitionSettings`](../../recognitionsettings). يدعم GIF، PNG، JPEG، BMP، TIFF، JFIF.

### انظر أيضًا

* class [RecognitionSettings](../../recognitionsettings)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
