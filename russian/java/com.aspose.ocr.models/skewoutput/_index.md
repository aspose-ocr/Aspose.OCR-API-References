---
title: "SkewOutput"
second_title: "Aspose.OCR для Java API Reference"
description: "Данные о угле наклона в градусах и имени файла"
type: docs
weight: 23
url: /ru/java/com.aspose.ocr.models/skewoutput/
---

**Inheritance:**
java.lang.Object
```
public class SkewOutput
```

Данные об угле наклона в градусах и имени файла.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SkewOutput()](#SkewOutput) |  |
| [SkewOutput(String source, double angle, int page)](#SkewOutput-java.lang.String-double-int) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [Angle](#Angle) | Угол наклона в градусах. |
| [Page](#Page) | Номер страницы. |
| [Source](#Source) | Полный путь к файлу или URL, если имеется. |

### SkewOutput() {#SkewOutput}
```
public SkewOutput()
```


### SkewOutput(String source, double angle, int page) {#SkewOutput-java.lang.String-double-int}
```
public SkewOutput(String source, double angle, int page)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | java.lang.String |  |
| угол | double |  |
| страница | int |  |

### Angle {#Angle}
```
public double Angle
```


Угол наклона в градусах.

### Page {#Page}
```
public int Page
```


Номер страницы.

### Source {#Source}
```
public String Source
```


Полный путь к файлу или URL, если он указан. Пусто для потоков, массивов байтов, base64.
