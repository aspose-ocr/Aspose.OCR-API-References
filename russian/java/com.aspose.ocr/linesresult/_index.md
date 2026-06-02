---
title: "RecognitionResult.LinesResult"
second_title: "Aspose.OCR для Java API Reference"
description: 
type: docs
weight: 10
url: /ru/java/com.aspose.ocr/recognitionresult.linesresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult.LinesResult
```
## Поля

| Поле | Описание |
| --- | --- |
| [confidence](#confidence) | Оценка уверенности, присвоенная распознанной строке текста, представлена в виде числа с плавающей точкой от 0.0 до 1.0. |
| [line](#line) |  |
| [textInLine](#textInLine) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### confidence {#confidence}
```
public double confidence
```


Оценка уверенности, присвоенная распознанной строке текста, представлена в виде числа с плавающей точкой от 0.0 до 1.0. Оценка 1.0 указывает на высший уровень уверенности распознавания.

Это значение всегда устанавливается в 0 при использовании временной лицензии. Уверенность рассчитывается только для следующих языков: группа китайских языков, арабский, хинди, европейские, корейский, японский, телугу, тамильский и каннада.

Уверенность не рассчитывается для ExtLatin или языков, содержащих диакритические знаки.

### line {#line}
```
public Rectangle line
```


### textInLine {#textInLine}
```
public String textInLine
```


### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait}
```
public final void wait()
```




### wait(long arg0) {#wait-long}
```
public final native void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

