---
title: "PassportRecognitionSettings"
second_title: "مرجع Aspose.OCR لـ Java API"
description: "إعدادات التعرف على جواز السفر تحتوي على عناصر تسمح بتخصيص عملية التعرف."
type: docs
weight: 23
url: /ar/java/com.aspose.ocr/passportrecognitionsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.ocr.ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/)
```
public class PassportRecognitionSettings extends ReceiptRecognitionSettings
```

إعدادات التعرف على جواز السفر تحتوي على عناصر تسمح بتخصيص عملية التعرف.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PassportRecognitionSettings()](#PassportRecognitionSettings) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | مجموعة الأحرف المسموح بها. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | مجموعة الأحرف المسموح بها. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | اكتشف الصور التي تحتوي على نص أبيض على خلفية داكنة/سوداء واختر تلقائيًا خوارزمية OCR خاصة لها. |
| [setCountry(Country country)](#setCountry-com.aspose.ocr.models.Country) | حدد القالب للتعرف على جواز السفر واستخراج الكلمات المفتاحية. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | يضبط القائمة السوداء لرموز التعرف. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | يحدد مستوى اكتشاف اللغة للتعرف على النص. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | يحصل أو يضبط عدد الخيوط للمعالجة. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | يسمح لك باستخدام خوارزميات إضافية خصيصًا للتعرف على الخطوط الصغيرة. |
### PassportRecognitionSettings() {#PassportRecognitionSettings}
```
public PassportRecognitionSettings()
```





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
| allowedCharacters | java.lang.String | يحتوي على مصفوفة من الأحرف. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


اكتشف الصور التي تحتوي على نص أبيض على خلفية داكنة/سوداء واختر تلقائيًا خوارزمية OCR خاصة لها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| automaticColorInversion | boolean | يحتوي على قيمة منطقية - تم ضبط automaticColorInversion. |

### setCountry(Country country) {#setCountry-com.aspose.ocr.models.Country}
```
public void setCountry(Country country)
```


حدد القالب للتعرف على جواز السفر واستخراج الكلمات المفتاحية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| country | [Country](../../com.aspose.ocr.models/country/) | بلد جواز السفر. |

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


يحدد مستوى اكتشاف اللغة للتعرف على النص. يعمل فقط إذا كانت اللغة المحددة هي Language.MULTILANGUAGE أو Language.AUTO أو Language.UNIVERSAL. هذه العملية تستغرق وقتًا طويلاً وتبطئ بشكل كبير التعرف العام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) | قيمة تعداد لتعيين المستوى (Paragraph, Word, Page). |

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


يسمح لك باستخدام خوارزميات إضافية خصيصًا للتعرف على الخطوط الصغيرة. مفيد للصور التي تحتوي على أحرف صغيرة الحجم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| upscaleSmallFont | boolean | يحتوي على قيمة منطقية - تم ضبط upscaleSmallFont. |
