---
title: "RecognitionResult"
second_title: "Aspose.OCR для Java API Reference"
description: "Результаты распознавания изображения"
type: docs
weight: 26
url: /ru/java/com.aspose.ocr/recognitionresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult
```

Результаты распознавания изображения. Содержит элементы с информацией о распознавании и методы экспорта результатов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RecognitionResult()](#RecognitionResult) | Инициализирует новый экземпляр |
## Поля

| Поле | Описание |
| --- | --- |
| [language](#language) | Язык распознанного текста на изображении. |
| [recognitionCharactersList](#recognitionCharactersList) | Набор символов, найденных алгоритмом распознавания и упорядоченных по убыванию вероятности. |
| [recognitionLinesResult](#recognitionLinesResult) | Получает список результатов распознавания со списком строк (прямоугольников). |
| [recognitionRegionsResult](#recognitionRegionsResult) | Получает список результатов распознавания со списком областей (прямоугольников). |
| [recognitionText](#recognitionText) | Результат распознавания всей страницы или отдельной области. |
| [warnings](#warnings) | Получает или задает список сообщений предупреждений, описывающих некритические ошибки, возникшие во время генерации. |
## Методы

| Метод | Описание |
| --- | --- |
| [GetJson()](#GetJson) | Создаёт JSON‑строку с результатами распознавания. |
| [GetKeywords()](#GetKeywords) | Получить ключевые слова из паспорта (тестовый режим). |
| [GetXml()](#GetXml) | Создаёт JSON‑строку с результатами распознавания. |
| [SetKeyword(String key, RecognitionResult.LinesResult result)](#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult) |  |
| [getSpellCheckCorrectedText()](#getSpellCheckCorrectedText) | Корректирует текст (заменяет ошибочно написанные слова). |
| [getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)](#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Корректирует текст (заменяет ошибочно написанные слова). |
| [getSpellCheckErrorList()](#getSpellCheckErrorList) | Найдите слова с ошибками и предложенные варианты написания для заданного входного текста. |
| [getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)](#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Найдите слова с ошибками и предложенные варианты написания для заданного входного текста. |
| [save(String fullFileName)](#save-java.lang.String) | Сохраняет документ в виде простого текста |
| [save(String fullFileName, Format format)](#save-java.lang.String-com.aspose.ocr.models.Format) | Сохраняет документ в виде простого текста или в другом формате документа. |
| [save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode) | Сохраняет документ в виде простого текста или в другом формате документа. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format) | Сохраняет исправленный с английским словарём текст в документе в виде простого текста или в формате Microsoft Word Text Document. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Сохраняет исправленный текст в документе в виде простого текста или в другом формате. |
| [toString()](#toString) |  |
| [useUserDictionary(String dictionaryPath)](#useUserDictionary-java.lang.String) | Позволяет использовать собственный словарь для исправления орфографии. |
### RecognitionResult() {#RecognitionResult}
```
public RecognitionResult()
```


Инициализирует новый экземпляр

### language {#language}
```
public Language language
```


Язык распознанного текста на изображении. Это значение определяется автоматически, если выбраны Language.AUTO, Language.MULTILANGUAGE или Language.UNIVERSAL.

### recognitionCharactersList {#recognitionCharactersList}
```
public ArrayList<char[]> recognitionCharactersList
```


Набор символов, найденных алгоритмом распознавания и упорядоченных по убыванию вероятности.

### recognitionLinesResult {#recognitionLinesResult}
```
public ArrayList<RecognitionResult.LinesResult> recognitionLinesResult
```


Получает список результатов распознавания со списком строк (прямоугольников).

### recognitionRegionsResult {#recognitionRegionsResult}
```
public ArrayList<RecognitionResult.RegionResult> recognitionRegionsResult
```


Получает список результатов распознавания со списком областей (прямоугольников).

### recognitionText {#recognitionText}
```
public String recognitionText
```


Результат распознавания всей страницы или отдельной области.

### warnings {#warnings}
```
public ArrayList<String> warnings
```


Получает или задает список сообщений предупреждений, описывающих некритические ошибки, возникшие во время генерации.

### GetJson() {#GetJson}
```
public String GetJson()
```


Создаёт JSON‑строку с результатами распознавания.

**Returns:**
java.lang.String — результаты распознавания в виде JSON‑строки.
### GetKeywords() {#GetKeywords}
```
public HashMap<String,RecognitionResult.LinesResult> GetKeywords()
```


Получить ключевые слова из паспорта (тестовый режим. Работает только с паспортами США и МАДАГАСКАРА).

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.ocr.RecognitionResult.LinesResult> — словарь, где ключом является ключевое слово, а значением — LinesResult.
### GetXml() {#GetXml}
```
public String GetXml()
```


Создаёт JSON‑строку с результатами распознавания.

**Returns:**
java.lang.String — результаты распознавания в виде XML‑строки.
### SetKeyword(String key, RecognitionResult.LinesResult result) {#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult}
```
public void SetKeyword(String key, RecognitionResult.LinesResult result)
```



### getSpellCheckCorrectedText() {#getSpellCheckCorrectedText}
```
public String getSpellCheckCorrectedText()
```


Корректирует текст (заменяет ошибочно написанные слова).

**Returns:**
java.lang.String — строка исправленных результатов распознавания. Словарь по умолчанию — английский.
### getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language) {#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)
```


Корректирует текст (заменяет ошибочно написанные слова).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Словарь для использования. |

**Returns:**
java.lang.String — строка исправленных результатов распознавания.
### getSpellCheckErrorList() {#getSpellCheckErrorList}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList()
```


Найдите слова с ошибками и предложенные варианты написания для заданного входного текста. Словарь по умолчанию — английский.

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> — ArrayList объектов SpellCheckError, представляющих слова с ошибками, содержащих списки предложенных правильных написаний для каждого ошибочного слова и расстояние редактирования.
### getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language) {#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)
```


Найдите слова с ошибками и предложенные варианты написания для заданного входного текста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Словарь для использования. |

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> — ArrayList объектов SpellCheckError, представляющих слова с ошибками, содержащих списки предложенных правильных написаний для каждого ошибочного слова и расстояние редактирования.




### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Сохраняет документ в виде простого текста

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullFileName | java.lang.String | Имя файла с путём для сохранения результата распознавания |

### save(String fullFileName, Format format) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format format)
```


Сохраняет документ в виде простого текста или в другом формате документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullFileName | java.lang.String | Имя файла с путём для сохранения результата распознавания. |
| format | [Format](../../com.aspose.ocr.models/format/) | Перечисление форматов документа типа Format. |

### save(String fullFileName, Format format, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)
```


Сохраняет документ в виде простого текста или в другом формате документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullFileName | java.lang.String | Имя файла с путём для сохранения результата распознавания. |
| format | [Format](../../com.aspose.ocr.models/format/) | Перечисление форматов документа типа Format. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Уменьшите размер PDF‑файла, понижая качество фоновых изображений. По умолчанию сохраняется оригинальное качество изображения. |

### saveSpellCheckCorrectedText(String fullFileName, Format format) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format)
```


Сохраняет исправленный с английским словарём текст в документе в виде простого текста или в формате Microsoft Word Text Document.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullFileName | java.lang.String | Имя файла с путём для сохранения результата распознавания. |
| format | [Format](../../com.aspose.ocr.models/format/) | Перечисление форматов документа типа Format. |

### saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)
```


Сохраняет исправленный текст в документе в виде простого текста или в другом формате.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullFileName | java.lang.String | Имя файла с путём для сохранения результата распознавания. |
| format | [Format](../../com.aspose.ocr.models/format/) | Перечисление форматов документа типа Format. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Словарь для проверки орфографии. |
### useUserDictionary(String dictionaryPath) {#useUserDictionary-java.lang.String}
```
public void useUserDictionary(String dictionaryPath)
```


Позволяет использовать собственный словарь для исправления орфографии.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dictionaryPath | java.lang.String | Полный путь к пользовательскому словарю (словарю частот). Формат файла словаря: обычный текстовый файл в кодировке UTF-8. Слово и частота слова разделяются запятой, слово ожидается в первом столбце, а частота — во втором. Каждая пара слово‑частота находится в отдельной строке. Строка определяется как последовательность символов, за которой следует перевод строки ("\n"), возврат каретки ("\r"), или возврат каретки, сразу за которым следует перевод строки ("\r\n"). Ожидается, что каждое слово будет в нижнем регистре. |
