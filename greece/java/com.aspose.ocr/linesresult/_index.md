---
title: "RecognitionResult.LinesResult"
second_title: "Αναφορά API του Aspose.OCR για Java"
description: 
type: docs
weight: 10
url: /el/java/com.aspose.ocr/recognitionresult.linesresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult.LinesResult
```
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [confidence](#confidence) | Η βαθμολογία εμπιστοσύνης που εκχωρείται στη γραμμή κειμένου που αναγνωρίστηκε, που αναπαρίσταται ως τιμή κινητής υποδιαστολής μεταξύ 0.0 και 1.0. |
| [line](#line) |  |
| [textInLine](#textInLine) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
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


Η βαθμολογία εμπιστοσύνης που εκχωρείται στη γραμμή κειμένου που αναγνωρίστηκε, που αναπαρίσταται ως τιμή κινητής υποδιαστολής μεταξύ 0.0 και 1.0. Ένα σκορ 1.0 υποδεικνύει το υψηλότερο επίπεδο βεβαιότητας αναγνώρισης.

Αυτή η τιμή ορίζεται πάντα σε 0 όταν χρησιμοποιείται προσωρινή άδεια. Η εμπιστοσύνη υπολογίζεται μόνο για τις ακόλουθες γλώσσες: ομάδα κινεζικών, αραβικά, χίντι, ευρωπαϊκά, κορεατικά, ιαπωνικά, τελουγκου, ταμίλ και κανάντα.

Η εμπιστοσύνη δεν υπολογίζεται για το ExtLatin ή για γλώσσες που περιέχουν διακριτικά σημεία.

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
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

