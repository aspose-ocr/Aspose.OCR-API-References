---
title: "RecognizeImage"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "يتعرف على النص على الصورة."
type: docs
weight: 140
url: /ar/net/aspose.ocr/asposeocr/recognizeimage/
---
## RecognizeImage(string) {#recognizeimage_5}

يتعرف على النص على الصورة.

```csharp
public string RecognizeImage(string fullPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath | String | المسار إلى الصورة. |

### قيمة الإرجاع

النص المتعرف عليه.

### ملاحظات

يستخدم تصحيح الانحراف التلقائي للصورة واكتشاف مناطق النص. يدعم GIF, PNG, JPEG, BMP, TIFF, JFIF.

### انظر أيضًا

* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

---

## RecognizeImage(string, RecognitionSettings) {#recognizeimage_3}

يتعرف على النص على الصورة.

```csharp
public RecognitionResult RecognizeImage(string fullPath, RecognitionSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath | String | المسار إلى الصورة. |
| settings | RecognitionSettings | إعدادات التعرف. |

### قيمة الإرجاع

كائن [`RecognitionResult`](../../recognitionresult) مع نتائج التعرف على الصورة.

### ملاحظات

يتعرف على الصورة مع إمكانية تحديد [`RecognitionSettings`](../../recognitionsettings). يدعم GIF, PNG, JPEG, BMP, TIFF, JFIF.

### انظر أيضًا

* class [RecognitionResult](../../recognitionresult)
* class [RecognitionSettings](../../recognitionsettings)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

---

## RecognizeImage(MemoryStream) {#recognizeimage_4}

يتعرف على النص على الصورة.

```csharp
public string RecognizeImage(MemoryStream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | MemoryStream | دفق الذاكرة الذي يحتوي على الصورة. |

### قيمة الإرجاع

النص المتعرف عليه.

### ملاحظات

يستخدم تصحيح الانحراف التلقائي للصورة واكتشاف مناطق النص. يدعم GIF, PNG, JPEG, BMP, TIFF, JFIF.

### انظر أيضًا

* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

---

## RecognizeImage(MemoryStream, RecognitionSettings) {#recognizeimage_2}

يتعرف على النص على الصورة. يتعرف على الصورة مع القدرة على تحديد [`RecognitionSettings`](../../recognitionsettings). يدعم GIF, PNG, JPEG, BMP, TIFF, JFIF.

```csharp
public RecognitionResult RecognizeImage(MemoryStream stream, RecognitionSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | MemoryStream | دفق الذاكرة الذي يحتوي على الصورة. |
| settings | RecognitionSettings | إعدادات التعرف. |

### قيمة الإرجاع

كائن [`RecognitionResult`](../../recognitionresult) مع نتائج التعرف على الصورة.

### انظر أيضًا

* class [RecognitionResult](../../recognitionresult)
* class [RecognitionSettings](../../recognitionsettings)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

---

## RecognizeImage(byte[], int, int, PixelType, RecognitionSettings) {#recognizeimage_1}

يتعرف على النص على الصورة.

```csharp
public RecognitionResult RecognizeImage(byte[] imageData, int width, int height, 
    PixelType pixelFormat, RecognitionSettings settings = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| imageData | Byte[] | الصورة المفكوكة في مصفوفة بايتات. يستخدم تقنية إضاءة RGB للـ bitsPerPixel &gt; 1. |
| العرض | Int32 | عرض الصورة. |
| الارتفاع | Int32 | ارتفاع الصورة. |
| تنسيق البكسل | PixelType | يدعم byte، rgb، bgr، rgba. |
| settings | RecognitionSettings | إعدادات التعرف. |

### قيمة الإرجاع

كائن [`RecognitionResult`](../../recognitionresult) مع نتائج التعرف على الصورة.

### ملاحظات

يتعرف على الصورة مع إمكانية تحديد [`RecognitionSettings`](../../recognitionsettings). يدعم بيانات البايت المفكوكة على شكل صف.

### انظر أيضًا

* class [RecognitionResult](../../recognitionresult)
* enum [PixelType](../../pixeltype)
* class [RecognitionSettings](../../recognitionsettings)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

---

## RecognizeImage(Color[], int, int, RecognitionSettings) {#recognizeimage}

يتعرف على النص على الصورة.

```csharp
public RecognitionResult RecognizeImage(Color[] imageData, int width, int height, 
    RecognitionSettings settings = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| imageData | Color[] | الصورة المفكوكة في مصفوفة Aspose.Drawing.Color. |
| العرض | Int32 | عرض الصورة. |
| الارتفاع | Int32 | ارتفاع الصورة. |
| settings | RecognitionSettings | إعدادات التعرف. |

### قيمة الإرجاع

كائن [`RecognitionResult`](../../recognitionresult) مع نتائج التعرف على الصورة.

### ملاحظات

يتعرف على الصورة مع إمكانية تحديد [`RecognitionSettings`](../../recognitionsettings). يدعم بيانات البايت المفكوكة على شكل صف.

### انظر أيضًا

* class [RecognitionResult](../../recognitionresult)
* class [RecognitionSettings](../../recognitionsettings)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.OCR.dll -->
