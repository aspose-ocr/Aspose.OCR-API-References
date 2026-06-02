---
title: "RecognitionSettings"
second_title: "Aspose.OCR для Java API Reference"
description: "Настройки распознавания изображения"
type: docs
weight: 27
url: /ru/java/com.aspose.ocr/recognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionSettings
```

Настройки распознавания изображения. Содержит элементы, позволяющие настраивать процесс распознавания.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RecognitionSettings()](#RecognitionSettings) | Конструктор по умолчанию: устанавливает recognitionAreas в null, linesFiltration в false, autoSkew в false, recognizeSingleLine в false. |
| [RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)](#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean) | Конструктор позволяет установить все параметры. |
| [RecognitionSettings(boolean recognizeSingleLine)](#RecognitionSettings-boolean) | Конструктор позволяет установить recognizeSingleLine. |
| [RecognitionSettings(ReceiptRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings) |  |
| [RecognitionSettings(InvoiceRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings) |  |
| [RecognitionSettings(IDCardRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings) |  |
| [RecognitionSettings(PassportRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings) |  |
| [RecognitionSettings(CarPlateRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Набор разрешённых символов. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | Набор разрешённых символов. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Обнаруживает изображения с белым текстом на тёмном/чёрном фоне и автоматически выбирает для них специальный алгоритм OCR. |
| [setDetectAreasMode(DetectAreasMode detectAreasMode)](#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode) | Определяет тип нейронной сети, используемой для обнаружения областей. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Устанавливает черный список для символов распознавания. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Указывает уровень обнаружения языка для распознавания текста. |
| [setLinesFiltration(boolean linesFiltration)](#setLinesFiltration-boolean) | Позволяет распознавать текст в таблицах (области, окружённые линиями). |
| [setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)](#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle) | Устанавливает список областей текста для обработки. |
| [setRecognizeSingleLine(boolean recognizeSingleLine)](#setRecognizeSingleLine-boolean) | Устанавливает однострочное распознавание изображения. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | Получает или задает количество потоков для обработки. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Позволяет использовать дополнительные алгоритмы специально для распознавания мелкого шрифта. |
### RecognitionSettings() {#RecognitionSettings}
```
public RecognitionSettings()
```


Конструктор по умолчанию: устанавливает recognitionAreas в null, linesFiltration в false, autoSkew в false, recognizeSingleLine в false.

### RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine) {#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean}
```
public RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)
```


Конструктор позволяет установить все параметры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Прямоугольники для распознавания. |
| recognizeSingleLine | boolean | True, если изображение содержит только одну строку. |

### RecognitionSettings(boolean recognizeSingleLine) {#RecognitionSettings-boolean}
```
public RecognitionSettings(boolean recognizeSingleLine)
```


Конструктор позволяет установить recognizeSingleLine. Значения по умолчанию в этом случае: detectAreas — false, autoSkew = false, recognitionAreas — null.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recognizeSingleLine | boolean | True, если изображение содержит только одну строку. |

### RecognitionSettings(ReceiptRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings}
```
public RecognitionSettings(ReceiptRecognitionSettings recSettings)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recSettings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) |  |

### RecognitionSettings(InvoiceRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings}
```
public RecognitionSettings(InvoiceRecognitionSettings recSettings)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recSettings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) |  |

### RecognitionSettings(IDCardRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings}
```
public RecognitionSettings(IDCardRecognitionSettings recSettings)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recSettings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) |  |

### RecognitionSettings(PassportRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings}
```
public RecognitionSettings(PassportRecognitionSettings recSettings)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recSettings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) |  |

### RecognitionSettings(CarPlateRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings}
```
public RecognitionSettings(CarPlateRecognitionSettings recSettings)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recSettings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) |  |




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
| allowedCharacters | java.lang.String | содержит строку символов. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Обнаруживает изображения с белым текстом на тёмном/чёрном фоне и автоматически выбирает для них специальный алгоритм OCR.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| automaticColorInversion | boolean | содержит логическое значение — установлен automaticColorInversion. True по умолчанию. |

### setDetectAreasMode(DetectAreasMode detectAreasMode) {#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode}
```
public void setDetectAreasMode(DetectAreasMode detectAreasMode)
```


Определяет тип нейронной сети, используемой для обнаружения областей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | содержит значение перечисления @see [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/). |

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
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) |  |

### setLinesFiltration(boolean linesFiltration) {#setLinesFiltration-boolean}
```
public void setLinesFiltration(boolean linesFiltration)
```


Позволяет распознавать текст в таблицах (области, окружённые линиями).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| linesFiltration | boolean | false — повышает производительность и не обнаруживает таблицы и не удаляет линии; иначе — true. Отключено (false) по умолчанию. |

### setRecognitionAreas(ArrayList<Rectangle> recognitionAreas) {#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle}
```
public void setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)
```


Устанавливает список текстовых областей для обработки. Позволяет вручную указать области с текстом для более точного распознавания. Если пользовательские области заданы [setDetectAreasMode(DetectAreasMode)](../../com.aspose.ocr/recognitionsettings/\#setDetectAreasMode-DetectAreasMode) (DetectAreasMode)\} не NONE или [PreprocessingFilter.AutoSkew()](../../com.aspose.ocr/preprocessingfilter/\#AutoSkew) (boolean)\} свойства будут игнорироваться. Отключает DetectAreas и AutoSkew.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Прямоугольники для распознавания. |

### setRecognizeSingleLine(boolean recognizeSingleLine) {#setRecognizeSingleLine-boolean}
```
public void setRecognizeSingleLine(boolean recognizeSingleLine)
```


Устанавливает распознавание однострочного изображения. Отключено (false) по умолчанию. Отключает все шаги обработки, связанные с разбиением на строки. Установите этот параметр в true, если ваше изображение содержит только одну строку. Отключает настройки [setRecognitionAreas(ArrayList)](../../com.aspose.ocr/recognitionsettings/\#setRecognitionAreas-ArrayList), поэтому все настройки областей будут игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recognizeSingleLine | boolean | True для однострочного изображения. |

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
| upscaleSmallFont | boolean | содержит логическое значение — установлен upscaleSmallFont. |

### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String