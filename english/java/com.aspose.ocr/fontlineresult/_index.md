---
title: FontLineResult
second_title: Aspose.OCR for Java API Reference
description: Detected font information for a recognized text line
type: docs
weight: 15
url: /java/com.aspose.ocr/fontlineresult/
---

**Inheritance:**
java.lang.Object
```
public final class FontLineResult
```

Detected font information for a recognized text line.
## Constructors

| Constructor | Description |
| --- | --- |
| [FontLineResult(int lineIndex, int sizePx, Double sizePtEstimate, String style, double styleConfidence, String font, double fontConfidence)](#FontLineResult-int-int-java.lang.Double-java.lang.String-double-java.lang.String-double) |  |
## Fields

| Field | Description |
| --- | --- |
| [font](#font) | Detected font family name. |
| [fontConfidence](#fontConfidence) | Confidence score for detected font family. |
| [lineIndex](#lineIndex) | Zero-based line index in the processed font batch. |
| [sizePtEstimate](#sizePtEstimate) | Estimated font size in points. |
| [sizePx](#sizePx) | Detected line height in pixels. |
| [style](#style) | Detected font style. |
| [styleConfidence](#styleConfidence) | Confidence score for detected style. |
## Methods

| Method | Description |
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
### FontLineResult(int lineIndex, int sizePx, Double sizePtEstimate, String style, double styleConfidence, String font, double fontConfidence) {#FontLineResult-int-int-java.lang.Double-java.lang.String-double-java.lang.String-double}
```
public FontLineResult(int lineIndex, int sizePx, Double sizePtEstimate, String style, double styleConfidence, String font, double fontConfidence)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lineIndex | int |  |
| sizePx | int |  |
| sizePtEstimate | java.lang.Double |  |
| style | java.lang.String |  |
| styleConfidence | double |  |
| font | java.lang.String |  |
| fontConfidence | double |  |

### font {#font}
```
public final String font
```


Detected font family name.

### fontConfidence {#fontConfidence}
```
public final double fontConfidence
```


Confidence score for detected font family.

### lineIndex {#lineIndex}
```
public final int lineIndex
```


Zero-based line index in the processed font batch.

### sizePtEstimate {#sizePtEstimate}
```
public final Double sizePtEstimate
```


Estimated font size in points.

### sizePx {#sizePx}
```
public final int sizePx
```


Detected line height in pixels.

### style {#style}
```
public final String style
```


Detected font style.

### styleConfidence {#styleConfidence}
```
public final double styleConfidence
```


Confidence score for detected style.

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

