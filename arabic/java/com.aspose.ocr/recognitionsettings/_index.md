---
title: "RecognitionSettings"
second_title: "مرجع Aspose.OCR لـ Java API"
description: "إعدادات التعرف على الصورة"
type: docs
weight: 27
url: /ar/java/com.aspose.ocr/recognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionSettings
```

إعدادات التعرف على الصورة. يحتوي على عناصر تسمح بتخصيص عملية التعرف.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [RecognitionSettings()](#RecognitionSettings) | المنشئ الافتراضي: تعيين recognitionAreas إلى null، linesFiltration إلى false، autoSkew إلى false، recognizeSingleLine إلى false. |
| [RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)](#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean) | المنشئ يسمح بتعيين جميع الخيارات. |
| [RecognitionSettings(boolean recognizeSingleLine)](#RecognitionSettings-boolean) | المنشئ يسمح بتعيين recognizeSingleLine. |
| [RecognitionSettings(ReceiptRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings) |  |
| [RecognitionSettings(InvoiceRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings) |  |
| [RecognitionSettings(IDCardRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings) |  |
| [RecognitionSettings(PassportRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings) |  |
| [RecognitionSettings(CarPlateRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings) |  |
## الدوال

| الدالة | الوصف |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | مجموعة الأحرف المسموح بها. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | مجموعة الأحرف المسموح بها. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | اكتشف الصور التي تحتوي على نص أبيض على خلفية داكنة/سوداء واختر تلقائيًا خوارزمية OCR خاصة لها. |
| [setDetectAreasMode(DetectAreasMode detectAreasMode)](#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode) | يحدد نوع الشبكة العصبية المستخدمة لاكتشاف المناطق. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | يضبط القائمة السوداء لرموز التعرف. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | يحدد مستوى اكتشاف اللغة لتعرف النص. |
| [setLinesFiltration(boolean linesFiltration)](#setLinesFiltration-boolean) | يسمح بالتعرف على النص في الجداول (المناطق المحاطة بالخطوط). |
| [setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)](#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle) | يضبط قائمة مناطق النص للمعالجة. |
| [setRecognizeSingleLine(boolean recognizeSingleLine)](#setRecognizeSingleLine-boolean) | يضبط التعرف على الصورة ذات السطر الواحد. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | يحصل أو يضبط عدد الخيوط للمعالجة. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | يسمح لك باستخدام خوارزميات إضافية خصيصًا لتعرف الخط الصغير. |
### RecognitionSettings() {#RecognitionSettings}
```
public RecognitionSettings()
```


المنشئ الافتراضي: تعيين recognitionAreas إلى null، linesFiltration إلى false، autoSkew إلى false، recognizeSingleLine إلى false.

### RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine) {#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean}
```
public RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)
```


المنشئ يسمح بتعيين جميع الخيارات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | مستطيلات للتعرف. |
| recognizeSingleLine | boolean | صحيح إذا كانت الصورة تحتوي على سطر واحد فقط. |

### RecognitionSettings(boolean recognizeSingleLine) {#RecognitionSettings-boolean}
```
public RecognitionSettings(boolean recognizeSingleLine)
```


المُنشئ يسمح بتعيين recognizeSingleLine. القيم الافتراضية في هذه الحالة: detectAreas - false، autoSkew = false، recognitionAreas - null.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| recognizeSingleLine | boolean | صحيح إذا كانت الصورة تحتوي على سطر واحد فقط. |

### RecognitionSettings(ReceiptRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings}
```
public RecognitionSettings(ReceiptRecognitionSettings recSettings)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| recSettings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) |  |

### RecognitionSettings(InvoiceRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings}
```
public RecognitionSettings(InvoiceRecognitionSettings recSettings)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| recSettings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) |  |

### RecognitionSettings(IDCardRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings}
```
public RecognitionSettings(IDCardRecognitionSettings recSettings)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| recSettings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) |  |

### RecognitionSettings(PassportRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings}
```
public RecognitionSettings(PassportRecognitionSettings recSettings)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| recSettings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) |  |

### RecognitionSettings(CarPlateRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings}
```
public RecognitionSettings(CarPlateRecognitionSettings recSettings)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| recSettings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) |  |




### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


مجموعة الأحرف المسموح بها. تحدد نوع الأحرف المسموح بها لنتيجة التعرف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) | يحتوي على قيمة تعداد @see [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/). |

### setAllowedCharacters(String allowedCharacters) {#setAllowedCharacters-java.lang.String}
```
public void setAllowedCharacters(String allowedCharacters)
```


مجموعة الأحرف المسموح بها. تحدد مصفوفة الأحرف المسموح بها لنتيجة التعرف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| allowedCharacters | java.lang.String | يحتوي على سلسلة من الأحرف. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


اكتشف الصور التي تحتوي على نص أبيض على خلفية داكنة/سوداء واختر تلقائيًا خوارزمية OCR خاصة لها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| automaticColorInversion | boolean | يحتوي على قيمة منطقية - تم تعيين automaticColorInversion. صحيح بشكل افتراضي. |

### setDetectAreasMode(DetectAreasMode detectAreasMode) {#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode}
```
public void setDetectAreasMode(DetectAreasMode detectAreasMode)
```


يحدد نوع الشبكة العصبية المستخدمة لاكتشاف المناطق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | يحتوي على قيمة تعداد @see [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/). |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


يضبط القائمة السوداء لرموز التعرف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| characters | java.lang.String | الأحرف المستبعدة من التعرف. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.models.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr.models/language/) | يضبط اللغة المستخدمة في OCR. متعدد اللغات (بدون) بشكل افتراضي. |

### setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel) {#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel}
```
public void setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)
```


يحدد مستوى اكتشاف اللغة لتعرف النص. يعمل فقط إذا كانت اللغة المختارة هي Language.MULTILANGUAGE أو Language.AUTO أو Language.UNIVERSAL. هذه العملية تستغرق وقتًا طويلاً وتبطئ بشكل كبير التعرف العام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) |  |

### setLinesFiltration(boolean linesFiltration) {#setLinesFiltration-boolean}
```
public void setLinesFiltration(boolean linesFiltration)
```


يسمح بالتعرف على النص في الجداول (المناطق المحاطة بالخطوط).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| linesFiltration | boolean | false - يسمح بزيادة الأداء وعدم اكتشاف الجداول وإزالة الخطوط؛ وإلا - true. معطل (false) بشكل افتراضي. |

### setRecognitionAreas(ArrayList<Rectangle> recognitionAreas) {#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle}
```
public void setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)
```


يضبط قائمة مناطق النص للمعالجة. يسمح بتحديد المناطق التي تحتوي على نص يدويًا للحصول على تعريف أكثر دقة. إذا تم تعيين مناطق مخصصة [setDetectAreasMode(DetectAreasMode)](../../com.aspose.ocr/recognitionsettings/\#setDetectAreasMode-DetectAreasMode) (DetectAreasMode)\} ليست NONE أو [PreprocessingFilter.AutoSkew()](../../com.aspose.ocr/preprocessingfilter/\#AutoSkew) (boolean)\} سيتم تجاهل الخصائص. يعطل DetectAreas و AutoSkew.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | مستطيلات للتعرف. |

### setRecognizeSingleLine(boolean recognizeSingleLine) {#setRecognizeSingleLine-boolean}
```
public void setRecognizeSingleLine(boolean recognizeSingleLine)
```


يضبط التعرف على الصور ذات السطر الواحد. معطل (false) بشكل افتراضي. يعطل جميع خطوات المعالجة المرتبطة بالتقسيم إلى أسطر. اضبط هذا المعامل إلى true إذا كانت صورتك تحتوي على سطر واحد فقط. يعطل إعدادات [setRecognitionAreas(ArrayList)](../../com.aspose.ocr/recognitionsettings/\#setRecognitionAreas-ArrayList)، لذا سيتم تجاهل جميع إعدادات المناطق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| recognizeSingleLine | boolean | صحيح لصورة ذات سطر واحد |

### setThreadsCount(int threadsCount) {#setThreadsCount-int}
```
public void setThreadsCount(int threadsCount)
```


يحصل أو يضبط عدد الخيوط للمعالجة. بشكل افتراضي، 0 يعني أن الصورة ستُعالج بعدد خيوط يساوي عدد المعالجات لديك. ThreadsCount = 1 يعني أن الصورة ستُعالج في الخيط الرئيسي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| threadsCount | int | عدد الخيوط التي سيتم إنشاؤها للتعرف المتوازي على أجزاء الصورة. |

### setUpscaleSmallFont(boolean upscaleSmallFont) {#setUpscaleSmallFont-boolean}
```
public void setUpscaleSmallFont(boolean upscaleSmallFont)
```


يسمح لك باستخدام خوارزميات إضافية خصيصًا لتعرف الخط الصغير. مفيد للصور التي تحتوي على أحرف صغيرة الحجم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| upscaleSmallFont | boolean | يحتوي على قيمة منطقية - تم تعيين upscaleSmallFont. |

### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String