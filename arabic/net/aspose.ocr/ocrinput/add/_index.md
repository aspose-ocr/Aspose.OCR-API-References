---
title: "Add"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "أضف المسار أو URI الذي يحتوي على الصورة للتعرف / المعالجة. يجب أن يتطابق نوع الصورة مع النوع المحدد في المنشئ."
type: docs
weight: 30
url: /ar/net/aspose.ocr/ocrinput/add/
---
## Add(string) {#add_4}

أضف المسار أو URI الذي يحتوي على الصورة للتعرف / المعالجة. يجب أن يتطابق نوع الصورة مع النوع المحدد في المنشئ.

```csharp
public void Add(string fullPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath | String | المسار إلى الصورة/ المستند / المجلد / الأرشيف. |

### انظر أيضًا

* class [OcrInput](../../ocrinput)
* namespace [Aspose.OCR](../../ocrinput)
* assembly [Aspose.OCR](../../../)

---

## Add(MemoryStream) {#add_2}

أضف تدفق الذاكرة الذي يحتوي على الصورة للتعرف / المعالجة. يجب أن يتطابق نوع الصورة مع النوع المحدد في المنشئ.

```csharp
public void Add(MemoryStream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | MemoryStream | دفق الذاكرة الذي يحتوي على الصورة أو المستند. |

### انظر أيضًا

* class [OcrInput](../../ocrinput)
* namespace [Aspose.OCR](../../ocrinput)
* assembly [Aspose.OCR](../../../)

---

## Add(string, int, int) {#add_5}

أضف الصور / المستندات متعددة الصفحات للتعرف / المعالجة. يجب أن يتطابق نوع الصورة مع النوع المحدد في المنشئ.

```csharp
public void Add(string fullPath, int startPage, int pagesCount)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath | String | المسار إلى الصورة/ المستند / المجلد / الأرشيف. |
| startPage | Int32 | الصفحة/الصورة الأولى للمعالجة / التعرف. استخدم للمستندات، zip، المجلدات. |
| pagesCount | Int32 | العدد الإجمالي للصفحات/الصور للمعالجة / التعرف. استخدم للمستندات، zip، المجلدات. الافتراضي = 1. |

### انظر أيضًا

* class [OcrInput](../../ocrinput)
* namespace [Aspose.OCR](../../ocrinput)
* assembly [Aspose.OCR](../../../)

---

## Add(MemoryStream, int, int) {#add_3}

أضف تدفق الذاكرة الذي يحتوي على الصورة متعددة الصفحات للتعرف / المعالجة. يجب أن يتطابق نوع الصورة مع النوع المحدد في المنشئ.

```csharp
public void Add(MemoryStream stream, int startPage, int pagesCount)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | MemoryStream | دفق الذاكرة الذي يحتوي على المستند متعدد الصفحات. |
| startPage | Int32 | الصفحة/الصورة الأولى للمعالجة / التعرف. استخدم للمستندات. |
| pagesCount | Int32 | العدد الإجمالي للصفحات/الصور للمعالجة / التعرف. استخدم للمستندات. الافتراضي = 1. |

### انظر أيضًا

* class [OcrInput](../../ocrinput)
* namespace [Aspose.OCR](../../ocrinput)
* assembly [Aspose.OCR](../../../)

---

## Add(byte[], int, int, PixelType) {#add_1}

أضف الصورة المفكوكة إلى القائمة للتعرف / المعالجة. يجب أن يتطابق نوع الصورة مع النوع المحدد في المنشئ (SingleImage).

```csharp
public void Add(byte[] arr, int width, int height, PixelType pixelFormat)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| arr | Byte[] | الصورة المفكوكة في مصفوفة Aspose.Drawing.Color. |
| العرض | Int32 | عرض الصورة. |
| الارتفاع | Int32 | ارتفاع الصورة. |
| تنسيق البكسل | PixelType | يدعم byte، rgb، bgr، rgba. |

### انظر أيضًا

* enum [PixelType](../../pixeltype)
* class [OcrInput](../../ocrinput)
* namespace [Aspose.OCR](../../ocrinput)
* assembly [Aspose.OCR](../../../)

---

## Add(Color[], int, int) {#add}

أضف الصورة المفكوكة إلى القائمة للتعرف / المعالجة. يجب أن يتطابق نوع الصورة مع النوع المحدد في المنشئ (SingleImage).

```csharp
public void Add(Color[] imageData, int width, int height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| imageData | Color[] | الصورة المفكوكة في مصفوفة Aspose.Drawing.Color. |
| العرض | Int32 | عرض الصورة. |
| الارتفاع | Int32 | ارتفاع الصورة. |

### انظر أيضًا

* class [OcrInput](../../ocrinput)
* namespace [Aspose.OCR](../../ocrinput)
* assembly [Aspose.OCR](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
