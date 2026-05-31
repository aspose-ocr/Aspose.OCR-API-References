---
title: "RecognitionResult"
second_title: "مرجع Aspose.OCR لـ Java API"
description: "نتائج التعرف على الصورة"
type: docs
weight: 26
url: /ar/java/com.aspose.ocr/recognitionresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult
```

نتائج التعرف على الصورة. يحتوي على عناصر بمعلومات التعرف وطرق لتصدير النتيجة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [RecognitionResult()](#RecognitionResult) | يُنشئ مثيلًا جديدًا من |
## الحقول

| حقل | الوصف |
| --- | --- |
| [language](#language) | لغة النص المعترف به في الصورة. |
| [recognitionCharactersList](#recognitionCharactersList) | مجموعة من الأحرف التي وجدها خوارزمية التعرف مرتبة بترتيب تنازلي حسب الاحتمالية. |
| [recognitionLinesResult](#recognitionLinesResult) | يحصل على قائمة من نتائج التعرف مع قائمة من الصفوف (مستطيلات). |
| [recognitionRegionsResult](#recognitionRegionsResult) | يحصل على قائمة من نتائج التعرف مع قائمة من المناطق (مستطيلات). |
| [recognitionText](#recognitionText) | نتيجة التعرف لجميع الصفحات أو منطقة واحدة. |
| [warnings](#warnings) | يحصل أو يضبط قائمة رسائل التحذير التي تصف الأخطاء غير الحرجة التي ظهرت أثناء الإنشاء. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [GetJson()](#GetJson) | تكوين سلسلة JSON مع نتائج التعرف. |
| [GetKeywords()](#GetKeywords) | احصل على الكلمات المفتاحية من جواز السفر (وضع الاختبار. |
| [GetXml()](#GetXml) | تكوين سلسلة JSON مع نتائج التعرف. |
| [SetKeyword(String key, RecognitionResult.LinesResult result)](#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult) |  |
| [getSpellCheckCorrectedText()](#getSpellCheckCorrectedText) | يصحح النص (يستبدل الكلمات المكتوبة خطأً). |
| [getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)](#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | يصحح النص (يستبدل الكلمات المكتوبة خطأً). |
| [getSpellCheckErrorList()](#getSpellCheckErrorList) | ابحث عن الكلمات المكتوبة بشكل خاطئ مع الاقتراحات الإملائية لنص الإدخال المعطى. |
| [getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)](#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | ابحث عن الكلمات المكتوبة بشكل خاطئ مع الاقتراحات الإملائية لنص الإدخال المعطى. |
| [save(String fullFileName)](#save-java.lang.String) | يحفظ المستند كنص عادي |
| [save(String fullFileName, Format format)](#save-java.lang.String-com.aspose.ocr.models.Format) | يحفظ المستند كنص عادي أو بتنسيق مستند آخر. |
| [save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode) | يحفظ المستند كنص عادي أو بتنسيق مستند آخر. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format) | يحفظ النص المصحح باستخدام القاموس الإنجليزي في المستند كنص عادي أو بتنسيق مستند نصي مايكروسوفت وورد. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | يحفظ النص المصحح في المستند كنص عادي أو بتنسيق آخر. |
| [toString()](#toString) |  |
| [useUserDictionary(String dictionaryPath)](#useUserDictionary-java.lang.String) | يسمح باستخدام القاموس الخاص لتصحيح التدقيق الإملائي. |
### RecognitionResult() {#RecognitionResult}
```
public RecognitionResult()
```


يُنشئ مثيلًا جديدًا من

### language {#language}
```
public Language language
```


لغة النص المعترف به في الصورة. يتم تحديد هذه القيمة تلقائيًا إذا تم اختيار Language.AUTO أو Language.MULTILANGUAGE أو Language.UNIVERSAL.

### recognitionCharactersList {#recognitionCharactersList}
```
public ArrayList<char[]> recognitionCharactersList
```


مجموعة من الأحرف التي وجدها خوارزمية التعرف مرتبة بترتيب تنازلي حسب الاحتمالية.

### recognitionLinesResult {#recognitionLinesResult}
```
public ArrayList<RecognitionResult.LinesResult> recognitionLinesResult
```


يحصل على قائمة من نتائج التعرف مع قائمة من الصفوف (مستطيلات).

### recognitionRegionsResult {#recognitionRegionsResult}
```
public ArrayList<RecognitionResult.RegionResult> recognitionRegionsResult
```


يحصل على قائمة من نتائج التعرف مع قائمة من المناطق (مستطيلات).

### recognitionText {#recognitionText}
```
public String recognitionText
```


نتيجة التعرف لجميع الصفحات أو منطقة واحدة.

### warnings {#warnings}
```
public ArrayList<String> warnings
```


يحصل أو يضبط قائمة رسائل التحذير التي تصف الأخطاء غير الحرجة التي ظهرت أثناء الإنشاء.

### GetJson() {#GetJson}
```
public String GetJson()
```


تكوين سلسلة JSON مع نتائج التعرف.

**Returns:**
java.lang.String - نتائج التعرف كسلسلة JSON.
### GetKeywords() {#GetKeywords}
```
public HashMap<String,RecognitionResult.LinesResult> GetKeywords()
```


احصل على الكلمات المفتاحية من جواز السفر (وضع الاختبار. يعمل فقط لجوازات السفر الأمريكية وماداغاسكار).

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.ocr.RecognitionResult.LinesResult> - قاموس حيث الكلمة المفتاحية هي المفتاح وLinesResult هي القيمة.
### GetXml() {#GetXml}
```
public String GetXml()
```


تكوين سلسلة JSON مع نتائج التعرف.

**Returns:**
java.lang.String - نتائج التعرف كسلسلة XML.
### SetKeyword(String key, RecognitionResult.LinesResult result) {#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult}
```
public void SetKeyword(String key, RecognitionResult.LinesResult result)
```



### getSpellCheckCorrectedText() {#getSpellCheckCorrectedText}
```
public String getSpellCheckCorrectedText()
```


يصحح النص (يستبدل الكلمات المكتوبة خطأً).

**Returns:**
java.lang.String - سلسلة نتائج التعرف المصححة. القاموس الإنجليزي الافتراضي.
### getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language) {#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)
```


يصحح النص (يستبدل الكلمات المكتوبة خطأً).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | القاموس المراد استخدامه. |

**Returns:**
java.lang.String - سلسلة نتائج التعرف المصححة.
### getSpellCheckErrorList() {#getSpellCheckErrorList}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList()
```


ابحث عن الكلمات المكتوبة بشكل خاطئ مع الاقتراحات الإملائية لنص الإدخال المعطى. القاموس الإنجليزي الافتراضي.

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - ArrayList من كائن SpellCheckError يمثل الكلمات المكتوبة بشكل خاطئ مع قوائم الاقتراحات الصحيحة لكل كلمة مكتوبة بشكل خاطئ، ومع مسافة التحرير.
### getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language) {#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)
```


ابحث عن الكلمات المكتوبة بشكل خاطئ مع الاقتراحات الإملائية لنص الإدخال المعطى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | القاموس المراد استخدامه. |

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - ArrayList من كائن SpellCheckError يمثل الكلمات المكتوبة بشكل خاطئ مع قوائم الاقتراحات الصحيحة لكل كلمة مكتوبة بشكل خاطئ، ومع مسافة التحرير.




### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


يحفظ المستند كنص عادي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullFileName | java.lang.String | اسم الملف مع المسار لحفظ نتيجة التعرف |

### save(String fullFileName, Format format) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format format)
```


يحفظ المستند كنص عادي أو بتنسيق مستند آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullFileName | java.lang.String | اسم الملف مع المسار لحفظ نتيجة التعرف. |
| format | [Format](../../com.aspose.ocr.models/format/) | نوع تعداد تنسيق المستند Format. |

### save(String fullFileName, Format format, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)
```


يحفظ المستند كنص عادي أو بتنسيق مستند آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullFileName | java.lang.String | اسم الملف مع المسار لحفظ نتيجة التعرف. |
| format | [Format](../../com.aspose.ocr.models/format/) | نوع تعداد تنسيق المستند Format. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | قلل حجم ملف PDF عن طريق خفض جودة الصور الخلفية. بشكل افتراضي، يتم الحفاظ على جودة الصورة الأصلية. |

### saveSpellCheckCorrectedText(String fullFileName, Format format) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format)
```


يحفظ النص المصحح باستخدام القاموس الإنجليزي في المستند كنص عادي أو بتنسيق مستند نصي مايكروسوفت وورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullFileName | java.lang.String | اسم الملف مع المسار لحفظ نتيجة التعرف. |
| format | [Format](../../com.aspose.ocr.models/format/) | نوع تعداد تنسيق المستند Format. |

### saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)
```


يحفظ النص المصحح في المستند كنص عادي أو بتنسيق آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullFileName | java.lang.String | اسم الملف مع المسار لحفظ نتيجة التعرف. |
| format | [Format](../../com.aspose.ocr.models/format/) | نوع تعداد تنسيق المستند Format. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | قاموس للتدقيق الإملائي. |
### useUserDictionary(String dictionaryPath) {#useUserDictionary-java.lang.String}
```
public void useUserDictionary(String dictionaryPath)
```


يسمح باستخدام القاموس الخاص لتصحيح التدقيق الإملائي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dictionaryPath | java.lang.String | المسار الكامل إلى قاموس المستخدم (قاموس التردد). تنسيق ملف القاموس: ملف نص عادي بترميز UTF-8. يتم فصل الكلمة وتردد الكلمة بفاصلة، تُتوقع الكلمة في العمود الأول والتردد في العمود الثاني. كل زوج كلمة-تردد في سطر منفصل. يُعرّف السطر على أنه تسلسل من الأحرف يتبعه تغذية سطر (\"\\n\"), عودة سيارة (\"\\r\"), أو عودة سيارة يتبعها مباشرة تغذية سطر (\"\\r\\n\"). يُتوقع أن تكون كل كلمة بأحرف صغيرة. |
