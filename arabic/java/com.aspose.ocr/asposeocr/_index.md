---
title: "AsposeOCR"
second_title: "مرجع Aspose.OCR لـ Java API"
description: "الفئة الرئيسية للتعرف على النص من الصور"
type: docs
weight: 10
url: /ar/java/com.aspose.ocr/asposeocr/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public class AsposeOCR implements AutoCloseable
```

الفئة الرئيسية للتعرف على النص من الصور.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [AsposeOCR()](#AsposeOCR) | منشئ عام. |
## الحقول

| الحقل | الوصف |
| --- | --- |
| [DebugMode](#DebugMode) | يفعل وضع التصحيح. |
| [DebugModeSaveDirectory](#DebugModeSaveDirectory) | الدليل الذي سيتم حفظ نتائج التصحيح فيه. |
## الدوال

| الدالة | الوصف |
| --- | --- |
| [CalculateSkew(OcrInput input)](#CalculateSkew-com.aspose.ocr.OcrInput) | يحسب زوايا الانحراف للصور. |
| [CompareImageTexts(String fullPath1, String fullPath2)](#CompareImageTexts-java.lang.String-java.lang.String) | تحقق مما إذا كانت صورتان تحتويان على نفس النص. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | تحقق مما إذا كانت صورتان تحتويان على نفس النص. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | تحقق مما إذا كانت صورتان تحتويان على نفس النص. |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | يصحح النص (يستبدل الكلمات المكتوبة خطأً). |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String) | يصحح النص (يستبدل الكلمات المكتوبة خطأً). |
| [DetectDefects(OcrInput input, DefectType defectType)](#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType) | يحدد تلقائيًا المناطق المشكلة في الصورة والتي يمكن أن تؤثر بشكل كبير على دقة التعرف الضوئي على الأحرف. |
| [DetectDocumentLayout(OcrInput input)](#DetectDocumentLayout-com.aspose.ocr.OcrInput) | يحلل الصورة ويحدد الأنواع المختلفة لمناطق المحتوى داخلها. |
| [DetectLanguages(OcrInput input)](#DetectLanguages-com.aspose.ocr.OcrInput) | يحلل النص الموجود على الصورة لتحديد اللغات التي كُتب بها. |
| [DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)](#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean) | يكتشف مناطق النص على الصور. |
| [DetectTables(OcrInput images)](#DetectTables-com.aspose.ocr.OcrInput) | يكتشف مناطق الجداول على الصور. |
| [ImageHasText(String fullPath, String text)](#ImageHasText-java.lang.String-java.lang.String) | تحقق مما إذا كانت الصورة تحتوي على الجزء النصي المقدم مع بحث غير حساس لحالة الأحرف. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | تحقق مما إذا كانت الصورة تحتوي على الجزء النصي المقدم مع بحث غير حساس لحالة الأحرف. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | تحقق مما إذا كانت الصورة تحتوي على الجزء النصي المقدم. |
| [ImageHasText(String fullPath, Pattern regex)](#ImageHasText-java.lang.String-java.util.regex.Pattern) | تحقق مما إذا كان نص الصورة يطابق التعبير النمطي المقدم. |
| [ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings) | تحقق مما إذا كان نص الصورة يطابق التعبير النمطي المقدم. |
| [ImageTextDiff(String fullPath1, String fullPath2)](#ImageTextDiff-java.lang.String-java.lang.String) | قارن النصوص على الصورتين وأرجع رقمًا يمثل مدى تشابههما (من 0 إلى 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | قارن النصوص على الصورتين وأرجع رقمًا يمثل مدى تشابههما (من 0 إلى 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | قارن النصوص على الصورتين وأرجع رقمًا يمثل مدى تشابههما (من 0 إلى 1). |
| [Recognize(OcrInput input)](#Recognize-com.aspose.ocr.OcrInput) | يتعرف على الصورة مع القدرة على تحديد الدعم للأنواع GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, المجلد, المصفوفة, أرشيف zip, URL, base64. |
| [Recognize(OcrInput input, RecognitionSettings settings)](#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings) | يتعرف على الصورة مع القدرة على تحديد الدعم للأنواع GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, المجلد, المصفوفة, أرشيف zip, URL, base64. |
| [RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)](#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings) | يتعرف على لوحة السيارة مع القدرة على تحديد الدعم للأنواع GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, المجلد, المصفوفة, أرشيف zip, URL, base64. |
| [RecognizeCharacters(OcrInput input)](#RecognizeCharacters-com.aspose.ocr.OcrInput) | يكتشف الرموز على الصور. |
| [RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)](#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language) | يكتشف الرموز على الصور. |
| [RecognizeFast(OcrInput input)](#RecognizeFast-com.aspose.ocr.OcrInput) | يتعرف على النص في صورة ذات جودة جيدة. |
| [RecognizeFormula(OcrInput input, boolean detectAreas)](#RecognizeFormula-com.aspose.ocr.OcrInput-boolean) | يتعرف على الصيغ الرياضية من الصور المدخلة المقدمة. |
| [RecognizeHandwrittenText(OcrInput input)](#RecognizeHandwrittenText-com.aspose.ocr.OcrInput) | يتعرف على النص المكتوب يدويًا على الصور. |
| [RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)](#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings) | يتعرف على بطاقة الهوية مع القدرة على تحديد الدعم للأنواع GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, المجلد, المصفوفة, أرشيف zip, URL, base64. |
| [RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)](#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings) | يتعرف على الفاتورة مع القدرة على تحديد الدعم للأنواع GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, المجلد, المصفوفة, أرشيف zip, URL, base64. |
| [RecognizePassport(OcrInput input, PassportRecognitionSettings settings)](#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings) | يتعرف على جواز السفر مع إمكانية التحديد. |
| [RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)](#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings) | يتعرف على الإيصالات مع إمكانية التحديد يدعم GIF و PNG و JPEG و WBMP و TIFF و JFIF و TIFF و PDF و InputStream و BufferedImage و المجلد و المصفوفة و أرشيف zip و URL و base64. |
| [RecognizeTables(OcrInput input, Language language)](#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language) | اكتشاف الجداول والبنية، يتعرف على خلايا النص. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage) | يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult مع تصحيح التدقيق الإملائي. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult. |
| [close()](#close) |  |

### AsposeOCR() {#AsposeOCR}
```
public AsposeOCR()
```


منشئ عام.

### DebugMode {#DebugMode}
```
public static boolean DebugMode
```


يفعل وضع التصحيح. عند التفعيل، يقوم النظام بحفظ نتائج معالجة الصور الوسيطة مثل الصور المسبقة المعالجة والصور التي تحتوي على مستطيلات خطوط النص المرسومة.

### DebugModeSaveDirectory {#DebugModeSaveDirectory}
```
public static String DebugModeSaveDirectory
```


الدليل الذي سيتم حفظ نتائج التصحيح فيه. إذا لم يتم تحديده، سيُستخدم الدليل الحالي للعمل كإعداد افتراضي.

### CalculateSkew(OcrInput input) {#CalculateSkew-com.aspose.ocr.OcrInput}
```
public ArrayList<SkewOutput> CalculateSkew(OcrInput input)
```


يحسب زوايا الانحراف للصور. يدعم GIF و PNG و JPEG و WBMP و TIFF و JFIF و TIFF و PDF و InputStream و BufferedImage و المجلد و المصفوفة و أرشيف zip و URL و base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | الحاوية التي تحتوي على المصادر.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.SkewOutput> - قائمة ArrayList لزوايا الانحراف بالدرجات [SkewOutput](../../com.aspose.ocr.models/skewoutput/)
### CompareImageTexts(String fullPath1, String fullPath2) {#CompareImageTexts-java.lang.String-java.lang.String}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2)
```


تحقق مما إذا كانت صورتان تحتويان على نفس النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath1 | java.lang.String | المسار إلى الصورة الأولى. |
| fullPath2 | java.lang.String | المسار إلى الصورة الثانية. |

**Returns:**
boolean - صحيح إذا كانت الصور تحتوي على نفس النص (تشابه 90%).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)
```


تحقق مما إذا كانت صورتان تحتويان على نفس النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath1 | java.lang.String | المسار إلى الصورة الأولى. |
| fullPath2 | java.lang.String | المسار إلى الصورة الثانية. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | إعدادات التعرف. |

**Returns:**
boolean - صحيح إذا كانت الصور تحتوي على نفس النص (تشابه 90%).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


تحقق مما إذا كانت صورتان تحتويان على نفس النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath1 | java.lang.String | المسار إلى الصورة الأولى. |
| fullPath2 | java.lang.String | المسار إلى الصورة الثانية. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | إعدادات التعرف. |
| ignoreCase | boolean | True - يعني بحث غير حساس لحالة الأحرف. |

**Returns:**
boolean - صحيح إذا كانت الصور تحتوي على نفس النص (تشابه 90%).
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)
```


يصحح النص (يستبدل الكلمات المكتوبة خطأً).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص للتصحيح. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | القاموس للاستخدام [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |

**Returns:**
java.lang.String - نص مع الكلمات المستبدلة.
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)
```


يصحح النص (يستبدل الكلمات المكتوبة خطأً).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص للتصحيح. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | القاموس للاستخدام [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |
| dictionaryPath | java.lang.String | المسار الكامل إلى قاموس المستخدم (قاموس التردد). تنسيق ملف القاموس: ملف نص عادي بترميز UTF-8. يتم فصل الكلمة وتردد الكلمة بفاصلة، تُتوقع الكلمة في العمود الأول والتردد في العمود الثاني. كل زوج كلمة-تردد في سطر منفصل. يُعرّف السطر على أنه تسلسل من الأحرف يتبعه تغذية سطر ("\\n"), أو عودة سيارة ("\\r"), أو عودة سيارة يتبعها مباشرة تغذية سطر ("\\r\\n"). يُتوقع أن تكون كل كلمة بحروف صغيرة. |

**Returns:**
java.lang.String - نص مع الكلمات المستبدلة.
### DetectDefects(OcrInput input, DefectType defectType) {#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType}
```
public ArrayList<DefectOutput> DetectDefects(OcrInput input, DefectType defectType)
```


اكتشاف تلقائي للمناطق المشكلة في الصورة التي يمكن أن تؤثر بشكل كبير على دقة OCR. يدعم GIF و PNG و JPEG و WBMP و TIFF و JFIF و TIFF و PDF و InputStream و BufferedImage و المجلد و المصفوفة و أرشيف zip و URL و base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | الحاوية التي تحتوي على المصادر.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| defectType | [DefectType](../../com.aspose.ocr.models/defecttype/) | أنواع العيوب التي سيتم التعرف عليها [DefectType](../../com.aspose.ocr.models/defecttype/). |

**Returns:**
java.util.ArrayList<com.aspose.ocr.DefectOutput> - قائمة ArrayList من [DefectOutput](../../com.aspose.ocr/defectoutput/) مع مناطق النص المكتشفة أو السطور.
### DetectDocumentLayout(OcrInput input) {#DetectDocumentLayout-com.aspose.ocr.OcrInput}
```
public ArrayList<LayoutOutput> DetectDocumentLayout(OcrInput input)
```


يقوم بتحليل الصورة وتحديد الأنواع المختلفة لمناطق المحتوى داخلها. يدعم GIF و PNG و JPEG و WBMP و TIFF و JFIF و TIFF و PDF و InputStream و BufferedImage و المجلد و المصفوفة و أرشيف zip و URL و base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | الحاوية التي تحتوي على المصادر.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LayoutOutput> - مناطق المحتوى المكتشفة. ArrayList من [LayoutOutput](../../com.aspose.ocr.models/layoutoutput/)
### DetectLanguages(OcrInput input) {#DetectLanguages-com.aspose.ocr.OcrInput}
```
public ArrayList<LanguageDetectionOutput> DetectLanguages(OcrInput input)
```


يقوم بتحليل النص الموجود على الصورة لتحديد اللغات التي كُتب بها. يتيح ذلك اختيار لغة التعرف الأنسب ويساعد في مهام معالجة النصوص اللاحقة مثل التدقيق الإملائي أو الترجمة. يدعم GIF و PNG و JPEG و WBMP و TIFF و JFIF و TIFF و PDF و InputStream و BufferedImage و المجلد و المصفوفة و أرشيف zip و URL و base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | الحاوية التي تحتوي على المصادر.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LanguageDetectionOutput> - يُرجع قائمة بأكثر اللغات احتمالاً، مرتبة حسب الاحتمالية. ArrayList من [LanguageDetectionOutput](../../com.aspose.ocr.models/languagedetectionoutput/)
### DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas) {#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean}
```
public ArrayList<RectangleOutput> DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)
```


يكتشف مناطق النص على الصور. يدعم GIF و PNG و JPEG و WBMP و TIFF و JFIF و TIFF و PDF و InputStream و BufferedImage و المجلد و المصفوفة و أرشيف zip و URL و base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | الحاوية التي تحتوي على المصادر.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| areasType | [AreasType](../../com.aspose.ocr.models/areastype/) | يحدد أي المستطيلات تُرجع - سطر أم فقرات. |
| isDetectAreas | boolean | تمكين الكشف التلقائي عن مناطق النص. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - قائمة ArrayList من [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) مع مناطق النص المكتشفة أو السطور.
### DetectTables(OcrInput images) {#DetectTables-com.aspose.ocr.OcrInput}
```
public ArrayList<RectangleOutput> DetectTables(OcrInput images)
```


يكتشف مناطق الجداول على الصور. يدعم GIF و PNG و JPEG و WBMP و TIFF و JFIF و TIFF و PDF و InputStream و BufferedImage و المجلد و المصفوفة و أرشيف zip و URL و base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | الحاوية التي تحتوي على المصادر.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - قائمة ArrayList من [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) مع مناطق الجداول المكتشفة.
### ImageHasText(String fullPath, String text) {#ImageHasText-java.lang.String-java.lang.String}
```
public boolean ImageHasText(String fullPath, String text)
```


تحقق مما إذا كانت الصورة تحتوي على الجزء النصي المقدم مع بحث غير حساس لحالة الأحرف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath | java.lang.String | مسار الصورة. |
| text | java.lang.String | مجزء نص للبحث في الصورة. |

**Returns:**
boolean - صحيح إذا كانت الصورة تحتوي على مجزء نص. خطأ - الصورة لا تحتوي على مجزء نص.
### ImageHasText(String fullPath, String text, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings)
```


تحقق مما إذا كانت الصورة تحتوي على الجزء النصي المقدم مع بحث غير حساس لحالة الأحرف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath | java.lang.String | مسار الصورة. |
| text | java.lang.String | مجزء نص للبحث في الصورة. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | إعدادات التعرف. |

**Returns:**
boolean - صحيح إذا كانت الصورة تحتوي على مجزء نص. خطأ - الصورة لا تحتوي على مجزء نص.
### ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)
```


تحقق مما إذا كانت الصورة تحتوي على الجزء النصي المقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath | java.lang.String | مسار الصورة. |
| text | java.lang.String | مجزء نص للبحث في الصورة. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | إعدادات التعرف. |
| ignoreCase | boolean | True - يعني بحث غير حساس لحالة الأحرف. |

**Returns:**
boolean - صحيح إذا كانت الصورة تحتوي على مجزء نص. خطأ - الصورة لا تحتوي على مجزء نص.
### ImageHasText(String fullPath, Pattern regex) {#ImageHasText-java.lang.String-java.util.regex.Pattern}
```
public boolean ImageHasText(String fullPath, Pattern regex)
```


تحقق مما إذا كان نص الصورة يطابق التعبير النمطي المقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath | java.lang.String | مسار الصورة. |
| regex | java.util.regex.Pattern | كائن java.util.regex.Pattern مع النمط والخيارات المقدمة. |

**Returns:**
boolean - صحيح إذا كان نص الصورة يطابق التعبير النمطي المقدم.
### ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)
```


تحقق مما إذا كان نص الصورة يطابق التعبير النمطي المقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath | java.lang.String | مسار الصورة. |
| regex | java.util.regex.Pattern | كائن java.util.regex.Pattern مع النمط والخيارات المقدمة. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | إعدادات التعرف. |

**Returns:**
boolean - صحيح إذا كان نص الصورة يطابق التعبير النمطي المقدم.
### ImageTextDiff(String fullPath1, String fullPath2) {#ImageTextDiff-java.lang.String-java.lang.String}
```
public float ImageTextDiff(String fullPath1, String fullPath2)
```


قارن النصوص على الصورتين وأرجع رقمًا يمثل مدى تشابههما (من 0 إلى 1).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath1 | java.lang.String | المسار إلى الصورة الأولى. |
| fullPath2 | java.lang.String | المسار إلى الصورة الثانية. |

**Returns:**
float - 0 يعني أن النصوص مختلفة تماماً؛ 1 يعني أن النصوص متطابقة.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)
```


قارن النصوص على الصورتين وأرجع رقمًا يمثل مدى تشابههما (من 0 إلى 1).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath1 | java.lang.String | المسار إلى الصورة الأولى. |
| fullPath2 | java.lang.String | المسار إلى الصورة الثانية. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | إعدادات التعرف. |

**Returns:**
float - 0 يعني أن النصوص مختلفة تماماً؛ 1 يعني أن النصوص متطابقة.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


قارن النصوص على الصورتين وأرجع رقمًا يمثل مدى تشابههما (من 0 إلى 1).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath1 | java.lang.String | المسار إلى الصورة الأولى. |
| fullPath2 | java.lang.String | المسار إلى الصورة الثانية. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | إعدادات التعرف. |
| ignoreCase | boolean | True - يعني بحث غير حساس لحالة الأحرف. |

**Returns:**
float - 0 يعني أن النصوص مختلفة تماماً؛ 1 يعني أن النصوص متطابقة.
### Recognize(OcrInput input) {#Recognize-com.aspose.ocr.OcrInput}
```
public OcrOutput Recognize(OcrInput input)
```


يتعرف على الصورة مع القدرة على تحديد الدعم للأنواع GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, المجلد, المصفوفة, أرشيف zip, URL, base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). مثال. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### Recognize(OcrInput input, RecognitionSettings settings) {#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings}
```
public OcrOutput Recognize(OcrInput input, RecognitionSettings settings)
```


يتعرف على الصورة مع القدرة على تحديد الدعم للأنواع GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, المجلد, المصفوفة, أرشيف zip, URL, base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). مثال. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings) {#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings}
```
public OcrOutput RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)
```


يتعرف على لوحة السيارة مع القدرة على تحديد الدعم للأنواع GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, المجلد, المصفوفة, أرشيف zip, URL, base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). مثال. |
| settings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCharacters(OcrInput input) {#RecognizeCharacters-com.aspose.ocr.OcrInput}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input)
```


يكتشف الرموز في الصور. يدعم GIF، PNG، JPEG، WBMP، TIFF، JFIF، TIFF، PDF، InputStream، BufferedImage، المجلد، المصفوفة، أرشيف zip، URL، base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | الحاوية التي تحتوي على المصادر.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - قائمة ArrayList من [Character](../../com.aspose.ocr.models/character/) مع بيانات الرموز المكتشفة لكل صورة.
### RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language) {#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)
```


يكتشف الرموز في الصور. يدعم GIF، PNG، JPEG، WBMP، TIFF، JFIF، TIFF، PDF، InputStream، BufferedImage، المجلد، المصفوفة، أرشيف zip، URL، base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | الحاوية التي تحتوي على المصادر.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | يحدد نوع الشبكة العصبية المستخدمة لاكتشاف المناطق. |
| language | [Language](../../com.aspose.ocr.models/language/) | اللغة المستخدمة في OCR. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - قائمة ArrayList من [Character](../../com.aspose.ocr.models/character/) مع بيانات الرموز المكتشفة.
### RecognizeFast(OcrInput input) {#RecognizeFast-com.aspose.ocr.OcrInput}
```
public ArrayList<String> RecognizeFast(OcrInput input)
```


يتعرف على النص في صورة ذات جودة جيدة. لا يستخدم تصحيح الانحراف التلقائي للصورة واكتشاف مناطق النص. يدعم GIF، PNG، JPEG، WBMP، TIFF، JFIF، TIFF، PDF، InputStream، BufferedImage، المجلد، المصفوفة، أرشيف zip، URL، base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/) كائن. |

**Returns:**
java.util.ArrayList<java.lang.String> - قائمة ArrayList مع النص المعترف به.
### RecognizeFormula(OcrInput input, boolean detectAreas) {#RecognizeFormula-com.aspose.ocr.OcrInput-boolean}
```
public OcrOutput RecognizeFormula(OcrInput input, boolean detectAreas)
```


يتعرف على الصيغ الرياضية من الصور المدخلة. يدعم GIF، PNG، JPEG، WBMP، TIFF، JFIF، TIFF، PDF، InputStream، BufferedImage، المجلد، المصفوفة، أرشيف zip، URL، base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). مثال. |
| detectAreas | boolean | إذا تم تعيينه إلى true، يكتشف تلقائيًا ويعزل مناطق الصيغة قبل إجراء التعرف. إذا كان false، يعالج الصورة بأكملها كصيغة. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - OcrOutput list with images recognition results [OcrOutput](../../com.aspose.ocr/ocroutput/)
### RecognizeHandwrittenText(OcrInput input) {#RecognizeHandwrittenText-com.aspose.ocr.OcrInput}
```
public OcrOutput RecognizeHandwrittenText(OcrInput input)
```


يتعرف على النص المكتوب بخط اليد في الصور. يدعم GIF، PNG، JPEG، WBMP، TIFF، JFIF، TIFF، PDF، InputStream، BufferedImage، المجلد، المصفوفة، أرشيف zip، URL، base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). الحاوية مع المصادر.. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings) {#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings}
```
public OcrOutput RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)
```


يتعرف على بطاقة الهوية مع القدرة على تحديد الدعم للأنواع GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, المجلد, المصفوفة, أرشيف zip, URL, base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). مثال. |
| settings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings) {#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings}
```
public OcrOutput RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)
```


يتعرف على الفاتورة مع القدرة على تحديد الدعم للأنواع GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, المجلد, المصفوفة, أرشيف zip, URL, base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). مثال. |
| settings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizePassport(OcrInput input, PassportRecognitionSettings settings) {#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings}
```
public OcrOutput RecognizePassport(OcrInput input, PassportRecognitionSettings settings)
```


يتعرف على جواز السفر مع إمكانية التحديد. يدعم GIF، PNG، JPEG، WBMP، TIFF، JFIF، TIFF، PDF، InputStream، BufferedImage، المجلد، المصفوفة، أرشيف zip، URL، base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). مثال. |
| settings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings) {#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings}
```
public OcrOutput RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)
```


يتعرف على الإيصالات مع إمكانية التحديد يدعم GIF و PNG و JPEG و WBMP و TIFF و JFIF و TIFF و PDF و InputStream و BufferedImage و المجلد و المصفوفة و أرشيف zip و URL و base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). مثال. |
| settings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeTables(OcrInput input, Language language) {#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language}
```
public ArrayList<OCRTablePage> RecognizeTables(OcrInput input, Language language)
```


يكتشف الجداول والبنية، يتعرف على خلايا النص. يدعم GIF، PNG، JPEG، WBMP، TIFF، JFIF، TIFF، PDF، InputStream، BufferedImage، المجلد، المصفوفة، أرشيف zip، URL، base64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). مثال. |
| language | [Language](../../com.aspose.ocr.models/language/) | يحدد الأبجدية المستخدمة أثناء التعرف. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.OCRTablePage> - كائنات قائمة OCRTablePage مع النصوص المعترف بها في الجداول. [OCRTablePage](../../com.aspose.ocr.models/ocrtablepage/)
### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)
```


يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | تنسيق المستند (Docx، Txt، Pdf، PdfNoImg، Xlsx، Xml، Json، Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | قائمة بـ [RecognitionResult](../../com.aspose.ocr/recognitionresult/). الكائنات. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | تنسيق المستند (Docx، Txt، Pdf، PdfNoImg، Xlsx، Xml، Json، Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | قائمة بـ [RecognitionResult](../../com.aspose.ocr/recognitionresult/). الكائنات. |
| embeddedFontPath | java.lang.String | اختياريًا. المسار الكامل إلى خط المستخدم. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | تنسيق المستند (Docx، Txt، Pdf، PdfNoImg، Xlsx، Xml، Json، Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | قائمة بـ [RecognitionResult](../../com.aspose.ocr/recognitionresult/). الكائنات. |
| embeddedFontPath | java.lang.String | اختياريًا. المسار الكامل إلى خط المستخدم. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | قلل حجم ملف PDF عن طريق خفض جودة الصور الخلفية. بشكل افتراضي، يتم الحفاظ على جودة الصورة الأصلية. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)
```


يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullFileName | java.lang.String | اسم الملف مع مسار لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | تنسيق المستند (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | قائمة بـ [RecognitionResult](../../com.aspose.ocr/recognitionresult/). الكائنات. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)
```


يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult مع تصحيح التدقيق الإملائي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullFileName | java.lang.String | اسم الملف مع مسار لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | تنسيق المستند (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | قائمة بـ [RecognitionResult](../../com.aspose.ocr/recognitionresult/). الكائنات. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | قيمة تعداد [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullFileName | java.lang.String | اسم الملف مع مسار لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | تنسيق المستند (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | قائمة بـ [RecognitionResult](../../com.aspose.ocr/recognitionresult/). الكائنات. |
| embeddedFontPath | java.lang.String | اختياريًا. المسار الكامل إلى خط المستخدم. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullFileName | java.lang.String | اسم الملف مع مسار لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | تنسيق المستند (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | قائمة بـ [RecognitionResult](../../com.aspose.ocr/recognitionresult/). الكائنات. |
| embeddedFontPath | java.lang.String | اختياريًا. المسار الكامل إلى خط المستخدم. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | قلل حجم ملف PDF عن طريق خفض جودة الصور الخلفية. بشكل افتراضي، يتم الحفاظ على جودة الصورة الأصلية. |

### close() {#close}
```
public void close()
```