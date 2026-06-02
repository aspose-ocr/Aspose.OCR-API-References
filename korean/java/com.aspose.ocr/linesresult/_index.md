---
title: "RecognitionResult.LinesResult"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: 
type: docs
weight: 10
url: /ko/java/com.aspose.ocr/recognitionresult.linesresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult.LinesResult
```
## 필드

| 필드 | 설명 |
| --- | --- |
| [confidence](#confidence) | 인식된 텍스트 라인에 할당된 신뢰도 점수로, 0.0에서 1.0 사이의 부동 소수점 값으로 표시됩니다. |
| [line](#line) |  |
| [textInLine](#textInLine) |  |
## 메서드

| 메서드 | 설명 |
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


인식된 텍스트 라인에 할당된 신뢰도 점수로, 0.0에서 1.0 사이의 부동 소수점 값으로 표시됩니다. 점수 1.0은 가장 높은 인식 확신 수준을 나타냅니다.

임시 라이선스를 사용할 때 이 값은 항상 0으로 설정됩니다. 신뢰도는 다음 언어에 대해서만 계산됩니다: 중국어 그룹, 아랍어, 힌디어, 유럽어, 한국어, 일본어, 텔루구어, 타밀어, 그리고 칸나다어.

ExtLatin 또는 구분 기호가 포함된 언어에 대해서는 신뢰도가 계산되지 않습니다.

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
| 매개변수 | 유형 | 설명 |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

