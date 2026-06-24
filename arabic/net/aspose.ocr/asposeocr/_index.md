---
title: "AsposeOcr"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "API الرئيسي لمكتبة Aspose OCR"
type: docs
weight: 20
url: /ar/net/aspose.ocr/asposeocr/
---
## AsposeOcr class

API الرئيسي لمكتبة Aspose OCR

```csharp
public class AsposeOcr : IDisposable
```

## Constructors

| Name | الوصف |
| --- | --- |
| [AsposeOcr](asposeocr)() | يُنشئ مثيلًا جديدًا من الفئة [`AsposeOcr`](../asposeocr). مُنشئ فارغ. |

## Methods

| Name | الوصف |
| --- | --- |
| [CalculateSkew](../../aspose.ocr/asposeocr/calculateskew)(OcrInput) | يحسب زوايا الانحراف للصور. يدعم GIF، PNG، JPEG، BMP، TIFF، JFIF، التدفق، المجلد، المصفوفات، الأرشيفات. |
| [CompareImageTexts](../../aspose.ocr/asposeocr/compareimagetexts)(string, string, RecognitionSettings, bool) | تحقق مما إذا كانت الصورتان تحتويان على نفس النص. |
| [CorrectSpelling](../../aspose.ocr/asposeocr/correctspelling)(string, SpellCheckLanguage, string) | يصحح النص (يستبدل الكلمات المكتوبة خطأ). |
| [DetectDefects](../../aspose.ocr/asposeocr/detectdefects)(OcrInput, DefectType) | يحدد تلقائيًا المناطق المشكلة في الصورة التي يمكن أن تؤثر بشكل كبير على دقة OCR. يدعم صور PNG، JPEG، BMP، TIFF، JFIF، وGIF المقدمة كملف أو تدفق أو مصفوفة بكسل. يدعم التعرف الجماعي. |
| [DetectDocumentLayout](../../aspose.ocr/asposeocr/detectdocumentlayout)(OcrInput) | يحلل الصورة ويحدد الأنواع المختلفة لمناطق المحتوى داخلها. يدعم صور PNG، JPEG، BMP، TIFF، JFIF، وGIF من ملفات، تدفقات، ومصفوفات بكسل. يمكنه معالجة المجلدات والأرشيفات بشكل جماعي. |
| [DetectLanguages](../../aspose.ocr/asposeocr/detectlanguages)(OcrInput) | يحلل النص على الصورة لتحديد اللغات المكتوبة بها. يتيح ذلك اختيار لغة التعرف الأنسب ويساعد في مهام معالجة النصوص اللاحقة مثل التدقيق الإملائي أو الترجمة. |
| [DetectRectangles](../../aspose.ocr/asposeocr/detectrectangles#detectrectangles)(OcrInput) | يكتشف مناطق النص على الصور. يدعم GIF، PNG، JPEG، BMP، TIFF، JFIF، التدفق، المجلد، المصفوفات، الأرشيفات. |
| [DetectRectangles](../../aspose.ocr/asposeocr/detectrectangles#detectrectangles_1)(OcrInput, AreasType, bool) | يكتشف مناطق النص على الصور. يدعم GIF، PNG، JPEG، BMP، TIFF، JFIF، التدفق، المجلد، المصفوفات، الأرشيفات. |
| [DetectTables](../../aspose.ocr/asposeocr/detecttables)(OcrInput) | يكتشف مناطق الجداول على الصور. يدعم GIF، PNG، JPEG، BMP، TIFF، JFIF، التدفق، المجلد، المصفوفات، الأرشيفات. |
| [Dispose](../../aspose.ocr/asposeocr/dispose)() | مسح الموارد للتعرف. |
| [ImageHasText](../../aspose.ocr/asposeocr/imagehastext#imagehastext_1)(string, Regex, RecognitionSettings, bool) | تحقق مما إذا كان نص الصورة يطابق التعبير النمطي المقدم. |
| [ImageHasText](../../aspose.ocr/asposeocr/imagehastext#imagehastext)(string, string, RecognitionSettings, bool, bool) | تحقق مما إذا كانت الصورة تحتوي على الجزء النصي المقدم. |
| [ImageTextDiff](../../aspose.ocr/asposeocr/imagetextdiff)(string, string, RecognitionSettings, bool, bool) | قارن النصوص على الصورتين وأرجع رقمًا يمثل مدى تشابههما (من 0 إلى 1). |
| [Recognize](../../aspose.ocr/asposeocr/recognize#recognize)(OcrInput) | يتعرف على النص في الصور / المستندات. يدعم GIF، PNG، JPEG، BMP، TIFF، JFIF، التدفق، الدليل، المصفوفات، الأرشيفات. |
| [Recognize](../../aspose.ocr/asposeocr/recognize#recognize_1)(OcrInput, AsposeOcrPresets) | يتعرف على النص من مدخل OCR المعطى باستخدام تكوين مسبق محدد. |
| [Recognize](../../aspose.ocr/asposeocr/recognize#recognize_2)(OcrInput, RecognitionSettings) | يتعرف على النص في الصور / المستندات. يدعم GIF، PNG، JPEG، BMP، TIFF، JFIF، التدفق، الدليل، المصفوفات، الأرشيفات. |
| [Recognize](../../aspose.ocr/asposeocr/recognize#recognize_3)(OcrInput, RecognitionSettings, CancellationToken) | يتعرف على النص في الصور / المستندات. يدعم GIF، PNG، JPEG، BMP، TIFF، JFIF، التدفق، الدليل، المصفوفات، الأرشيفات. |
| [RecognizeCarPlate](../../aspose.ocr/asposeocr/recognizecarplate#recognizecarplate)(OcrInput) | يتعرف على النص على لوحة السيارة. |
| [RecognizeCarPlate](../../aspose.ocr/asposeocr/recognizecarplate#recognizecarplate_1)(OcrInput, CarPlateRecognitionSettings) | يتعرف على النص على لوحة السيارة. |
| [RecognizeCharacters](../../aspose.ocr/asposeocr/recognizecharacters#recognizecharacters)(OcrInput) | يكشف عن الرموز في الصور. يدعم GIF و PNG و JPEG و BMP و TIFF و JFIF، التدفق، المجلد، المصفوفات، الأرشيفات. |
| [RecognizeCharacters](../../aspose.ocr/asposeocr/recognizecharacters#recognizecharacters_1)(OcrInput, DetectAreasMode, Language) | يكشف عن الرموز في الصور. يدعم GIF و PNG و JPEG و BMP و TIFF و JFIF، التدفق، المجلد، المصفوفات، الأرشيفات. |
| [RecognizeFast](../../aspose.ocr/asposeocr/recognizefast)(OcrInput) | يتعرف على النص في الصور / المستندات. يدعم GIF، PNG، JPEG، BMP، TIFF، JFIF، التدفق، الدليل، المصفوفات، الأرشيفات. |
| [RecognizeFormula](../../aspose.ocr/asposeocr/recognizeformula)(OcrInput, bool) | يتعرف على الصيغ الرياضية من صور الإدخال المقدمة. |
| [RecognizeFormulaAI](../../aspose.ocr/asposeocr/recognizeformulaai)(OcrInput) | يتعرف على الصيغ الرياضية من صور الإدخال المقدمة باستخدام الذكاء الاصطناعي. |
| [RecognizeHandwrittenText](../../aspose.ocr/asposeocr/recognizehandwrittentext)(OcrInput) | يتعرف على النص المكتوب بخط اليد في الصور. |
| [RecognizeIDCard](../../aspose.ocr/asposeocr/recognizeidcard#recognizeidcard)(OcrInput) | يتعرف على النص على بطاقة الهوية. |
| [RecognizeIDCard](../../aspose.ocr/asposeocr/recognizeidcard#recognizeidcard_1)(OcrInput, IDCardRecognitionSettings) | يتعرف على النص على بطاقة الهوية. |
| [RecognizeInvoice](../../aspose.ocr/asposeocr/recognizeinvoice#recognizeinvoice)(OcrInput) | يتعرف على النص على الفواتير. |
| [RecognizeInvoice](../../aspose.ocr/asposeocr/recognizeinvoice#recognizeinvoice_1)(OcrInput, InvoiceRecognitionSettings) | يتعرف على النص على الفواتير. |
| [RecognizeLines](../../aspose.ocr/asposeocr/recognizelines#recognizelines)(OcrInput) | يتعرف على الصور التي تحتوي على سطر واحد من النص. يدعم GIF و PNG و JPEG و BMP و TIFF و JFIF، التدفق، المجلد، المصفوفات، الأرشيفات. |
| [RecognizeLines](../../aspose.ocr/asposeocr/recognizelines#recognizelines_1)(OcrInput, RecognitionSettings) | يتعرف على الصور التي تحتوي على سطر واحد من النص. يدعم GIF و PNG و JPEG و BMP و TIFF و JFIF، التدفق، المجلد، المصفوفات، الأرشيفات. |
| [RecognizePassport](../../aspose.ocr/asposeocr/recognizepassport#recognizepassport)(OcrInput) | يتعرف على النص على جواز السفر. |
| [RecognizePassport](../../aspose.ocr/asposeocr/recognizepassport#recognizepassport_1)(OcrInput, PassportRecognitionSettings) | يتعرف على النص على جواز السفر. |
| [RecognizeReceipt](../../aspose.ocr/asposeocr/recognizereceipt#recognizereceipt)(OcrInput) | يتعرف على النص على الإيصالات. |
| [RecognizeReceipt](../../aspose.ocr/asposeocr/recognizereceipt#recognizereceipt_1)(OcrInput, ReceiptRecognitionSettings) | يتعرف على النص على الإيصالات. |
| [RecognizeTables](../../aspose.ocr/asposeocr/recognizetables)(OcrInput, Language) | يكشف عن الجداول والبنية، ويتعرف على خلايا النص. يدعم GIF و PNG و JPEG و BMP و TIFF و JFIF، التدفق، الدليل، المصفوفات، الأرشيفات. |
| static [SaveMultipageDocument](../../aspose.ocr/asposeocr/savemultipagedocument#savemultipagedocument_1)(MemoryStream, SaveFormat, List&lt;RecognitionResult&gt;, string, PdfOptimizationMode) | يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult. |
| static [SaveMultipageDocument](../../aspose.ocr/asposeocr/savemultipagedocument#savemultipagedocument_3)(string, SaveFormat, List&lt;RecognitionResult&gt;, string, PdfOptimizationMode) | يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult. |
| static [SaveMultipageDocument](../../aspose.ocr/asposeocr/savemultipagedocument#savemultipagedocument)(MemoryStream, SaveFormat, List&lt;RecognitionResult&gt;, bool, SpellCheckLanguage, string, string, PdfOptimizationMode) | يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult. |
| static [SaveMultipageDocument](../../aspose.ocr/asposeocr/savemultipagedocument#savemultipagedocument_2)(string, SaveFormat, List&lt;RecognitionResult&gt;, bool, SpellCheckLanguage, string, string, PdfOptimizationMode) | يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult. |

## الحقول

| Name | الوصف |
| --- | --- |
| static [DebugMode](../../aspose.ocr/asposeocr/debugmode) | يفعل وضع التصحيح. عند التفعيل، يقوم النظام بحفظ نتائج معالجة الصور الوسيطة مثل الصور المعالجة مسبقًا والصور التي تحتوي على مستطيلات خطوط النص المرسومة. |
| static [DebugModeSaveDirectory](../../aspose.ocr/asposeocr/debugmodesavedirectory) | الدليل الذي سيتم حفظ نتائج التصحيح فيه. إذا لم يتم تحديده، سيُستخدم الدليل العامل الحالي كإعداد افتراضي. |

## الأحداث

| Name | الوصف |
| --- | --- |
| event [OcrProgress](../../aspose.ocr/asposeocr/ocrprogress) | حدث لتتبع تقدم التعرف على الصور متعددة الصفحات. |

### انظر أيضًا

* namespace [Aspose.OCR](../../aspose.ocr)
* assembly [Aspose.OCR](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
