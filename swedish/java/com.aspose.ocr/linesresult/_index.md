---
title: "RecognitionResult.LinesResult"
second_title: "Aspose.OCR för Java API-referens"
description: 
type: docs
weight: 10
url: /sv/java/com.aspose.ocr/recognitionresult.linesresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult.LinesResult
```
## Fält

| Fält | Beskrivning |
| --- | --- |
| [confidence](#confidence) | Konfidenspoängen som tilldelas den igenkända textraden, representerad som ett flyttal mellan 0.0 och 1.0. |
| [line](#line) |  |
| [textInLine](#textInLine) |  |
## Metoder

| Metod | Beskrivning |
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


Konfidenspoängen som tilldelas den igenkända textraden, representerad som ett flyttal mellan 0.0 och 1.0. Ett värde på 1.0 indikerar den högsta nivån av igenkänningssäkerhet.

Detta värde sätts alltid till 0 när en tillfällig licens används. Konfidens beräknas endast för följande språk: kinesisk språkgrupp, arabiska, hindi, europeiska, koreanska, japanska, telugu, tamil och kannada.

Konfidens beräknas inte för ExtLatin eller språk som innehåller diakritiska tecken.

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
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

