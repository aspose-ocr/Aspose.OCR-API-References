---
title: "RecognitionResult.LinesResult"
second_title: "Aspose.OCR für Java API-Referenz"
description: 
type: docs
weight: 10
url: /de/java/com.aspose.ocr/recognitionresult.linesresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult.LinesResult
```
## Felder

| Feld | Beschreibung |
| --- | --- |
| [confidence](#confidence) | Der Vertrauenswert, der der erkannten Textzeile zugewiesen wird, dargestellt als Gleitkommawert zwischen 0,0 und 1,0. |
| [line](#line) |  |
| [textInLine](#textInLine) |  |
## Methoden

| Methode | Beschreibung |
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


Der Vertrauenswert, der der erkannten Textzeile zugewiesen wird, dargestellt als Gleitkommawert zwischen 0,0 und 1,0. Ein Wert von 1,0 zeigt das höchste Maß an Erkennungssicherheit an.

Dieser Wert wird bei Verwendung einer temporären Lizenz immer auf 0 gesetzt. Der Vertrauenswert wird nur für die folgenden Sprachen berechnet: Chinesische Sprachgruppe, Arabisch, Hindi, Europäisch, Koreanisch, Japanisch, Telugu, Tamil und Kannada.

Der Vertrauenswert wird für ExtLatin oder Sprachen mit diakritischen Zeichen nicht berechnet.

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
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

