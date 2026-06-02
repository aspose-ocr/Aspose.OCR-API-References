---
title: "LayoutOutput"
second_title: "Aspose.OCR для Java API Reference"
description: "Информация об обнаруженных областях содержимого на изображении"
type: docs
weight: 15
url: /ru/java/com.aspose.ocr.models/layoutoutput/
---

**Inheritance:**
java.lang.Object
```
public class LayoutOutput
```

Информация об обнаруженных областях содержимого на изображении.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LayoutOutput()](#LayoutOutput) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [captions](#captions) | Обнаруженные подписи. |
| [equations](#equations) | Обнаруженные уравнения. |
| [headers](#headers) | Обнаруженные заголовки. |
| [images](#images) | Обнаруженные изображения/иллюстрации. |
| [lists](#lists) | Обнаруженные списки. |
| [page](#page) | Номер страницы. |
| [paragraphs](#paragraphs) | Обнаруженные абзацы. |
| [source](#source) | Полный путь к файлу или URL, если имеется. |
| [tables](#tables) | Обнаруженные таблицы. |

### LayoutOutput() {#LayoutOutput}
```
public LayoutOutput()
```


### captions {#captions}
```
public ArrayList<ContentArea> captions
```


Обнаруженные подписи.

### equations {#equations}
```
public ArrayList<ContentArea> equations
```


Обнаруженные уравнения.

### headers {#headers}
```
public ArrayList<ContentArea> headers
```


Обнаруженные заголовки.

### images {#images}
```
public ArrayList<ContentArea> images
```


Обнаруженные изображения/иллюстрации.

### lists {#lists}
```
public ArrayList<ContentArea> lists
```


Обнаруженные списки.

### page {#page}
```
public int page
```


Номер страницы.

### paragraphs {#paragraphs}
```
public ArrayList<ContentArea> paragraphs
```


Обнаруженные абзацы.

### source {#source}
```
public String source
```


Полный путь к файлу или URL, если он указан. Пусто для потоков, массивов байтов, base64.

### tables {#tables}
```
public ArrayList<ContentArea> tables
```


Обнаруженные таблицы.

