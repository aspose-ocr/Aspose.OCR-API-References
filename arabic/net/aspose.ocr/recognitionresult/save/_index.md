---
title: "Save"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "يحفظ المستند كملف PDF نصي عادي أو مستند Microsoft Word."
type: docs
weight: 150
url: /ar/net/aspose.ocr/recognitionresult/save/
---
## Save(string, SaveFormat, bool, SpellCheckLanguage, string, string, PdfOptimizationMode) {#save_2}

يحفظ المستند كنص عادي أو PDF أو مستند Microsoft Word.

```csharp
public void Save(string fullFileName, SaveFormat saveFormat, bool applySpellingCorrection, 
    SpellCheckLanguage language = SpellCheckLanguage.Eng, string dictionaryPath = null, 
    string embeddedFontPath = null, 
    PdfOptimizationMode optimizePdf = PdfOptimizationMode.MAXIMUM_QUALITY)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fullFileName | String | اسم الملف مع مسار لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | SaveFormat | تنسيق المستند (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml). |
| applySpellingCorrection | Boolean | عيّن القيمة true لتصحيح الكلمات المكتوبة بشكل خاطئ إذا وجدت ذلك في نتيجة التعرف. |
| language | SpellCheckLanguage | قاموس لتدقيق الإملاء (اختياري). |
| dictionaryPath | String | اختياريًا. المسار الكامل إلى القاموس الخاص بالمستخدم بصيغة .txt. الصيغة هي [كلمة - مسافة - تكرار(عدد)]. مثال: the 23135851162\nthat 3400031103\n |
| embeddedFontPath | String | اختياريًا. المسار الكامل إلى خط المستخدم. |
| optimizePdf | PdfOptimizationMode | تقليل حجم ملف PDF عن طريق خفض جودة الصور الخلفية. بشكل افتراضي، يتم الحفاظ على جودة الصورة الأصلية. |

### انظر أيضًا

* enum [SaveFormat](../../saveformat)
* enum [SpellCheckLanguage](../../../aspose.ocr.spellchecker/spellchecklanguage)
* enum [PdfOptimizationMode](../../pdfoptimizationmode)
* class [RecognitionResult](../../recognitionresult)
* namespace [Aspose.OCR](../../recognitionresult)
* assembly [Aspose.OCR](../../../)

---

## Save(string, SaveFormat, string, PdfOptimizationMode) {#save_3}

يحفظ المستند كنص عادي أو PDF أو مستند Microsoft Word.

```csharp
public void Save(string fullFileName, SaveFormat saveFormat, string embeddedFontPath = null, 
    PdfOptimizationMode optimizePdf = PdfOptimizationMode.MAXIMUM_QUALITY)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fullFileName | String | اسم الملف مع مسار لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | SaveFormat | تنسيق المستند (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml). |
| embeddedFontPath | String | اختياريًا. المسار الكامل إلى خط المستخدم. |
| optimizePdf | PdfOptimizationMode | تقليل حجم ملف PDF عن طريق خفض جودة الصور الخلفية. بشكل افتراضي، يتم الحفاظ على جودة الصورة الأصلية. |

### انظر أيضًا

* enum [SaveFormat](../../saveformat)
* enum [PdfOptimizationMode](../../pdfoptimizationmode)
* class [RecognitionResult](../../recognitionresult)
* namespace [Aspose.OCR](../../recognitionresult)
* assembly [Aspose.OCR](../../../)

---

## Save(MemoryStream, SaveFormat, bool, SpellCheckLanguage, string, string, PdfOptimizationMode) {#save}

يحفظ المستند كنص عادي أو PDF أو مستند Microsoft Word.

```csharp
public void Save(MemoryStream stream, SaveFormat saveFormat, bool applySpellingCorrection, 
    SpellCheckLanguage language = SpellCheckLanguage.Eng, string dictionaryPath = null, 
    string embeddedFontPath = null, 
    PdfOptimizationMode optimizePdf = PdfOptimizationMode.MAXIMUM_QUALITY)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | MemoryStream | MemoryStream لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | SaveFormat | تنسيق المستند (Docx, Txt, Pdf). |
| applySpellingCorrection | Boolean | عيّن القيمة true لتصحيح الكلمات المكتوبة بشكل خاطئ إذا وجدت ذلك في نتيجة التعرف. |
| language | SpellCheckLanguage | قاموس لتدقيق الإملاء (اختياري). |
| dictionaryPath | String | اختياريًا. المسار الكامل إلى القاموس الخاص بالمستخدم بصيغة .txt. الصيغة هي [كلمة - مسافة - تكرار(عدد)]. مثال: the 23135851162\nthat 3400031103\n |
| embeddedFontPath | String | اختياريًا. المسار الكامل إلى خط المستخدم. |
| optimizePdf | PdfOptimizationMode | تقليل حجم ملف PDF عن طريق خفض جودة الصور الخلفية. بشكل افتراضي، يتم الحفاظ على جودة الصورة الأصلية. |

### انظر أيضًا

* enum [SaveFormat](../../saveformat)
* enum [SpellCheckLanguage](../../../aspose.ocr.spellchecker/spellchecklanguage)
* enum [PdfOptimizationMode](../../pdfoptimizationmode)
* class [RecognitionResult](../../recognitionresult)
* namespace [Aspose.OCR](../../recognitionresult)
* assembly [Aspose.OCR](../../../)

---

## Save(MemoryStream, SaveFormat, string, PdfOptimizationMode) {#save_1}

يحفظ المستند كنص عادي أو PDF أو مستند Microsoft Word.

```csharp
public void Save(MemoryStream stream, SaveFormat saveFormat, string embeddedFontPath = null, 
    PdfOptimizationMode optimizePdf = PdfOptimizationMode.MAXIMUM_QUALITY)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | MemoryStream | MemoryStream لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | SaveFormat | تنسيق المستند (Docx, Txt, Pdf). |
| embeddedFontPath | String | اختياريًا. المسار الكامل إلى خط المستخدم. |
| optimizePdf | PdfOptimizationMode | تقليل حجم ملف PDF عن طريق خفض جودة الصور الخلفية. بشكل افتراضي، يتم الحفاظ على جودة الصورة الأصلية. |

### انظر أيضًا

* enum [SaveFormat](../../saveformat)
* enum [PdfOptimizationMode](../../pdfoptimizationmode)
* class [RecognitionResult](../../recognitionresult)
* namespace [Aspose.OCR](../../recognitionresult)
* assembly [Aspose.OCR](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
