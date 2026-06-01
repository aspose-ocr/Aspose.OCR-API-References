---
title: "RecognitionResult.LinesResult"
second_title: "Referensi API Aspose.OCR untuk Java"
description: 
type: docs
weight: 10
url: /id/java/com.aspose.ocr/recognitionresult.linesresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult.LinesResult
```
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [confidence](#confidence) | Skor kepercayaan yang diberikan pada baris teks yang dikenali, direpresentasikan sebagai nilai floating-point antara 0.0 dan 1.0. |
| [line](#line) |  |
| [textInLine](#textInLine) |  |
## Metode

| Metode | Deskripsi |
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


Skor kepercayaan yang diberikan pada baris teks yang dikenali, direpresentasikan sebagai nilai floating-point antara 0.0 dan 1.0. Skor 1.0 menunjukkan tingkat kepastian pengenalan tertinggi.

Nilai ini selalu diatur ke 0 saat menggunakan lisensi sementara. Kepercayaan hanya dihitung untuk bahasa-bahasa berikut: kelompok bahasa Cina, Arab, Hindi, Eropa, Korea, Jepang, Telugu, Tamil, dan Kannada.

Kepercayaan tidak dihitung untuk ExtLatin atau bahasa yang mengandung tanda diakritik.

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
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

