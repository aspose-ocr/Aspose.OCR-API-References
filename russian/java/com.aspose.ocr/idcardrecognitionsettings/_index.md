---
title: "IDCardRecognitionSettings"
second_title: "Aspose.OCR для Java API Reference"
description: "Настройки распознавания удостоверения личности содержат элементы, позволяющие настраивать процесс распознавания"
type: docs
weight: 14
url: /ru/java/com.aspose.ocr/idcardrecognitionsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.ocr.ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/)
```
public class IDCardRecognitionSettings extends ReceiptRecognitionSettings
```

Настройки распознавания удостоверения личности содержат элементы, позволяющие настраивать процесс распознавания
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [IDCardRecognitionSettings()](#IDCardRecognitionSettings) | Конструктор по умолчанию: установить autoSkew в true. |
## Методы

| Метод | Описание |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Набор разрешённых символов. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | Набор разрешённых символов. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Обнаруживает изображения с белым текстом на тёмном/чёрном фоне и автоматически выбирает для них специальный алгоритм OCR. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Устанавливает черный список для символов распознавания. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Указывает уровень обнаружения языка для распознавания текста. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | Получает или задает количество потоков для обработки. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Позволяет использовать дополнительные алгоритмы специально для распознавания мелкого шрифта. |
### IDCardRecognitionSettings() {#IDCardRecognitionSettings}
```
public IDCardRecognitionSettings()
```


Конструктор по умолчанию: установить autoSkew в true.



### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Набор разрешённых символов. Определяет тип символов, разрешённых в результате распознавания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) | содержит enum @see [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) value. |

### setAllowedCharacters(String allowedCharacters) {#setAllowedCharacters-java.lang.String}
```
public void setAllowedCharacters(String allowedCharacters)
```


Набор разрешённых символов. Определяет массив символов, разрешённых в результате распознавания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| allowedCharacters | java.lang.String | содержит массив символов. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Обнаруживает изображения с белым текстом на тёмном/чёрном фоне и автоматически выбирает для них специальный алгоритм OCR.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| automaticColorInversion | boolean | содержит логическое значение - установлен automaticColorInversion. |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


Устанавливает черный список для символов распознавания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| characters | java.lang.String | Символы, исключённые из распознавания. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.models.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr.models/language/) | Устанавливает язык, используемый для OCR. По умолчанию — мультиязык (none). |

### setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel) {#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel}
```
public void setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)
```


Указывает уровень обнаружения языка для распознавания текста. Работает только если выбранный язык — Language.MULTILANGUAGE, Language.AUTO или Language.UNIVERSAL. Этот процесс требует много времени и значительно замедляет общее распознавание.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) | значение перечисления для установки уровня (Paragraph, Word, Page). |

### setThreadsCount(int threadsCount) {#setThreadsCount-int}
```
public void setThreadsCount(int threadsCount)
```


Получает или задает количество потоков для обработки. По умолчанию 0 означает, что изображение будет обрабатываться с количеством потоков, равным числу процессоров. ThreadsCount = 1 означает, что изображение будет обрабатываться в основном потоке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threadsCount | int | количество потоков, которые будут созданы для параллельного распознавания фрагментов изображения. |

### setUpscaleSmallFont(boolean upscaleSmallFont) {#setUpscaleSmallFont-boolean}
```
public void setUpscaleSmallFont(boolean upscaleSmallFont)
```


Позволяет использовать дополнительные алгоритмы специально для распознавания мелкого шрифта. Полезно для изображений с небольшими символами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| upscaleSmallFont | boolean | содержит логическое значение - установлен upscaleSmallFont. |

