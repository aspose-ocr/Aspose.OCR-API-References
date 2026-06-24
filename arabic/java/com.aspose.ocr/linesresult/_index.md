---
title: "RecognitionResult.LinesResult"
second_title: "مرجع Aspose.OCR لـ Java API"
description: 
type: docs
weight: 10
url: /ar/java/com.aspose.ocr/recognitionresult.linesresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult.LinesResult
```
## الحقول

| الحقل | الوصف |
| --- | --- |
| [confidence](#confidence) | درجة الثقة المخصصة لسطر النص المعترف به، ممثلة كقيمة عائمة بين 0.0 و 1.0. |
| [line](#line) |  |
| [textInLine](#textInLine) |  |
## الدوال

| الدالة | الوصف |
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


درجة الثقة المخصصة لسطر النص المعترف به، ممثلة كقيمة عائمة بين 0.0 و 1.0. تشير درجة 1.0 إلى أعلى مستوى من اليقين في التعرف.

يتم دائمًا تعيين هذه القيمة إلى 0 عند استخدام ترخيص مؤقت. تُحسب الثقة فقط للغات التالية: مجموعة اللغة الصينية، العربية، الهندية، الأوروبية، الكورية، اليابانية، التيلجو، التاميلية، والكانادا.

لا تُحسب الثقة للغة ExtLatin أو اللغات التي تحتوي على علامات تشكيل.

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
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

