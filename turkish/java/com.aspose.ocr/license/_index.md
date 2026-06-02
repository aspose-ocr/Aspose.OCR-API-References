---
title: "Lisans"
second_title: "Aspose.OCR for Java API Referansı"
description: "Bileşeni lisanslamak için yöntemler sağlar"
type: docs
weight: 21
url: /tr/java/com.aspose.ocr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Bileşeni lisanslamak için yöntemler sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [License()](#License) | Bu sınıfın yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |

| [setLicense(File licenseFile)](#setLicense-java.io.File) | Bileşeni lisanslar. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream) | Bileşeni lisanslar. |
| [setLicense(String licenseFilePath)](#setLicense-java.lang.String) | Bileşeni lisanslar. |
| [isValid()](#isValid--) | Lisansı kontrol edin. |
### License() {#License}
```
public License()
```


Bu sınıfın yeni bir örneğini başlatır.


### setLicense(File licenseFile) {#setLicense-java.io.File}
```
public static void setLicense(File licenseFile)
```


Bileşeni lisanslar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| licenseFile | java.io.File | dosya yol adının temsili |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream}
```
public static void setLicense(InputStream stream)
```


Bileşeni lisanslar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Lisansı içeren bir akış. |

### setLicense(String licenseFilePath) {#setLicense-java.lang.String}
```
public static void setLicense(String licenseFilePath)
```


Bileşeni lisanslar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| licenseFilePath | java.lang.String | Tam veya kısa bir dosya adı olabilir. Değerlendirme moduna geçmek için boş bir dize kullanın. |



### isValid() {#isValid--}
```
public static boolean isValid()
```


Lisansı kontrol edin.

**Returns:**
boolean - Lisansın geçerli olduğu Boolean değeri.
