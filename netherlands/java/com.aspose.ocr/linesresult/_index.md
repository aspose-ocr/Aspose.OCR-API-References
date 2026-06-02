---
title: "RecognitionResult.LinesResult"
second_title: "Aspose.OCR for Java API-referentie"
description: 
type: docs
weight: 10
url: /nl/java/com.aspose.ocr/recognitionresult.linesresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult.LinesResult
```
## Velden

| Veld | Beschrijving |
| --- | --- |
| [confidence](#confidence) | De vertrouwensscore toegewezen aan de herkende tekstreeks, weergegeven als een zwevendekommagetal tussen 0.0 en 1.0. |
| [line](#line) |  |
| [textInLine](#textInLine) |  |
## Methoden

| Methode | Beschrijving |
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


De vertrouwensscore toegewezen aan de herkende tekstreeks, weergegeven als een zwevendekommagetal tussen 0.0 en 1.0. Een score van 1.0 geeft het hoogste niveau van herkenningszekerheid aan.

Deze waarde wordt altijd op 0 gezet bij gebruik van een tijdelijke licentie. Vertrouwen wordt alleen berekend voor de volgende talen: Chinese taalgroep, Arabisch, Hindi, Europees, Koreaans, Japans, Telugu, Tamil en Kannada.

Vertrouwen wordt niet berekend voor ExtLatin of talen die diakritische tekens bevatten.

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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

