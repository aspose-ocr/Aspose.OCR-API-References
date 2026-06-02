---
title: "SpellCheckError"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: "추가 데이터와 함께 오타 단어를 나타내기"
type: docs
weight: 10
url: /ko/java/com.aspose.ocr.spellcheck/spellcheckerror/
---

**Inheritance:**
java.lang.Object
```
public class SpellCheckError
```

추가 데이터를 포함한 맞춤법 오류 단어를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SpellCheckError()](#SpellCheckError) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [length](#length) | 입력 텍스트에서 오타 단어의 길이. |
| [startPosition](#startPosition) | 입력 텍스트에서 단어의 위치. |
| [suggestedWords](#suggestedWords) | 제안된 올바른 철자를 포함하는 객체 목록 |
| [word](#word) | 오타가 발생한 단어. |
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
### SpellCheckError() {#SpellCheckError}
```
public SpellCheckError()
```


### length {#length}
```
public int length
```


입력 텍스트에서 오타 단어의 길이.

### startPosition {#startPosition}
```
public int startPosition
```


입력 텍스트에서 단어의 위치.

### suggestedWords {#suggestedWords}
```
public List<SpellCheck.SuggestedWord> suggestedWords
```


제안된 올바른 철자를 포함하는 객체 목록

### word {#word}
```
public String word
```


오타가 발생한 단어.

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

