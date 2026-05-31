---
title: "Lizenz"
second_title: "Aspose.OCR für Java API-Referenz"
description: "Stellt Methoden zum Lizenzieren der Komponente bereit"
type: docs
weight: 21
url: /de/java/com.aspose.ocr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Stellt Methoden zur Lizenzierung der Komponente bereit.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [License()](#License) | Initialisiert eine neue Instanz dieser Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |

| [setLicense(File licenseFile)](#setLicense-java.io.File) | Lizenziert die Komponente. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream) | Lizenziert die Komponente. |
| [setLicense(String licenseFilePath)](#setLicense-java.lang.String) | Lizenziert die Komponente. |
| [isValid()](#isValid--) | Lizenz prüfen. |
### License() {#License}
```
public License()
```


Initialisiert eine neue Instanz dieser Klasse.


### setLicense(File licenseFile) {#setLicense-java.io.File}
```
public static void setLicense(File licenseFile)
```


Lizenziert die Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseFile | java.io.File | Darstellung des Dateipfads |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream}
```
public static void setLicense(InputStream stream)
```


Lizenziert die Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Ein Stream, der die Lizenz enthält. |

### setLicense(String licenseFilePath) {#setLicense-java.lang.String}
```
public static void setLicense(String licenseFilePath)
```


Lizenziert die Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseFilePath | java.lang.String | Kann ein voller oder kurzer Dateiname sein. Verwenden Sie eine leere Zeichenkette, um in den Evaluierungsmodus zu wechseln. |



### isValid() {#isValid--}
```
public static boolean isValid()
```


Lizenz prüfen.

**Returns:**
boolean – Boolescher Wert, ob die Lizenz gültig ist.
