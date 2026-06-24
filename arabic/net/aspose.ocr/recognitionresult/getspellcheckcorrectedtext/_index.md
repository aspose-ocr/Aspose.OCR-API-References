---
title: "GetSpellCheckCorrectedText"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "يصصح النص ويستبدل الكلمات المكتوبة بشكل خاطئ."
type: docs
weight: 120
url: /ar/net/aspose.ocr/recognitionresult/getspellcheckcorrectedtext/
---
## RecognitionResult.GetSpellCheckCorrectedText method

يصحح النص (يستبدل الكلمات المكتوبة خطأ).

```csharp
public string GetSpellCheckCorrectedText(SpellCheckLanguage language = SpellCheckLanguage.Eng, 
    string dictionaryPath = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| language | SpellCheckLanguage | القاموس المراد استخدامه. |
| dictionaryPath | String | اختياريًا. المسار الكامل لقاموس المستخدم (قاموس التردد). تنسيق ملف القاموس: ملف نص عادي بترميز UTF-8. يتم فصل الكلمة وتردد الكلمة بمسافة أو علامة تبويب. بشكل افتراضي، يُتوقع أن تكون الكلمة في العمود الأول والتردد في العمود الثاني. كل زوج كلمة-تردد في سطر منفصل. يُعرّف السطر على أنه تسلسل من الأحرف يتبعه تغذية سطر ("\n"), عودة سيارة ("\r"), أو عودة سيارة يتبعها مباشرة تغذية سطر ("\r\n"). يُتوقع أن تكون كل كلمة بأحرف صغيرة. |

### قيمة الإرجاع

نص مع كلمات مستبدلة.

### انظر أيضًا

* enum [SpellCheckLanguage](../../../aspose.ocr.spellchecker/spellchecklanguage)
* class [RecognitionResult](../../recognitionresult)
* namespace [Aspose.OCR](../../recognitionresult)
* assembly [Aspose.OCR](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
