---
title: "RecognitionResult.LinesResult"
second_title: "Aspose.OCR जावा के लिए API संदर्भ"
description: 
type: docs
weight: 10
url: /hi/java/com.aspose.ocr/recognitionresult.linesresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult.LinesResult
```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [confidence](#confidence) | पहचानी गई टेक्स्ट लाइन को दिया गया विश्वसनीयता स्कोर, जो 0.0 से 1.0 के बीच एक फ्लोटिंग पॉइंट मान के रूप में दर्शाया गया है। |
| [line](#line) |  |
| [textInLine](#textInLine) |  |
## विधियाँ

| विधि | विवरण |
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


पहचानी गई टेक्स्ट लाइन को दिया गया विश्वसनीयता स्कोर, जो 0.0 से 1.0 के बीच एक फ्लोटिंग पॉइंट मान के रूप में दर्शाया गया है। 1.0 का स्कोर पहचान की सबसे उच्च स्तर की निश्चितता को दर्शाता है।

अस्थायी लाइसेंस का उपयोग करने पर यह मान हमेशा 0 पर सेट किया जाता है। विश्वसनीयता केवल निम्नलिखित भाषाओं के लिए गणना की जाती है: चीनी भाषा समूह, अरबी, हिंदी, यूरोपीय, कोरियन, जापानी, तेलुगु, तमिल, और कन्नड़।

ExtLatin या उन भाषाओं के लिए जिनमें उच्चारण चिह्न होते हैं, विश्वसनीयता की गणना नहीं की जाती।

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
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

