---
title: "OcrOutput"
second_title: "مرجع Aspose.OCR لـ Java API"
description: 
type: docs
weight: 21
url: /ar/java/com.aspose.ocr/ocroutput/
---

**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList
```
public class OcrOutput extends ArrayList<RecognitionResult>
```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [OcrOutput()](#OcrOutput) | يفّتح مثيلًا جديدًا من فئة OcrOutput بمجموعة فارغة. |
## الدوال

| الدالة | الوصف |
| --- | --- |

| [getTableData()](#getTableData) | يعيد بيانات جدولية منظمة مستخرجة من جميع الصفحات المعترف بها. |
| [save(OutputStream stream)](#save-java.io.OutputStream) | احفظ جميع نتائج التعرف إلى تدفق ذاكرة بالصيغة المحددة. |
| [save(OutputStream stream, Format saveFormat)](#save-java.io.OutputStream-com.aspose.ocr.models.Format) | احفظ جميع نتائج التعرف إلى تدفق ذاكرة بالصيغة المحددة. |
| [save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | احفظ جميع نتائج التعرف إلى تدفق ذاكرة بالصيغة المحددة. |
| [save(String fullFileName)](#save-java.lang.String) | احفظ جميع نتائج التعرف في ملف. |
| [save(String fullFileName, Format saveFormat)](#save-java.lang.String-com.aspose.ocr.models.Format) | احفظ جميع نتائج التعرف في ملف. |
| [save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | احفظ جميع نتائج التعرف في ملف. |
| [savePdf(OutputStream stream)](#savePdf-java.io.OutputStream) | احفظ جميع نتائج التعرف في مستند PDF قابل للبحث في الذاكرة، مع تضمين الصور الأصلية كخلفية. |
| [savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | احفظ جميع نتائج التعرف في مستند PDF قابل للبحث في الذاكرة، مع تضمين الصور الأصلية كخلفية. |
| [savePdf(String fullFileName)](#savePdf-java.lang.String) | احفظ جميع نتائج التعرف في ملف PDF قابل للبحث، مع تعيين الصور الأصلية كخلفية. |
| [savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | احفظ جميع نتائج التعرف في ملف PDF قابل للبحث، مع تعيين الصور الأصلية كخلفية. |

### getTableData() {#getTableData}
```
public OCRTable getTableData()
```


يعيد بيانات جدولية منظمة مستخرجة من جميع الصفحات المعترف بها.

كل صفحة تحتوي على صفوف، وكل صف يحتوي على خلايا بالنص المعترف به ومعلومات الموقع الاختيارية.

**Returns:**
[OCRTable](../../com.aspose.ocr.models/ocrtable/) - an [OCRTable](../../com.aspose.ocr.models/ocrtable/) structure representing all tables in the document


### save(OutputStream stream) {#save-java.io.OutputStream}
```
public void save(OutputStream stream)
```


احفظ جميع نتائج التعرف إلى تدفق ذاكرة بالصيغة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream لحفظ نتيجة التعرف بالتنسيق المحدد. |

### save(OutputStream stream, Format saveFormat) {#save-java.io.OutputStream-com.aspose.ocr.models.Format}
```
public void save(OutputStream stream, Format saveFormat)
```


احفظ جميع نتائج التعرف إلى تدفق ذاكرة بالصيغة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | تنسيق المستند (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


احفظ جميع نتائج التعرف إلى تدفق ذاكرة بالصيغة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | تنسيق المستند (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | اختياري. المسار الكامل إلى خط المستخدم. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | قلل حجم ملف PDF عن طريق خفض جودة الصور الخلفية. بشكل افتراضي، يتم الحفاظ على جودة الصورة الأصلية. |

### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


احفظ جميع نتائج التعرف في ملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullFileName | java.lang.String | اسم الملف مع مسار لحفظ نتيجة التعرف بالتنسيق المحدد. |

### save(String fullFileName, Format saveFormat) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format saveFormat)
```


احفظ جميع نتائج التعرف في ملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullFileName | java.lang.String | اسم الملف مع مسار لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | تنسيق المستند (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


احفظ جميع نتائج التعرف في ملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullFileName | java.lang.String | اسم الملف مع مسار لحفظ نتيجة التعرف بالتنسيق المحدد. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | تنسيق المستند (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | اختياري. المسار الكامل إلى خط المستخدم. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | قلل حجم ملف PDF عن طريق خفض جودة الصور الخلفية. بشكل افتراضي، يتم الحفاظ على جودة الصورة الأصلية. |

### savePdf(OutputStream stream) {#savePdf-java.io.OutputStream}
```
public void savePdf(OutputStream stream)
```


احفظ جميع نتائج التعرف في مستند PDF قابل للبحث في الذاكرة، مع تضمين الصور الأصلية كخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream لحفظ نتيجة التعرف بالتنسيق المحدد. |

### savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


احفظ جميع نتائج التعرف في مستند PDF قابل للبحث في الذاكرة، مع تضمين الصور الأصلية كخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream لحفظ نتيجة التعرف بالتنسيق المحدد. |
| embeddedFontPath | java.lang.String | اختياري. المسار الكامل إلى خط المستخدم. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | قلل حجم ملف PDF عن طريق خفض جودة الصور الخلفية. بشكل افتراضي، يتم الحفاظ على جودة الصورة الأصلية. |

### savePdf(String fullFileName) {#savePdf-java.lang.String}
```
public void savePdf(String fullFileName)
```


احفظ جميع نتائج التعرف في ملف PDF قابل للبحث، مع تعيين الصور الأصلية كخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullFileName | java.lang.String | اسم الملف مع مسار لحفظ نتيجة التعرف بالتنسيق المحدد. |

### savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


احفظ جميع نتائج التعرف في ملف PDF قابل للبحث، مع تعيين الصور الأصلية كخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullFileName | java.lang.String | اسم الملف مع مسار لحفظ نتيجة التعرف بالتنسيق المحدد. |
| embeddedFontPath | java.lang.String | اختياري. المسار الكامل إلى خط المستخدم. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | قلل حجم ملف PDF عن طريق خفض جودة الصور الخلفية. بشكل افتراضي، يتم الحفاظ على جودة الصورة الأصلية. |

### size() {#size}
```
public int size()
```




**Returns:**
int
