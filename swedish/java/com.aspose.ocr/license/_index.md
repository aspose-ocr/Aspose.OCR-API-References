---
title: "Licens"
second_title: "Aspose.OCR för Java API-referens"
description: "Tillhandahåller metoder för att licensiera komponenten"
type: docs
weight: 21
url: /sv/java/com.aspose.ocr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Tillhandahåller metoder för att licensiera komponenten.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [License()](#License) | Initierar en ny instans av denna klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |

| [setLicense(File licenseFile)](#setLicense-java.io.File) | Licensierar komponenten. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream) | Licensierar komponenten. |
| [setLicense(String licenseFilePath)](#setLicense-java.lang.String) | Licensierar komponenten. |
| [isValid()](#isValid--) | Kontrollera licens. |
### License() {#License}
```
public License()
```


Initierar en ny instans av denna klass.


### setLicense(File licenseFile) {#setLicense-java.io.File}
```
public static void setLicense(File licenseFile)
```


Licensierar komponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseFile | java.io.File | representation av filsökväg |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream}
```
public static void setLicense(InputStream stream)
```


Licensierar komponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | En ström som innehåller licensen. |

### setLicense(String licenseFilePath) {#setLicense-java.lang.String}
```
public static void setLicense(String licenseFilePath)
```


Licensierar komponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseFilePath | java.lang.String | Kan vara ett fullständigt eller kort filnamn. Använd en tom sträng för att växla till utvärderingsläge. |



### isValid() {#isValid--}
```
public static boolean isValid()
```


Kontrollera licens.

**Returns:**
boolean - Booleskt värde som anger om licensen är giltig.
