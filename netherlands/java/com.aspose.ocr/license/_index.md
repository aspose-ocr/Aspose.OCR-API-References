---
title: "Licentie"
second_title: "Aspose.OCR for Java API-referentie"
description: "Biedt methoden om het component te licentiëren"
type: docs
weight: 21
url: /nl/java/com.aspose.ocr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Biedt methoden om het component te licentiëren.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [License()](#License) | Initialiseert een nieuw exemplaar van deze klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |

| [setLicense(File licenseFile)](#setLicense-java.io.File) | Licentieert het component. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream) | Licentieert het component. |
| [setLicense(String licenseFilePath)](#setLicense-java.lang.String) | Licentieert het component. |
| [isValid()](#isValid--) | Controleer licentie. |
### License() {#License}
```
public License()
```


Initialiseert een nieuw exemplaar van deze klasse.


### setLicense(File licenseFile) {#setLicense-java.io.File}
```
public static void setLicense(File licenseFile)
```


Licentieert het component.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| licenseFile | java.io.File | representatie van het bestandspad |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream}
```
public static void setLicense(InputStream stream)
```


Licentieert het component.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Een stream die de licentie bevat. |

### setLicense(String licenseFilePath) {#setLicense-java.lang.String}
```
public static void setLicense(String licenseFilePath)
```


Licentieert het component.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| licenseFilePath | java.lang.String | Kan een volledige of korte bestandsnaam zijn. Gebruik een lege string om over te schakelen naar evaluatiemodus. |



### isValid() {#isValid--}
```
public static boolean isValid()
```


Controleer licentie.

**Returns:**
boolean - Booleaanse waarde licentie is geldig.
