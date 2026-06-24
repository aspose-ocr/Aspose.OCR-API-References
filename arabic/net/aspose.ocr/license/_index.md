---
title: "رخصة"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "يوفر طرقًا لترخيص المكوّن."
type: docs
weight: 40
url: /ar/net/aspose.ocr/license/
---
## License class

يوفر طرقًا لترخيص المكوّن.

```csharp
public class License
```

## Constructors

| Name | الوصف |
| --- | --- |
| [License](license)() | ينشئ مثيلًا جديدًا لهذه الفئة. |

## Properties

| Name | الوصف |
| --- | --- |
| [IsLicensed](../../aspose.ocr/license/islicensed) { get; } | يحصل على قيمة تشير إلى ما إذا كان المنتج مرخصًا. |

## Methods

| Name | الوصف |
| --- | --- |
| [SetLicense](../../aspose.ocr/license/setlicense#setlicense)(Stream) | يرخص المكوّن. |
| [SetLicense](../../aspose.ocr/license/setlicense#setlicense_1)(string) | يرخص المكوّن. |

### أمثلة

في هذا المثال، سيُجرى محاولة للعثور على ملف الترخيص المسمى MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، وفي مجلد التجميع الرئيسي، ثم في الموارد المدمجة للتجميع المستدعي.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

ملف jar الخاص بالمكوّن:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### انظر أيضًا

* namespace [Aspose.OCR](../../aspose.ocr)
* assembly [Aspose.OCR](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
