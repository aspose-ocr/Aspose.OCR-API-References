---
title: "AsposeOCR"
second_title: "Aspose.OCR для Java API Reference"
description: "Основной класс для распознавания текста с изображений"
type: docs
weight: 10
url: /ru/java/com.aspose.ocr/asposeocr/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public class AsposeOCR implements AutoCloseable
```

Основной класс для распознавания текста с изображений.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [AsposeOCR()](#AsposeOCR) | Публичный конструктор. |
## Поля

| Поле | Описание |
| --- | --- |
| [DebugMode](#DebugMode) | Включает режим отладки. |
| [DebugModeSaveDirectory](#DebugModeSaveDirectory) | Каталог, в котором будут сохраняться результаты отладки. |
## Методы

| Метод | Описание |
| --- | --- |
| [CalculateSkew(OcrInput input)](#CalculateSkew-com.aspose.ocr.OcrInput) | Вычисляет углы наклона изображений. |
| [CompareImageTexts(String fullPath1, String fullPath2)](#CompareImageTexts-java.lang.String-java.lang.String) | Проверяет, содержат ли два изображения один и тот же текст. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Проверяет, содержат ли два изображения один и тот же текст. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Проверяет, содержат ли два изображения один и тот же текст. |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Корректирует текст (заменяет ошибочно написанные слова). |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String) | Корректирует текст (заменяет ошибочно написанные слова). |
| [DetectDefects(OcrInput input, DefectType defectType)](#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType) | Автоматически находит проблемные области изображения, которые могут существенно влиять на точность OCR. |
| [DetectDocumentLayout(OcrInput input)](#DetectDocumentLayout-com.aspose.ocr.OcrInput) | Анализирует изображение и определяет различные типы областей контента внутри него. |
| [DetectLanguages(OcrInput input)](#DetectLanguages-com.aspose.ocr.OcrInput) | Анализирует текст на изображении, чтобы определить, на каких языках он написан. |
| [DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)](#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean) | Обнаруживает текстовые области на изображениях. |
| [DetectTables(OcrInput images)](#DetectTables-com.aspose.ocr.OcrInput) | Обнаруживает области таблиц на изображениях. |
| [ImageHasText(String fullPath, String text)](#ImageHasText-java.lang.String-java.lang.String) | Проверяет, содержит ли изображение предоставленный фрагмент текста без учёта регистра. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Проверяет, содержит ли изображение предоставленный фрагмент текста без учёта регистра. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Проверяет, содержит ли изображение предоставленный фрагмент текста. |
| [ImageHasText(String fullPath, Pattern regex)](#ImageHasText-java.lang.String-java.util.regex.Pattern) | Проверяет, соответствует ли текст изображения предоставленному регулярному выражению. |
| [ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings) | Проверяет, соответствует ли текст изображения предоставленному регулярному выражению. |
| [ImageTextDiff(String fullPath1, String fullPath2)](#ImageTextDiff-java.lang.String-java.lang.String) | Сравнивает тексты на двух изображениях и возвращает число, представляющее степень их схожести (от 0 до 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Сравнивает тексты на двух изображениях и возвращает число, представляющее степень их схожести (от 0 до 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Сравнивает тексты на двух изображениях и возвращает число, представляющее степень их схожести (от 0 до 1). |
| [Recognize(OcrInput input)](#Recognize-com.aspose.ocr.OcrInput) | Распознаёт изображение с возможностью указать поддерживаемые форматы GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папка, массив, zip‑архив, URL, base64. |
| [Recognize(OcrInput input, RecognitionSettings settings)](#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings) | Распознаёт изображение с возможностью указать поддерживаемые форматы GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папка, массив, zip‑архив, URL, base64. |
| [RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)](#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings) | Распознаёт номерные знаки автомобилей с возможностью указать поддерживаемые форматы GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папка, массив, zip‑архив, URL, base64. |
| [RecognizeCharacters(OcrInput input)](#RecognizeCharacters-com.aspose.ocr.OcrInput) | Обнаруживает символы на изображениях. |
| [RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)](#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language) | Обнаруживает символы на изображениях. |
| [RecognizeFast(OcrInput input)](#RecognizeFast-com.aspose.ocr.OcrInput) | Распознаёт текст на изображении высокого качества. |
| [RecognizeFormula(OcrInput input, boolean detectAreas)](#RecognizeFormula-com.aspose.ocr.OcrInput-boolean) | Распознаёт математические формулы из предоставленных входных изображений. |
| [RecognizeHandwrittenText(OcrInput input)](#RecognizeHandwrittenText-com.aspose.ocr.OcrInput) | Распознаёт рукописный текст на изображениях. |
| [RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)](#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings) | Распознаёт удостоверения личности с возможностью указать поддерживаемые форматы GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папка, массив, zip‑архив, URL, base64. |
| [RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)](#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings) | Распознаёт счета-фактуры с возможностью указать поддерживаемые форматы GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папка, массив, zip‑архив, URL, base64. |
| [RecognizePassport(OcrInput input, PassportRecognitionSettings settings)](#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings) | Распознает паспорт с возможностью указания. |
| [RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)](#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings) | Распознает чеки с возможностью указания Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папку, массив, zip‑архив, URL, base64. |
| [RecognizeTables(OcrInput input, Language language)](#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language) | Обнаруживает таблицы и структуру, распознает текстовые ячейки. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | Позволяет получить многостраничный документ из списка объектов RecognitionResult. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | Позволяет получить многостраничный документ из списка объектов RecognitionResult. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Позволяет получить многостраничный документ из списка объектов RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | Позволяет получить многостраничный документ из списка объектов RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Позволяет получить многостраничный документ из списка объектов RecognitionResult с исправлением орфографии. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | Позволяет получить многостраничный документ из списка объектов RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Позволяет получить многостраничный документ из списка объектов RecognitionResult. |
| [close()](#close) |  |

### AsposeOCR() {#AsposeOCR}
```
public AsposeOCR()
```


Публичный конструктор.

### DebugMode {#DebugMode}
```
public static boolean DebugMode
```


Включает режим отладки. При включении система сохраняет промежуточные результаты обработки изображений, такие как предварительно обработанные изображения и изображения с нарисованными прямоугольниками текстовых линий.

### DebugModeSaveDirectory {#DebugModeSaveDirectory}
```
public static String DebugModeSaveDirectory
```


Каталог, в котором будут сохраняться результаты отладки. Если не указан, по умолчанию будет использоваться текущий рабочий каталог.

### CalculateSkew(OcrInput input) {#CalculateSkew-com.aspose.ocr.OcrInput}
```
public ArrayList<SkewOutput> CalculateSkew(OcrInput input)
```


Вычисляет углы наклона изображений. Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папку, массив, zip‑архив, URL, base64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Контейнер с исходниками.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.SkewOutput> - ArrayList углов наклона в градусах [SkewOutput](../../com.aspose.ocr.models/skewoutput/)
### CompareImageTexts(String fullPath1, String fullPath2) {#CompareImageTexts-java.lang.String-java.lang.String}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2)
```


Проверяет, содержат ли два изображения один и тот же текст.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullPath1 | java.lang.String | Путь к первому изображению. |
| fullPath2 | java.lang.String | Путь ко второму изображению. |

**Returns:**
boolean - True если изображения имеют одинаковый текст (90% сходства).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)
```


Проверяет, содержат ли два изображения один и тот же текст.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullPath1 | java.lang.String | Путь к первому изображению. |
| fullPath2 | java.lang.String | Путь ко второму изображению. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Настройки распознавания. |

**Returns:**
boolean - True если изображения имеют одинаковый текст (90% сходства).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


Проверяет, содержат ли два изображения один и тот же текст.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullPath1 | java.lang.String | Путь к первому изображению. |
| fullPath2 | java.lang.String | Путь ко второму изображению. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Настройки распознавания. |
| ignoreCase | boolean | True - означает поиск без учёта регистра. |

**Returns:**
boolean - True если изображения имеют одинаковый текст (90% сходства).
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)
```


Корректирует текст (заменяет ошибочно написанные слова).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для исправления. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Словарь для использования [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |

**Returns:**
java.lang.String - Текст с заменёнными словами.
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)
```


Корректирует текст (заменяет ошибочно написанные слова).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для исправления. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Словарь для использования [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |
| dictionaryPath | java.lang.String | Полный путь к пользовательскому словарю (словарю частот). Формат файла словаря: обычный текстовый файл в кодировке UTF-8. Слово и частота слова разделяются запятой, слово ожидается в первом столбце, а частота — во втором. Каждая пара слово‑частота находится в отдельной строке. Строка определяется как последовательность символов, за которой следует перевод строки ("\n"), возврат каретки ("\r"), или возврат каретки, сразу за которым следует перевод строки ("\r\n"). Ожидается, что каждое слово будет в нижнем регистре. |

**Returns:**
java.lang.String - Текст с заменёнными словами.
### DetectDefects(OcrInput input, DefectType defectType) {#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType}
```
public ArrayList<DefectOutput> DetectDefects(OcrInput input, DefectType defectType)
```


Автоматически находить проблемные области изображения, которые могут существенно влиять на точность OCR. Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папку, массив, zip‑архив, URL, base64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Контейнер с исходниками.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| defectType | [DefectType](../../com.aspose.ocr.models/defecttype/) | Типы дефектов, которые нужно распознать [DefectType](../../com.aspose.ocr.models/defecttype/). |

**Returns:**
java.util.ArrayList<com.aspose.ocr.DefectOutput> - ArrayList из [DefectOutput](../../com.aspose.ocr/defectoutput/) с обнаруженными областями текста или строками.
### DetectDocumentLayout(OcrInput input) {#DetectDocumentLayout-com.aspose.ocr.OcrInput}
```
public ArrayList<LayoutOutput> DetectDocumentLayout(OcrInput input)
```


Анализирует изображение и определяет различные типы областей содержимого внутри него. Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папку, массив, zip‑архив, URL, base64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Контейнер с исходниками.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LayoutOutput> - Обнаруженные области содержимого. ArrayList из [LayoutOutput](../../com.aspose.ocr.models/layoutoutput/)
### DetectLanguages(OcrInput input) {#DetectLanguages-com.aspose.ocr.OcrInput}
```
public ArrayList<LanguageDetectionOutput> DetectLanguages(OcrInput input)
```


Анализирует текст на изображении, чтобы определить, на каких языках он написан. Это позволяет выбрать наиболее подходящий язык распознавания и помогает в дальнейших задачах обработки текста, таких как проверка орфографии или перевод. Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папку, массив, zip‑архив, URL, base64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Контейнер с исходниками.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LanguageDetectionOutput> - Возвращает список наиболее вероятных языков, упорядоченных по вероятности. ArrayList из [LanguageDetectionOutput](../../com.aspose.ocr.models/languagedetectionoutput/)
### DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas) {#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean}
```
public ArrayList<RectangleOutput> DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)
```


Обнаруживает текстовые области на изображениях. Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папку, массив, zip‑архив, URL, base64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Контейнер с исходниками.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| areasType | [AreasType](../../com.aspose.ocr.models/areastype/) | Определяет, какие прямоугольники возвращать — строки или абзацы. |
| isDetectAreas | boolean | Включить автоматическое обнаружение текстовых областей. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList из [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) с обнаруженными текстовыми областями или строками.
### DetectTables(OcrInput images) {#DetectTables-com.aspose.ocr.OcrInput}
```
public ArrayList<RectangleOutput> DetectTables(OcrInput images)
```


Обнаруживает области таблиц на изображениях. Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папку, массив, zip‑архив, URL, base64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Контейнер с исходниками.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList из [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) с обнаруженными областями таблиц.
### ImageHasText(String fullPath, String text) {#ImageHasText-java.lang.String-java.lang.String}
```
public boolean ImageHasText(String fullPath, String text)
```


Проверяет, содержит ли изображение предоставленный фрагмент текста без учёта регистра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullPath | java.lang.String | Путь к изображению. |
| text | java.lang.String | Текстовый фрагмент для поиска на изображении. |

**Returns:**
boolean - True, если изображение содержит текстовый фрагмент. False - изображение не содержит текстовый фрагмент.
### ImageHasText(String fullPath, String text, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings)
```


Проверяет, содержит ли изображение предоставленный фрагмент текста без учёта регистра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullPath | java.lang.String | Путь к изображению. |
| text | java.lang.String | Текстовый фрагмент для поиска на изображении. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Настройки распознавания. |

**Returns:**
boolean - True, если изображение содержит текстовый фрагмент. False - изображение не содержит текстовый фрагмент.
### ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)
```


Проверяет, содержит ли изображение предоставленный фрагмент текста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullPath | java.lang.String | Путь к изображению. |
| text | java.lang.String | Текстовый фрагмент для поиска на изображении. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Настройки распознавания. |
| ignoreCase | boolean | True - означает поиск без учёта регистра. |

**Returns:**
boolean - True, если изображение содержит текстовый фрагмент. False - изображение не содержит текстовый фрагмент.
### ImageHasText(String fullPath, Pattern regex) {#ImageHasText-java.lang.String-java.util.regex.Pattern}
```
public boolean ImageHasText(String fullPath, Pattern regex)
```


Проверяет, соответствует ли текст изображения предоставленному регулярному выражению.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullPath | java.lang.String | Путь к изображению. |
| regex | java.util.regex.Pattern | Объект java.util.regex.Pattern с предоставленным шаблоном и параметрами. |

**Returns:**
boolean — True, если текст изображения соответствует предоставленному регулярному выражению.
### ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)
```


Проверяет, соответствует ли текст изображения предоставленному регулярному выражению.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullPath | java.lang.String | Путь к изображению. |
| regex | java.util.regex.Pattern | Объект java.util.regex.Pattern с предоставленным шаблоном и параметрами. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Настройки распознавания. |

**Returns:**
boolean — True, если текст изображения соответствует предоставленному регулярному выражению.
### ImageTextDiff(String fullPath1, String fullPath2) {#ImageTextDiff-java.lang.String-java.lang.String}
```
public float ImageTextDiff(String fullPath1, String fullPath2)
```


Сравнивает тексты на двух изображениях и возвращает число, представляющее степень их схожести (от 0 до 1).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullPath1 | java.lang.String | Путь к первому изображению. |
| fullPath2 | java.lang.String | Путь ко второму изображению. |

**Returns:**
float — 0 означает, что тексты полностью различаются; 1 означает, что тексты идентичны.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)
```


Сравнивает тексты на двух изображениях и возвращает число, представляющее степень их схожести (от 0 до 1).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullPath1 | java.lang.String | Путь к первому изображению. |
| fullPath2 | java.lang.String | Путь ко второму изображению. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Настройки распознавания. |

**Returns:**
float — 0 означает, что тексты полностью различаются; 1 означает, что тексты идентичны.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


Сравнивает тексты на двух изображениях и возвращает число, представляющее степень их схожести (от 0 до 1).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullPath1 | java.lang.String | Путь к первому изображению. |
| fullPath2 | java.lang.String | Путь ко второму изображению. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Настройки распознавания. |
| ignoreCase | boolean | True - означает поиск без учёта регистра. |

**Returns:**
float — 0 означает, что тексты полностью различаются; 1 означает, что тексты идентичны.
### Recognize(OcrInput input) {#Recognize-com.aspose.ocr.OcrInput}
```
public OcrOutput Recognize(OcrInput input)
```


Распознаёт изображение с возможностью указать поддерживаемые форматы GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папка, массив, zip‑архив, URL, base64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). экземпляр. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### Recognize(OcrInput input, RecognitionSettings settings) {#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings}
```
public OcrOutput Recognize(OcrInput input, RecognitionSettings settings)
```


Распознаёт изображение с возможностью указать поддерживаемые форматы GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папка, массив, zip‑архив, URL, base64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). экземпляр. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings) {#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings}
```
public OcrOutput RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)
```


Распознаёт номерные знаки автомобилей с возможностью указать поддерживаемые форматы GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папка, массив, zip‑архив, URL, base64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). экземпляр. |
| settings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCharacters(OcrInput input) {#RecognizeCharacters-com.aspose.ocr.OcrInput}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input)
```


Обнаруживает символы на изображениях. Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папку, массив, zip‑архив, URL, base64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Контейнер с исходниками.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - ArrayList объектов [Character](../../com.aspose.ocr.models/character/) с данными обнаруженных символов для каждого изображения.
### RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language) {#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)
```


Обнаруживает символы на изображениях. Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папку, массив, zip‑архив, URL, base64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Контейнер с исходниками.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | Определяет тип нейронной сети, используемой для обнаружения областей. |
| language | [Language](../../com.aspose.ocr.models/language/) | Язык, используемый для OCR. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - ArrayList объектов [Character](../../com.aspose.ocr.models/character/) с данными обнаруженных символов.
### RecognizeFast(OcrInput input) {#RecognizeFast-com.aspose.ocr.OcrInput}
```
public ArrayList<String> RecognizeFast(OcrInput input)
```


Распознаёт текст на изображении хорошего качества. Не использует автоматическое исправление наклона изображения и обнаружение текстовых областей. Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папку, массив, zip‑архив, URL, base64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Экземпляр [OcrInput](../../com.aspose.ocr/ocrinput/). |

**Returns:**
java.util.ArrayList<java.lang.String> - ArrayList с распознанным текстом.
### RecognizeFormula(OcrInput input, boolean detectAreas) {#RecognizeFormula-com.aspose.ocr.OcrInput-boolean}
```
public OcrOutput RecognizeFormula(OcrInput input, boolean detectAreas)
```


Распознаёт математические формулы из предоставленных входных изображений. Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папку, массив, zip‑архив, URL, base64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). экземпляр. |
| detectAreas | boolean | Если установлено в true, автоматически обнаруживает и изолирует области формул перед выполнением распознавания. Если false, обрабатывает всё изображение как формулу. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - OcrOutput list with images recognition results [OcrOutput](../../com.aspose.ocr/ocroutput/)
### RecognizeHandwrittenText(OcrInput input) {#RecognizeHandwrittenText-com.aspose.ocr.OcrInput}
```
public OcrOutput RecognizeHandwrittenText(OcrInput input)
```


Распознаёт рукописный текст на изображениях. Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папку, массив, zip‑архив, URL, base64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). Контейнер с источниками.. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings) {#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings}
```
public OcrOutput RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)
```


Распознаёт удостоверения личности с возможностью указать поддерживаемые форматы GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папка, массив, zip‑архив, URL, base64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). экземпляр. |
| settings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings) {#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings}
```
public OcrOutput RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)
```


Распознаёт счета-фактуры с возможностью указать поддерживаемые форматы GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папка, массив, zip‑архив, URL, base64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). экземпляр. |
| settings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizePassport(OcrInput input, PassportRecognitionSettings settings) {#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings}
```
public OcrOutput RecognizePassport(OcrInput input, PassportRecognitionSettings settings)
```


Распознаёт паспорт с возможностью указания. Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папку, массив, zip‑архив, URL, base64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). экземпляр. |
| settings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings) {#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings}
```
public OcrOutput RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)
```


Распознает чеки с возможностью указания Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папку, массив, zip‑архив, URL, base64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). экземпляр. |
| settings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeTables(OcrInput input, Language language) {#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language}
```
public ArrayList<OCRTablePage> RecognizeTables(OcrInput input, Language language)
```


Обнаруживает таблицы и структуру, распознаёт текстовые ячейки. Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, папку, массив, zip‑архив, URL, base64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). экземпляр. |
| language | [Language](../../com.aspose.ocr.models/language/) | Определяет алфавит, используемый при распознавании. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.OCRTablePage> - объекты списка OCRTablePage с распознанными текстами в таблицах. [OCRTablePage](../../com.aspose.ocr.models/ocrtablepage/)
### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)
```


Позволяет получить многостраничный документ из списка объектов RecognitionResult.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream для сохранения результата распознавания в выбранном формате. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Формат документа (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Список объектов [RecognitionResult](../../com.aspose.ocr/recognitionresult/). |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


Позволяет получить многостраничный документ из списка объектов RecognitionResult.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream для сохранения результата распознавания в выбранном формате. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Формат документа (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Список объектов [RecognitionResult](../../com.aspose.ocr/recognitionresult/). |
| embeddedFontPath | java.lang.String | Опционально. Полный путь к пользовательскому шрифту. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Позволяет получить многостраничный документ из списка объектов RecognitionResult.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream для сохранения результата распознавания в выбранном формате. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Формат документа (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Список объектов [RecognitionResult](../../com.aspose.ocr/recognitionresult/). |
| embeddedFontPath | java.lang.String | Опционально. Полный путь к пользовательскому шрифту. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Уменьшите размер PDF‑файла, понижая качество фоновых изображений. По умолчанию сохраняется оригинальное качество изображения. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)
```


Позволяет получить многостраничный документ из списка объектов RecognitionResult.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullFileName | java.lang.String | Имя файла с путём для сохранения результата распознавания в выбранном формате. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Формат документа (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Список объектов [RecognitionResult](../../com.aspose.ocr/recognitionresult/). |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)
```


Позволяет получить многостраничный документ из списка объектов RecognitionResult с исправлением орфографии.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullFileName | java.lang.String | Имя файла с путём для сохранения результата распознавания в выбранном формате. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Формат документа (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Список объектов [RecognitionResult](../../com.aspose.ocr/recognitionresult/). |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Значение перечисления [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


Позволяет получить многостраничный документ из списка объектов RecognitionResult.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullFileName | java.lang.String | Имя файла с путём для сохранения результата распознавания в выбранном формате. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Формат документа (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Список объектов [RecognitionResult](../../com.aspose.ocr/recognitionresult/). |
| embeddedFontPath | java.lang.String | Опционально. Полный путь к пользовательскому шрифту. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Позволяет получить многостраничный документ из списка объектов RecognitionResult.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullFileName | java.lang.String | Имя файла с путём для сохранения результата распознавания в выбранном формате. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Формат документа (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Список объектов [RecognitionResult](../../com.aspose.ocr/recognitionresult/). |
| embeddedFontPath | java.lang.String | Опционально. Полный путь к пользовательскому шрифту. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Уменьшите размер PDF‑файла, понижая качество фоновых изображений. По умолчанию сохраняется оригинальное качество изображения. |

### close() {#close}
```
public void close()
```