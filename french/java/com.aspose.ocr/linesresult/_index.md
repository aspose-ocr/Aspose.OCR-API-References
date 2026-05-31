---
title: "RecognitionResult.LinesResult"
second_title: "Référence API d'Aspose.OCR pour Java"
description: 
type: docs
weight: 10
url: /fr/java/com.aspose.ocr/recognitionresult.linesresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult.LinesResult
```
## Champs

| Champ | Description |
| --- | --- |
| [confidence](#confidence) | Le score de confiance attribué à la ligne de texte reconnue, représenté par une valeur à virgule flottante entre 0.0 et 1.0. |
| [line](#line) |  |
| [textInLine](#textInLine) |  |
## Méthodes

| Méthode | Description |
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


Le score de confiance attribué à la ligne de texte reconnue, représenté par une valeur à virgule flottante entre 0.0 et 1.0. Un score de 1.0 indique le niveau le plus élevé de certitude de reconnaissance.

Cette valeur est toujours fixée à 0 lors de l'utilisation d'une licence temporaire. La confiance n'est calculée que pour les langues suivantes : groupe de langues chinoises, arabe, hindi, européennes, coréen, japonais, télougou, tamoul et kannada.

La confiance n'est pas calculée pour ExtLatin ou les langues contenant des signes diacritiques.

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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

