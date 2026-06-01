---
title: "RecognitionResult.LinesResult"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: 
type: docs
weight: 10
url: /ja/java/com.aspose.ocr/recognitionresult.linesresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult.LinesResult
```
## フィールド

| フィールド | 説明 |
| --- | --- |
| [confidence](#confidence) | 認識されたテキスト行に割り当てられる信頼度スコアで、0.0 から 1.0 の浮動小数点値で表されます。 |
| [line](#line) |  |
| [textInLine](#textInLine) |  |
## メソッド

| メソッド | 説明 |
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


認識されたテキスト行に割り当てられる信頼度スコアで、0.0 から 1.0 の浮動小数点値で表されます。スコアが 1.0 の場合、認識確度が最も高いことを示します。

一時ライセンスを使用する場合、この値は常に 0 に設定されます。信頼度は次の言語に対してのみ計算されます：中国語グループ、アラビア語、ヒンディー語、ヨーロッパ言語、韓国語、日本語、テルグ語、タミル語、カンナダ語。

ExtLatin またはアクセント記号を含む言語については、信頼度は計算されません。

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
| パラメータ | タイプ | 説明 |
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
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

