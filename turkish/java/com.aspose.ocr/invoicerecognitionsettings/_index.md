---
title: "InvoiceRecognitionSettings"
second_title: "Aspose.OCR for Java API Referansı"
description: "Fatura tanıma ayarları, tanıma sürecini özelleştirmeye izin veren öğeler içerir."
type: docs
weight: 17
url: /tr/java/com.aspose.ocr/invoicerecognitionsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.ocr.ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/)
```
public class InvoiceRecognitionSettings extends ReceiptRecognitionSettings
```

Fatura tanıma ayarları, tanıma sürecini özelleştirmeye izin veren öğeler içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [InvoiceRecognitionSettings()](#InvoiceRecognitionSettings) | Varsayılan yapıcı: autoSkew'i true olarak ayarla. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | İzin verilen karakterler kümesi. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | İzin verilen karakterler kümesi. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Koyu/siyah arka plan üzerindeki beyaz metinli görüntüleri algılayın ve bunlar için otomatik olarak özel bir OCR algoritması seçin. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Tanıma sembolleri için kara listeyi ayarlar. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Metin tanıma için dil algılama seviyesini belirtir. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | İşleme için kullanılan iş parçacığı sayısını alır veya ayarlar. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Küçük yazı tipi tanıması için özel olarak ek algoritmalar kullanmanıza olanak tanır. |
### InvoiceRecognitionSettings() {#InvoiceRecognitionSettings}
```
public InvoiceRecognitionSettings()
```


Varsayılan yapıcı: autoSkew'i true olarak ayarla.



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
