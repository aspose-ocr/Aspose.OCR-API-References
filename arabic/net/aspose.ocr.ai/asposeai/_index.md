---
title: "AsposeAI"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "واجهة برمجة التطبيقات الرئيسية للمكوّن الذكي في مكتبة Aspose OCR. توفر تكاملًا مع معالجات ما بعد الذكاء الاصطناعي مثل تصحيح الإملاء واستخراج الجداول وتصحيح التخطيط."
type: docs
weight: 630
url: /ar/net/aspose.ocr.ai/asposeai/
---
## AsposeAI class

واجهة برمجة التطبيقات الرئيسية للمكوّن الذكائي في مكتبة Aspose OCR. توفر التكامل مع المعالجات اللاحقة المدعومة بالذكاء الاصطناعي مثل تدقيق الإملاء، استخراج الجداول، وتصحيح التخطيط.

```csharp
public class AsposeAI : IDisposable
```

## Constructors

| Name | الوصف |
| --- | --- |
| [AsposeAI](asposeai#constructor)() | ينشئ مثيلًا جديدًا من الفئة AsposeAI بالإعدادات الافتراضية. تم تمكين تنزيل النماذج تلقائيًا. |
| [AsposeAI](asposeai#constructor_1)(ILogger) | ينشئ مثيلًا جديدًا من الفئة AsposeAI بمسجل مخصص. تم تمكين تنزيل النماذج تلقائيًا. |

## Methods

| Name | الوصف |
| --- | --- |
| [Dispose](../../aspose.ocr.ai/asposeai/dispose)() | يحرّر الموارد الداخلية المستخدمة بواسطة مثيل AsposeAI. |
| [FreeResources](../../aspose.ocr.ai/asposeai/freeresources)() | يطلق جميع الموارد المتعلقة بالذكاء الاصطناعي ويحرّر النماذج المحمَّلة. |
| [GetLocalPath](../../aspose.ocr.ai/asposeai/getlocalpath)() | يحصل على مسار دليل النماذج المحلي المُكوَّن حاليًا. |
| [IsInitialized](../../aspose.ocr.ai/asposeai/isinitialized)() | يتحقق مما إذا تم تهيئة محرك الذكاء الاصطناعي. |
| [ListLocal](../../aspose.ocr.ai/asposeai/listlocal)() | يسرد جميع النماذج المحلية المتاحة في الدليل المُكوَّن. |
| [RunPostprocessor](../../aspose.ocr.ai/asposeai/runpostprocessor#runpostprocessor_1)(List&lt;string&gt;) | يطبق معالج ما بعد الذكاء الاصطناعي المسجل على قائمة سلاسل النص المُعترف بها. |
| [RunPostprocessor](../../aspose.ocr.ai/asposeai/runpostprocessor#runpostprocessor)(OcrOutput) | يطبق معالج ما بعد الذكاء الاصطناعي المسجل على نتيجة OCR المهيكلة المعطاة. قد يشمل ذلك تصحيح الإملاء، اكتشاف الجداول، تنسيق الجداول، وتعزيزات أخرى مدعومة بالذكاء الاصطناعي حسب المعالجات المُكوَّنة. |
| [SetPostProcessor](../../aspose.ocr.ai/asposeai/setpostprocessor)(IOcrAIPostProcessor, AsposeAIModelConfig) | يضيف معالج ما بعد الذكاء الاصطناعي ليُطبق على نتائج OCR. إذا تم توفير *customSettings*، سيتم تحميل النموذج الذكي المحدد أو الافتراضي وتكوينه تلقائيًا قبل تطبيق معالج ما بعد المعالجة. |

### ملاحظات

⚠️ **Disclaimer:** باستخدام الميزات المدعومة بالذكاء الاصطناعي، أنت المسؤول الوحيد عن ضمان الامتثال لأي قوانين سارية، وشروط الترخيص، وسياسات استخدام نماذج الذكاء الاصطناعي من أطراف ثالثة، ولوائح خصوصية البيانات. لا تتحمل Aspose مسؤولية الدقة أو الترخيص أو موثوقية نماذج الذكاء الاصطناعي الخارجية.

### انظر أيضًا

* namespace [Aspose.OCR.AI](../../aspose.ocr.ai)
* assembly [Aspose.OCR](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
