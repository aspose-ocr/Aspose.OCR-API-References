---
title: "RecognitionResult.LinesResult"
second_title: "Riferimento API di Aspose.OCR per Java"
description: 
type: docs
weight: 10
url: /it/java/com.aspose.ocr/recognitionresult.linesresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult.LinesResult
```
## Campi

| Campo | Descrizione |
| --- | --- |
| [confidence](#confidence) | Il punteggio di confidenza assegnato alla riga di testo riconosciuta, rappresentato come valore a virgola mobile compreso tra 0,0 e 1,0. |
| [line](#line) |  |
| [textInLine](#textInLine) |  |
## Metodi

| Metodo | Descrizione |
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


Il punteggio di confidenza assegnato alla riga di testo riconosciuta, rappresentato come valore a virgola mobile compreso tra 0,0 e 1,0. Un punteggio di 1,0 indica il più alto livello di certezza del riconoscimento.

Questo valore è sempre impostato a 0 quando si utilizza una licenza temporanea. La confidenza è calcolata solo per le seguenti lingue: gruppo di lingue cinesi, arabo, hindi, europeo, coreano, giapponese, telugu, tamil e kannada.

La confidenza non è calcolata per ExtLatin o per le lingue che contengono segni diacritici.

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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

