---
title: "CarPlateRecognitionSettings"
second_title: "مرجع Aspose.OCR لـ Java API"
description: "إعدادات التعرف على رقم السيارة تحتوي على عناصر تسمح بتخصيص عملية التعرف."
type: docs
weight: 12
url: /ar/java/com.aspose.ocr/carplaterecognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class CarPlateRecognitionSettings
```

إعدادات التعرف على رقم السيارة تحتوي على عناصر تسمح بتخصيص عملية التعرف.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [CarPlateRecognitionSettings()](#CarPlateRecognitionSettings) | المنشئ الافتراضي: اضبط autoSkew إلى true. |
## الدوال

| الدالة | الوصف |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType) | مجموعة الأحرف المسموح بها. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | اكتشف الصور التي تحتوي على نص أبيض على خلفية داكنة/سوداء واختر تلقائيًا خوارزمية OCR خاصة لها. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | يضبط القائمة السوداء لرموز التعرف. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.Language) |  |
### CarPlateRecognitionSettings() {#CarPlateRecognitionSettings}
```
public CarPlateRecognitionSettings()
```


المنشئ الافتراضي: اضبط autoSkew إلى true.





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


مجموعة الأحرف المسموح بها. تحدد نوع الأحرف المسموح بها لنتيجة التعرف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) | يحتوي على قيمة تعداد @see [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/). |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


اكتشف الصور التي تحتوي على نص أبيض على خلفية داكنة/سوداء واختر تلقائيًا خوارزمية OCR خاصة لها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| automaticColorInversion | boolean | يحتوي على قيمة منطقية - تم تعيين automaticColorInversion. |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


يضبط القائمة السوداء لرموز التعرف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| characters | java.lang.String | الأحرف المستبعدة من التعرف. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr/language/) | يضبط اللغة المستخدمة في OCR. متعدد اللغات (بدون) بشكل افتراضي. |

