---
title: "RecognitionResult.LinesResult"
second_title: "Aspose.OCR for Java API Referansı"
description: 
type: docs
weight: 10
url: /tr/java/com.aspose.ocr/recognitionresult.linesresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult.LinesResult
```
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [confidence](#confidence) | Tanımlanan metin satırına atanan güven skoru, 0.0 ile 1.0 arasında bir kayan nokta değeri olarak temsil edilir. |
| [line](#line) |  |
| [textInLine](#textInLine) |  |
## Yöntemler

| Yöntem | Açıklama |
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


Tanımlanan metin satırına atanan güven skoru, 0.0 ile 1.0 arasında bir kayan nokta değeri olarak temsil edilir. 1.0 skoru, en yüksek tanıma kesinliği seviyesini gösterir.

Bu değer, geçici bir lisans kullanıldığında her zaman 0 olarak ayarlanır. Güven sadece aşağıdaki diller için hesaplanır: Çin dili grubu, Arapça, Hintçe, Avrupa dilleri, Korece, Japonca, Telugu, Tamil ve Kannada.

ExtLatin veya diakritik işaretler içeren diller için güven hesaplanmaz.

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
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

