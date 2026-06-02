---
title: "CarPlateRecognitionSettings"
second_title: "Aspose.OCR для Java API Reference"
description: "Настройки распознавания автомобильных номеров содержат элементы, позволяющие настраивать процесс распознавания"
type: docs
weight: 12
url: /ru/java/com.aspose.ocr/carplaterecognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class CarPlateRecognitionSettings
```

Настройки распознавания автомобильных номеров содержат элементы, позволяющие настраивать процесс распознавания
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CarPlateRecognitionSettings()](#CarPlateRecognitionSettings) | Конструктор по умолчанию: установить autoSkew в true. |
## Методы

| Метод | Описание |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType) | Набор разрешённых символов. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Обнаруживает изображения с белым текстом на тёмном/чёрном фоне и автоматически выбирает для них специальный алгоритм OCR. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Устанавливает черный список для символов распознавания. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.Language) |  |
### CarPlateRecognitionSettings() {#CarPlateRecognitionSettings}
```
public CarPlateRecognitionSettings()
```


Конструктор по умолчанию: установить autoSkew в true.





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Набор разрешённых символов. Определяет тип символов, разрешённых в результате распознавания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) | содержит значение перечисления @see [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/). |

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

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr/language/) | Устанавливает язык, используемый для OCR. По умолчанию — мультиязык (none). |

