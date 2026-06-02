---
title: "OCRTablePage"
second_title: "Aspose.OCR для Java API Reference"
description: "Представляет структурированные данные таблицы для всей страницы OCR‑документов"
type: docs
weight: 18
url: /ru/java/com.aspose.ocr.models/ocrtablepage/
---

**Inheritance:**
java.lang.Object
```
public class OCRTablePage
```

Представляет структурированные табличные данные для всей страницы OCR‑документа.

Этот объект агрегирует все распознанные таблицы на одной обработанной странице. Каждая страница может содержать одну или несколько обнаруженных таблиц, представленных в виде записей [OCRTable](../../com.aspose.ocr.models/ocrtable/).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OCRTablePage()](#OCRTablePage) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [addTable(OCRTable table)](#addTable-com.aspose.ocr.models.OCRTable) |  |
| [getTables()](#getTables) |  |

### OCRTablePage() {#OCRTablePage}
```
public OCRTablePage()
```


### addTable(OCRTable table) {#addTable-com.aspose.ocr.models.OCRTable}
```
public void addTable(OCRTable table)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| table | [OCRTable](../../com.aspose.ocr.models/ocrtable/) |  |



### getTables() {#getTables}
```
public List<OCRTable> getTables()
```




**Returns:**
java.util.List<com.aspose.ocr.models.OCRTable>
