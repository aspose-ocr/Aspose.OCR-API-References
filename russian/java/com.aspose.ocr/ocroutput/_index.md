---
title: "OcrOutput"
second_title: "Aspose.OCR для Java API Reference"
description: 
type: docs
weight: 21
url: /ru/java/com.aspose.ocr/ocroutput/
---

**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList
```
public class OcrOutput extends ArrayList<RecognitionResult>
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OcrOutput()](#OcrOutput) | Инициализирует новый экземпляр класса OcrOutput с пустой коллекцией. |
## Методы

| Метод | Описание |
| --- | --- |

| [getTableData()](#getTableData) | Возвращает структурированные табличные данные, извлечённые со всех распознанных страниц. |
| [save(OutputStream stream)](#save-java.io.OutputStream) | Сохраняет все результаты распознавания в поток памяти в указанном формате. |
| [save(OutputStream stream, Format saveFormat)](#save-java.io.OutputStream-com.aspose.ocr.models.Format) | Сохраняет все результаты распознавания в поток памяти в указанном формате. |
| [save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Сохраняет все результаты распознавания в поток памяти в указанном формате. |
| [save(String fullFileName)](#save-java.lang.String) | Сохранить все результаты распознавания в файл. |
| [save(String fullFileName, Format saveFormat)](#save-java.lang.String-com.aspose.ocr.models.Format) | Сохранить все результаты распознавания в файл. |
| [save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Сохранить все результаты распознавания в файл. |
| [savePdf(OutputStream stream)](#savePdf-java.io.OutputStream) | Сохранить все результаты распознавания в поисковый PDF‑документ в памяти, внедрив оригинальные изображения в качестве фона. |
| [savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Сохранить все результаты распознавания в поисковый PDF‑документ в памяти, внедрив оригинальные изображения в качестве фона. |
| [savePdf(String fullFileName)](#savePdf-java.lang.String) | Сохранить все результаты распознавания в поисковый PDF‑файл, при этом оригинальные изображения будут установлены в качестве фона. |
| [savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Сохранить все результаты распознавания в поисковый PDF‑файл, при этом оригинальные изображения будут установлены в качестве фона. |

### getTableData() {#getTableData}
```
public OCRTable getTableData()
```


Возвращает структурированные табличные данные, извлечённые со всех распознанных страниц.

Каждая страница содержит строки, а каждая строка содержит ячейки с распознанным текстом и необязательной информацией о позиции.

**Returns:**
[OCRTable](../../com.aspose.ocr.models/ocrtable/) - an [OCRTable](../../com.aspose.ocr.models/ocrtable/) structure representing all tables in the document


### save(OutputStream stream) {#save-java.io.OutputStream}
```
public void save(OutputStream stream)
```


Сохраняет все результаты распознавания в поток памяти в указанном формате.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream для сохранения результата распознавания в выбранном формате. |

### save(OutputStream stream, Format saveFormat) {#save-java.io.OutputStream-com.aspose.ocr.models.Format}
```
public void save(OutputStream stream, Format saveFormat)
```


Сохраняет все результаты распознавания в поток памяти в указанном формате.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream для сохранения результата распознавания в выбранном формате. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Формат документа (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Сохраняет все результаты распознавания в поток памяти в указанном формате.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream для сохранения результата распознавания в выбранном формате. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Формат документа (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | Необязательно. Полный путь к пользовательскому шрифту. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Уменьшите размер PDF‑файла, понижая качество фоновых изображений. По умолчанию сохраняется оригинальное качество изображения. |

### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Сохранить все результаты распознавания в файл.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullFileName | java.lang.String | Имя файла с путём для сохранения результата распознавания в выбранном формате. |

### save(String fullFileName, Format saveFormat) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format saveFormat)
```


Сохранить все результаты распознавания в файл.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullFileName | java.lang.String | Имя файла с путём для сохранения результата распознавания в выбранном формате. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Формат документа (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Сохранить все результаты распознавания в файл.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullFileName | java.lang.String | Имя файла с путём для сохранения результата распознавания в выбранном формате. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Формат документа (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | Необязательно. Полный путь к пользовательскому шрифту. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Уменьшите размер PDF‑файла, понижая качество фоновых изображений. По умолчанию сохраняется оригинальное качество изображения. |

### savePdf(OutputStream stream) {#savePdf-java.io.OutputStream}
```
public void savePdf(OutputStream stream)
```


Сохранить все результаты распознавания в поисковый PDF‑документ в памяти, внедрив оригинальные изображения в качестве фона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream для сохранения результата распознавания в выбранном формате. |

### savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Сохранить все результаты распознавания в поисковый PDF‑документ в памяти, внедрив оригинальные изображения в качестве фона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream для сохранения результата распознавания в выбранном формате. |
| embeddedFontPath | java.lang.String | Необязательно. Полный путь к пользовательскому шрифту. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Уменьшите размер PDF‑файла, понижая качество фоновых изображений. По умолчанию сохраняется оригинальное качество изображения. |

### savePdf(String fullFileName) {#savePdf-java.lang.String}
```
public void savePdf(String fullFileName)
```


Сохранить все результаты распознавания в поисковый PDF‑файл, при этом оригинальные изображения будут установлены в качестве фона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullFileName | java.lang.String | Имя файла с путём для сохранения результата распознавания в выбранном формате. |

### savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Сохранить все результаты распознавания в поисковый PDF‑файл, при этом оригинальные изображения будут установлены в качестве фона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullFileName | java.lang.String | Имя файла с путём для сохранения результата распознавания в выбранном формате. |
| embeddedFontPath | java.lang.String | Необязательно. Полный путь к пользовательскому шрифту. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Уменьшите размер PDF‑файла, понижая качество фоновых изображений. По умолчанию сохраняется оригинальное качество изображения. |

### size() {#size}
```
public int size()
```




**Returns:**
int
