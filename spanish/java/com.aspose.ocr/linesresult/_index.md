---
title: "RecognitionResult.LinesResult"
second_title: "Referencia de API de Aspose.OCR para Java"
description: 
type: docs
weight: 10
url: /es/java/com.aspose.ocr/recognitionresult.linesresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult.LinesResult
```
## Campos

| Campo | Descripción |
| --- | --- |
| [confidence](#confidence) | La puntuación de confianza asignada a la línea de texto reconocida, representada como un valor de punto flotante entre 0.0 y 1.0. |
| [line](#line) |  |
| [textInLine](#textInLine) |  |
## Métodos

| Método | Descripción |
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


La puntuación de confianza asignada a la línea de texto reconocida, representada como un valor de punto flotante entre 0.0 y 1.0. Una puntuación de 1.0 indica el nivel más alto de certeza en el reconocimiento.

Este valor siempre se establece en 0 al usar una licencia temporal. La confianza solo se calcula para los siguientes idiomas: grupo de idiomas chino, árabe, hindi, europeo, coreano, japonés, telugu, tamil y kannada.

La confianza no se calcula para ExtLatin o idiomas que contienen marcas diacríticas.

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
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

