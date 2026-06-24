---
title: "SetPostProcessor"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "يضيف معالجًا لاحقًا للذكاء الاصطناعي ليُطبق على نتائج OCR. إذا تم توفير customSettings، سيتم تحميل النموذج المحدد أو الافتراضي للذكاء الاصطناعي وتكوينه تلقائيًا قبل تطبيق المعالج اللاحق."
type: docs
weight: 80
url: /ar/net/aspose.ocr.ai/asposeai/setpostprocessor/
---
## AsposeAI.SetPostProcessor method

يضيف معالج ما بعد الذكاء الاصطناعي ليُطبق على نتائج OCR. إذا تم توفير *customSettings*، سيتم تحميل النموذج الذكي المحدد أو الافتراضي وتكوينه تلقائيًا قبل تطبيق معالج ما بعد المعالجة.

```csharp
public void SetPostProcessor(IOcrAIPostProcessor processor, 
    AsposeAIModelConfig customSettings = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| processor | IOcrAIPostProcessor | تنفيذ لـ [`IOcrAIPostProcessor`](../../iocraipostprocessor) يحدد المنطق للمعالجة اللاحقة القائمة على الذكاء الاصطناعي (مثل تدقيق الإملاء، استخراج الجداول، أو تصحيح التخطيط). |
| customSettings | AsposeAIModelConfig | إعداد نموذج الذكاء الاصطناعي المخصص للاستخدام. إذا تم توفيره، سيتم تحميل النموذج المحدد في [`AsposeAIModelConfig`](../../asposeaimodelconfig) وتطبيقه تلقائيًا. |

### انظر أيضًا

* interface [IOcrAIPostProcessor](../../iocraipostprocessor)
* class [AsposeAIModelConfig](../../asposeaimodelconfig)
* class [AsposeAI](../../asposeai)
* namespace [Aspose.OCR.AI](../../asposeai)
* assembly [Aspose.OCR](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
