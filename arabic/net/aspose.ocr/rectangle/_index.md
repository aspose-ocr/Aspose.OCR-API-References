---
title: "Rectangle"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "يخزن مجموعة من أربعة أعداد صحيحة تمثل موقع وحجم المستطيل."
type: docs
weight: 440
url: /ar/net/aspose.ocr/rectangle/
---
## Rectangle structure

يخزن مجموعة من أربعة أعداد صحيحة تمثل موقع وحجم المستطيل.

```csharp
public struct Rectangle
```

## Constructors

| Name | الوصف |
| --- | --- |
| [Rectangle](rectangle)(int, int, int, int) | ينشئ نسخة جديدة من بنية [`Rectangle`](../rectangle) بالموقع والحجم المحددين. |

## Properties

| Name | الوصف |
| --- | --- |
| static [Empty](../../aspose.ocr/rectangle/empty) { get; } | يحصل على نسخة جديدة من بنية [`Rectangle`](../rectangle) التي تكون قيم [`X`](./x) و[`Y`](./y) و[`Width`](./width) و[`Height`](./height) فيها صفر. |
| [Bottom](../../aspose.ocr/rectangle/bottom) { get; set; } | يحصل أو يعيّن الإحداثي y الذي هو مجموع قيم الخاصيتين [`Y`](./y) و[`Height`](./height) لهذا الهيكل [`Rectangle`](../rectangle). |
| [IsEmpty](../../aspose.ocr/rectangle/isempty) { get; } | يحصل على قيمة تشير إلى ما إذا كانت جميع الخصائص الرقمية لهذا [`Rectangle`](../rectangle) تساوي الصفر. |
| [Left](../../aspose.ocr/rectangle/left) { get; set; } | يحصل أو يعيّن الإحداثي x للحافة اليسرى لهذا الهيكل [`Rectangle`](../rectangle). |
| [Right](../../aspose.ocr/rectangle/right) { get; set; } | يحصل أو يعيّن الإحداثي x الذي هو مجموع قيم الخاصيتين [`X`](./x) و[`Width`](./width) لهذا الهيكل [`Rectangle`](../rectangle). |
| [Top](../../aspose.ocr/rectangle/top) { get; set; } | يحصل أو يعيّن إحداثي الصادي للحد العلوي لهذا الهيكل [`Rectangle`](../rectangle). |

## Methods

| Name | الوصف |
| --- | --- |
| [Contains](../../aspose.ocr/rectangle/contains)(int, int) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل [`Rectangle`](../rectangle). |
| override [Equals](../../aspose.ocr/rectangle/equals)(object) | يفحص ما إذا كان *obj* هو هيكل [`Rectangle`](../rectangle) بنفس الموقع والحجم لهذا الهيكل [`Rectangle`](../rectangle). |
| override [GetHashCode](../../aspose.ocr/rectangle/gethashcode)() | يعيد رمز التجزئة لهذا الهيكل [`Rectangle`](../rectangle). |
| override [ToString](../../aspose.ocr/rectangle/tostring)() | يحوّل خصائص هذا الهيكل [`Rectangle`](../rectangle) إلى سلسلة قابلة للقراءة البشرية. |
| [operator ==](../../aspose.ocr/rectangle/op_equality) | يفحص ما إذا كان هيكلا [`Rectangle`](../rectangle) متساويين في الموقع والحجم. |
| [operator !=](../../aspose.ocr/rectangle/op_inequality) | يفحص ما إذا كان هيكلا [`Rectangle`](../rectangle) يختلفان في الموقع أو الحجم. |

## الحقول

| Name | الوصف |
| --- | --- |
| [Height](../../aspose.ocr/rectangle/height) | عرض المستطيل. |
| [Width](../../aspose.ocr/rectangle/width) | ارتفاع المستطيل. |
| [X](../../aspose.ocr/rectangle/x) | موضع x للمستطيل. |
| [Y](../../aspose.ocr/rectangle/y) | موضع y للمستطيل. |

### انظر أيضًا

* namespace [Aspose.OCR](../../aspose.ocr)
* assembly [Aspose.OCR](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
