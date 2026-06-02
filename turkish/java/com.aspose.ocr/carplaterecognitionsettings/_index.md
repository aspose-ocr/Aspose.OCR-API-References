---
title: "CarPlateRecognitionSettings"
second_title: "Aspose.OCR for Java API Referansı"
description: "Araç plaka tanıma ayarları, tanıma sürecini özelleştirmeye izin veren öğeler içerir."
type: docs
weight: 12
url: /tr/java/com.aspose.ocr/carplaterecognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class CarPlateRecognitionSettings
```

Araç plaka tanıma ayarları, tanıma sürecini özelleştirmeye izin veren öğeler içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CarPlateRecognitionSettings()](#CarPlateRecognitionSettings) | Varsayılan yapıcı: autoSkew'i true olarak ayarla. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType) | İzin verilen karakterler kümesi. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Koyu/siyah arka plan üzerindeki beyaz metinli görüntüleri algılayın ve bunlar için otomatik olarak özel bir OCR algoritması seçin. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Tanıma sembolleri için kara listeyi ayarlar. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.Language) |  |
### CarPlateRecognitionSettings() {#CarPlateRecognitionSettings}
```
public CarPlateRecognitionSettings()
```


Varsayılan yapıcı: autoSkew'i true olarak ayarla.





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


İzin verilen karakter kümesi. Tanıma sonucunda izin verilen karakter tipini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) | enum @see [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) değerini içerir. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Koyu/siyah arka plan üzerindeki beyaz metinli görüntüleri algılayın ve bunlar için otomatik olarak özel bir OCR algoritması seçin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| automaticColorInversion | boolean | boolean değer içerir - bir automaticColorInversion ayarlanmıştır. |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


Tanıma sembolleri için kara listeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| characters | java.lang.String | Tanımadan hariç tutulan karakterler. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr/language/) | OCR için kullanılan dili ayarlar. Varsayılan olarak çoklu dil (hiçbiri). |

