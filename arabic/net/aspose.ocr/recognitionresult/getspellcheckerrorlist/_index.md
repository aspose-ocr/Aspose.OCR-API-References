---
title: "GetSpellCheckErrorList"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "ابحث عن الكلمات المكتوبة بشكل خاطئ مع اقتراحات التصحيح للنص المدخل."
type: docs
weight: 130
url: /ar/net/aspose.ocr/recognitionresult/getspellcheckerrorlist/
---
## RecognitionResult.GetSpellCheckErrorList method

ابحث عن الكلمات المكتوبة بشكل خاطئ مع اقتراحات التصحيح للنص المدخل.

```csharp
public List<SpellCheckError> GetSpellCheckErrorList(
    SpellCheckLanguage language = SpellCheckLanguage.Eng, string dictionaryPath = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| language | SpellCheckLanguage | القاموس المراد استخدامه. |
| dictionaryPath | String | اختياريًا. المسار الكامل لقاموس المستخدم (قاموس التردد). تنسيق ملف القاموس: ملف نص عادي بترميز UTF-8. يتم فصل الكلمة وتردد الكلمة بمسافة أو علامة تبويب. بشكل افتراضي، يُتوقع أن تكون الكلمة في العمود الأول والتردد في العمود الثاني. كل زوج كلمة-تردد في سطر منفصل. يُعرّف السطر على أنه تسلسل من الأحرف يتبعه تغذية سطر ("\n"), عودة سيارة ("\r"), أو عودة سيارة يتبعها مباشرة تغذية سطر ("\r\n"). يُتوقع أن تكون كل كلمة بأحرف صغيرة. |

### قيمة الإرجاع

قائمة من كائنات SpellCheckError تمثل الكلمات المكتوبة بشكل خاطئ مع قوائم الاقتراحات للتصحيحات الصحيحة لكل كلمة مكتوبة بشكل خاطئ، ومع مسافة التحرير.

### انظر أيضًا

* struct [SpellCheckError](../../../aspose.ocr.spellchecker/spellcheckerror)
* enum [SpellCheckLanguage](../../../aspose.ocr.spellchecker/spellchecklanguage)
* class [RecognitionResult](../../recognitionresult)
* namespace [Aspose.OCR](../../recognitionresult)
* assembly [Aspose.OCR](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
