---
title: "PassportRecognitionSettings"
second_title: "Aspose.OCR for Java API Referansı"
description: "Pasaport tanıma ayarları, tanıma sürecini özelleştirmeye izin veren öğeler içerir."
type: docs
weight: 23
url: /tr/java/com.aspose.ocr/passportrecognitionsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.ocr.ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/)
```
public class PassportRecognitionSettings extends ReceiptRecognitionSettings
```

Pasaport tanıma ayarları, tanıma sürecini özelleştirmeye izin veren öğeler içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PassportRecognitionSettings()](#PassportRecognitionSettings) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | İzin verilen karakterler kümesi. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | İzin verilen karakterler kümesi. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Koyu/siyah arka plan üzerindeki beyaz metinli görüntüleri algılayın ve bunlar için otomatik olarak özel bir OCR algoritması seçin. |
| [setCountry(Country country)](#setCountry-com.aspose.ocr.models.Country) | Pasaport tanıma şablonunu ayarlayın ve anahtar kelimeleri çıkarın. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Tanıma sembolleri için kara listeyi ayarlar. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Metin tanıma için dil algılama seviyesini belirtir. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | İşleme için kullanılan iş parçacığı sayısını alır veya ayarlar. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Küçük yazı tipi tanıması için özel olarak ek algoritmalar kullanmanıza olanak tanır. |
### PassportRecognitionSettings() {#PassportRecognitionSettings}
```
public PassportRecognitionSettings()
```





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


İzin verilen karakter kümesi. Tanıma sonucunda izin verilen karakter tipini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) | enum @see [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) değerini içerir. |

### setAllowedCharacters(String allowedCharacters) {#setAllowedCharacters-java.lang.String}
```
public void setAllowedCharacters(String allowedCharacters)
```


İzin verilen karakter kümesi. Tanıma sonucunda izin verilen karakter dizisini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| allowedCharacters | java.lang.String | karakter dizisini içerir. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Koyu/siyah arka plan üzerindeki beyaz metinli görüntüleri algılayın ve bunlar için otomatik olarak özel bir OCR algoritması seçin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| automaticColorInversion | boolean | boolean değer içerir - bir automaticColorInversion ayarlanmıştır. |

### setCountry(Country country) {#setCountry-com.aspose.ocr.models.Country}
```
public void setCountry(Country country)
```


Pasaport tanıma şablonunu ayarlayın ve anahtar kelimeleri çıkarın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| country | [Country](../../com.aspose.ocr.models/country/) | pasaport ülkesi. |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


Tanıma sembolleri için kara listeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| characters | java.lang.String | Tanımadan hariç tutulan karakterler. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.models.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr.models/language/) | OCR için kullanılan dili ayarlar. Varsayılan olarak çoklu dil (hiçbiri). |

### setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel) {#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel}
```
public void setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)
```


Metin tanıma için dil algılama seviyesini belirtir. Yalnızca seçilen dil Language.MULTILANGUAGE, Language.AUTO veya Language.UNIVERSAL olduğunda çalışır. Bu işlem zaman alıcıdır ve genel tanıma süresini önemli ölçüde yavaşlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) | seviyeyi ayarlamak için enum değeri (Paragraph, Word, Page). |

### setThreadsCount(int threadsCount) {#setThreadsCount-int}
```
public void setThreadsCount(int threadsCount)
```


İşleme için iş parçacığı sayısını alır veya ayarlar. Varsayılan olarak, 0, görüntünün işlemci sayınıza eşit iş parçacığıyla işleneceği anlamına gelir. ThreadsCount = 1, görüntünün ana iş parçacığında işleneceği anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadsCount | int | görüntü parçacıklarının paralel tanınması için oluşturulacak iş parçacığı sayısı. |

### setUpscaleSmallFont(boolean upscaleSmallFont) {#setUpscaleSmallFont-boolean}
```
public void setUpscaleSmallFont(boolean upscaleSmallFont)
```


Küçük yazı tipi tanıması için özel olarak ek algoritmalar kullanmanıza olanak tanır. Küçük boyutlu karakterlere sahip görüntüler için faydalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| upscaleSmallFont | boolean | boolean değer içerir - bir upscaleSmallFont ayarlanmıştır. |
