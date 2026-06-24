---
title: "RecognitionResult.LinesResult"
second_title: "Aspose.OCR for Java API 参考"
description: 
type: docs
weight: 10
url: /zh/java/com.aspose.ocr/recognitionresult.linesresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult.LinesResult
```
## 字段

| 字段 | 描述 |
| --- | --- |
| [confidence](#confidence) | 分配给识别文本行的置信度分数，表示为 0.0 到 1.0 之间的浮点值。 |
| [line](#line) |  |
| [textInLine](#textInLine) |  |
## 方法

| 方法 | 描述 |
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


分配给识别文本行的置信度分数，表示为 0.0 到 1.0 之间的浮点值。得分为 1.0 表示最高的识别确定性。

使用临时许可证时，此值始终设置为 0。置信度仅对以下语言计算：中文语言组、阿拉伯语、印地语、欧洲语言、韩语、日语、泰卢固语、泰米尔语和卡纳达语。

对于 ExtLatin 或包含变音符号的语言不计算置信度。

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
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

