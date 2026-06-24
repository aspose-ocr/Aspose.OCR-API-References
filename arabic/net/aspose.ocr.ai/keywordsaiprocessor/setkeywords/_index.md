---
title: "SetKeywords"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "يضبط الكلمات المفتاحية المستخدمة للبحث في النص المُعترف به عبر OCR."
type: docs
weight: 60
url: /ar/net/aspose.ocr.ai/keywordsaiprocessor/setkeywords/
---
## KeywordsAIProcessor.SetKeywords method

يضبط الكلمات المفتاحية المستخدمة للبحث في النص المُعترف به عبر OCR.

```csharp
public void SetKeywords(string[] keywords)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| keywords | String[] | الكلمات المفتاحية للبحث عنها. المطابقة غير حساسة لحالة الأحرف ولا تعتمد على الترتيب. |

### أمثلة

```csharp
var processor = new KeywordsAIProcessor();
processor.SetKeywords(new[] { "Total", "Subtotal", "Discount", "Quantity" });
```

### انظر أيضًا

* class [KeywordsAIProcessor](../../keywordsaiprocessor)
* namespace [Aspose.OCR.AI](../../keywordsaiprocessor)
* assembly [Aspose.OCR](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
