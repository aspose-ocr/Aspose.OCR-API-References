---
title: "Metered"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "يوفر طرقًا لتعيين المفتاح المقنن."
type: docs
weight: 30
url: /ar/net/aspose.ocr/metered/
---
## Metered class

يوفر طرقًا لتعيين المفتاح المقنن.

```csharp
public class Metered
```

## Constructors

| Name | الوصف |
| --- | --- |
| [Metered](metered)() | ينشئ مثيلًا جديدًا لهذه الفئة. |

## Methods

| Name | الوصف |
| --- | --- |
| [SetMeteredKey](../../aspose.ocr/metered/setmeteredkey)(string, string) | يضبط المفتاح العام والخاص المتعقب. إذا قمت بشراء ترخيص متعقب، عند بدء التطبيق، يجب استدعاء هذه الواجهة البرمجية، عادةً هذا يكفي. ومع ذلك، إذا فشل دائمًا تحميل بيانات الاستهلاك وتجاوز 24 ساعة، سيتم ضبط الترخيص إلى حالة التقييم، لتجنب هذه الحالة، يجب عليك فحص حالة الترخيص بانتظام، إذا كانت حالة التقييم، استدعِ هذه الواجهة البرمجية مرة أخرى. |
| static [GetConsumptionCredit](../../aspose.ocr/metered/getconsumptioncredit)() | يحصل على رصيد الاستهلاك. |
| static [GetConsumptionQuantity](../../aspose.ocr/metered/getconsumptionquantity)() | يحصل على حجم ملف الاستهلاك. |

### أمثلة

في هذا المثال، سيتم محاولة ضبط المفتاح العام والخاص المتعقب

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

ملف jar الخاص بالمكوّن:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### انظر أيضًا

* namespace [Aspose.OCR](../../aspose.ocr)
* assembly [Aspose.OCR](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
