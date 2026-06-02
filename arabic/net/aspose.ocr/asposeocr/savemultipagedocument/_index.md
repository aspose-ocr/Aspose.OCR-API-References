---
title: "SaveMultipageDocument"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult"
type: docs
weight: 290
url: /ar/net/aspose.ocr/asposeocr/savemultipagedocument/
---
## SaveMultipageDocument(string, SaveFormat, List&lt;RecognitionResult&gt;, string, PdfOptimizationMode) {#savemultipagedocument_3}

يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult

```csharp
public static void SaveMultipageDocument(string fullFileName, SaveFormat saveFormat, 
    List<RecognitionResult> results, string embeddedFontPath = null, 
    PdfOptimizationMode optimizePdf = PdfOptimizationMode.MAXIMUM_QUALITY)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fullFileName | String | اسم الملف مع مسار لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | SaveFormat | تنسيق المستند (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml). |
| results | List`1 | قائمة من كائنات [`RecognitionResult`](../../recognitionresult). |
| embeddedFontPath | String | اختياريًا. المسار الكامل إلى خط المستخدم. |
| optimizePdf | PdfOptimizationMode | تقليل حجم ملف PDF عن طريق خفض جودة الصور الخلفية. بشكل افتراضي، يتم الحفاظ على جودة الصورة الأصلية. |

### انظر أيضًا

* enum [SaveFormat](../../saveformat)
* class [RecognitionResult](../../recognitionresult)
* enum [PdfOptimizationMode](../../pdfoptimizationmode)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

---

## SaveMultipageDocument(string, SaveFormat, List&lt;RecognitionResult&gt;, bool, SpellCheckLanguage, string, string, PdfOptimizationMode) {#savemultipagedocument_2}

يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult

```csharp
public static void SaveMultipageDocument(string fullFileName, SaveFormat saveFormat, 
    List<RecognitionResult> results, bool applySpellingCorrection, 
    SpellCheckLanguage language = SpellCheckLanguage.Eng, string dictionaryPath = null, 
    string embeddedFontPath = null, 
    PdfOptimizationMode optimizePdf = PdfOptimizationMode.MAXIMUM_QUALITY)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fullFileName | String | اسم الملف مع مسار لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | SaveFormat | تنسيق المستند (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml). |
| results | List`1 | قائمة من كائنات [`RecognitionResult`](../../recognitionresult). |
| applySpellingCorrection | Boolean | عيّن true لتصحيح الكلمات المكتوبة بشكل خاطئ في حال وجودها في نتيجة التعرف. |
| language | SpellCheckLanguage | قاموس لتدقيق الإملاء (اختياري). |
| dictionaryPath | String | اختياريًا. المسار الكامل إلى القاموس الخاص بالمستخدم بصيغة .txt. الصيغة هي [كلمة - مسافة - تكرار(رقم)]. مثال: the 23135851162\nthat 3400031103\n |
| embeddedFontPath | String | اختياريًا. المسار الكامل إلى خط المستخدم. |
| optimizePdf | PdfOptimizationMode | تقليل حجم ملف PDF عن طريق خفض جودة الصور الخلفية. بشكل افتراضي، يتم الحفاظ على جودة الصورة الأصلية. |

### انظر أيضًا

* enum [SaveFormat](../../saveformat)
* class [RecognitionResult](../../recognitionresult)
* enum [SpellCheckLanguage](../../../aspose.ocr.spellchecker/spellchecklanguage)
* enum [PdfOptimizationMode](../../pdfoptimizationmode)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

---

## SaveMultipageDocument(MemoryStream, SaveFormat, List&lt;RecognitionResult&gt;, string, PdfOptimizationMode) {#savemultipagedocument_1}

يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult

```csharp
public static void SaveMultipageDocument(MemoryStream stream, SaveFormat saveFormat, 
    List<RecognitionResult> results, string embeddedFontPath = null, 
    PdfOptimizationMode optimizePdf = PdfOptimizationMode.MAXIMUM_QUALITY)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | MemoryStream | MemoryStream لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | SaveFormat | تنسيق المستند (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml). |
| results | List`1 | قائمة من كائنات [`RecognitionResult`](../../recognitionresult). |
| embeddedFontPath | String | اختياريًا. المسار الكامل إلى خط المستخدم. |
| optimizePdf | PdfOptimizationMode | تقليل حجم ملف PDF عن طريق خفض جودة الصور الخلفية. بشكل افتراضي، يتم الحفاظ على جودة الصورة الأصلية. |

### انظر أيضًا

* enum [SaveFormat](../../saveformat)
* class [RecognitionResult](../../recognitionresult)
* enum [PdfOptimizationMode](../../pdfoptimizationmode)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

---

## SaveMultipageDocument(MemoryStream, SaveFormat, List&lt;RecognitionResult&gt;, bool, SpellCheckLanguage, string, string, PdfOptimizationMode) {#savemultipagedocument}

يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult

```csharp
public static void SaveMultipageDocument(MemoryStream stream, SaveFormat saveFormat, 
    List<RecognitionResult> results, bool applySpellingCorrection, 
    SpellCheckLanguage language = SpellCheckLanguage.Eng, string dictionaryPath = null, 
    string embeddedFontPath = null, 
    PdfOptimizationMode optimizePdf = PdfOptimizationMode.MAXIMUM_QUALITY)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | MemoryStream | MemoryStream لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | SaveFormat | تنسيق المستند (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml). |
| results | List`1 | قائمة من كائنات [`RecognitionResult`](../../recognitionresult). |
| applySpellingCorrection | Boolean | عيّن true لتصحيح الكلمات المكتوبة بشكل خاطئ في حال وجودها في نتيجة التعرف. |
| language | SpellCheckLanguage | قاموس لتدقيق الإملاء (اختياري). |
| dictionaryPath | String | اختياريًا. المسار الكامل إلى القاموس الخاص بالمستخدم بصيغة .txt. الصيغة هي [كلمة - مسافة - تكرار(رقم)]. مثال: the 23135851162\nthat 3400031103\n |
| embeddedFontPath | String | اختياريًا. المسار الكامل إلى خط المستخدم. |
| optimizePdf | PdfOptimizationMode | تقليل حجم ملف PDF عن طريق خفض جودة الصور الخلفية. بشكل افتراضي، يتم الحفاظ على جودة الصورة الأصلية. |

### انظر أيضًا

* enum [SaveFormat](../../saveformat)
* class [RecognitionResult](../../recognitionresult)
* enum [SpellCheckLanguage](../../../aspose.ocr.spellchecker/spellchecklanguage)
* enum [PdfOptimizationMode](../../pdfoptimizationmode)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.OCR.dll -->
