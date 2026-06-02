---
title: "RecognitionSettings"
second_title: "Aspose.OCR for Java API Referansı"
description: "Görüntü tanıma ayarları"
type: docs
weight: 27
url: /tr/java/com.aspose.ocr/recognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionSettings
```

Görüntü tanıma ayarları. Tanıma sürecini özelleştirmeye izin veren öğeler içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RecognitionSettings()](#RecognitionSettings) | Varsayılan yapıcı: recognitionAreas null, linesFiltration false, autoSkew false, recognizeSingleLine false olarak ayarlar. |
| [RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)](#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean) | Yapıcı, tüm seçenekleri ayarlamaya izin verir. |
| [RecognitionSettings(boolean recognizeSingleLine)](#RecognitionSettings-boolean) | Yapıcı, recognizeSingleLine ayarlamaya izin verir. |
| [RecognitionSettings(ReceiptRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings) |  |
| [RecognitionSettings(InvoiceRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings) |  |
| [RecognitionSettings(IDCardRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings) |  |
| [RecognitionSettings(PassportRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings) |  |
| [RecognitionSettings(CarPlateRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | İzin verilen karakterler kümesi. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | İzin verilen karakterler kümesi. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Koyu/siyah arka plan üzerindeki beyaz metinli görüntüleri algılayın ve bunlar için otomatik olarak özel bir OCR algoritması seçin. |
| [setDetectAreasMode(DetectAreasMode detectAreasMode)](#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode) | Alan tespiti için kullanılan sinir ağı türünü belirler. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Tanıma sembolleri için kara listeyi ayarlar. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Metin tanıma için dil algılama seviyesini belirtir. |
| [setLinesFiltration(boolean linesFiltration)](#setLinesFiltration-boolean) | Tablolardaki (çizgilerle çevrili bölgeler) metni tanımaya izin verir. |
| [setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)](#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle) | İşleme için metin alanları listesini ayarlar. |
| [setRecognizeSingleLine(boolean recognizeSingleLine)](#setRecognizeSingleLine-boolean) | Tek satır görüntü tanımını ayarlar. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | İşleme için kullanılan iş parçacığı sayısını alır veya ayarlar. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Küçük yazı tipi tanıması için özel olarak ek algoritmalar kullanmanıza olanak tanır. |
### RecognitionSettings() {#RecognitionSettings}
```
public RecognitionSettings()
```


Varsayılan yapıcı: recognitionAreas null, linesFiltration false, autoSkew false, recognizeSingleLine false olarak ayarlar.

### RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine) {#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean}
```
public RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)
```


Yapıcı, tüm seçenekleri ayarlamaya izin verir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Tanıma için dikdörtgenler. |
| recognizeSingleLine | boolean | Görüntü yalnızca bir satır içeriyorsa Doğru. |

### RecognitionSettings(boolean recognizeSingleLine) {#RecognitionSettings-boolean}
```
public RecognitionSettings(boolean recognizeSingleLine)
```


Yapıcı, recognizeSingleLine ayarlamaya izin verir. Bu durumda varsayılan değerler: detectAreas - false, autoSkew = false, recognitionAreas - null.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recognizeSingleLine | boolean | Görüntü yalnızca bir satır içeriyorsa Doğru. |

### RecognitionSettings(ReceiptRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings}
```
public RecognitionSettings(ReceiptRecognitionSettings recSettings)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recSettings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) |  |

### RecognitionSettings(InvoiceRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings}
```
public RecognitionSettings(InvoiceRecognitionSettings recSettings)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recSettings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) |  |

### RecognitionSettings(IDCardRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings}
```
public RecognitionSettings(IDCardRecognitionSettings recSettings)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recSettings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) |  |

### RecognitionSettings(PassportRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings}
```
public RecognitionSettings(PassportRecognitionSettings recSettings)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recSettings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) |  |

### RecognitionSettings(CarPlateRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings}
```
public RecognitionSettings(CarPlateRecognitionSettings recSettings)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recSettings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) |  |




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
| allowedCharacters | java.lang.String | karakter dizisi içerir. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Koyu/siyah arka plan üzerindeki beyaz metinli görüntüleri algılayın ve bunlar için otomatik olarak özel bir OCR algoritması seçin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| automaticColorInversion | boolean | boolean değer içerir - automaticColorInversion ayarlanmıştır. Varsayılan olarak Doğru. |

### setDetectAreasMode(DetectAreasMode detectAreasMode) {#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode}
```
public void setDetectAreasMode(DetectAreasMode detectAreasMode)
```


Alan tespiti için kullanılan sinir ağı türünü belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | enum @see [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) değerini içerir. |

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
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) |  |

### setLinesFiltration(boolean linesFiltration) {#setLinesFiltration-boolean}
```
public void setLinesFiltration(boolean linesFiltration)
```


Tablolardaki (çizgilerle çevrili bölgeler) metni tanımaya izin verir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| linesFiltration | boolean | false - performansı artırmaya izin verir ve tabloları algılamaz ve satırları kaldırır; aksi takdirde - true. Varsayılan olarak devre dışı (false). |

### setRecognitionAreas(ArrayList<Rectangle> recognitionAreas) {#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle}
```
public void setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)
```


İşleme için metin alanları listesini ayarlar. Daha doğru tanıma için metin içeren alanları manuel olarak belirlemeye izin verir. Özel alanlar [setDetectAreasMode(DetectAreasMode)](../../com.aspose.ocr/recognitionsettings/\#setDetectAreasMode-DetectAreasMode) (DetectAreasMode)\} NONE olmadan veya [PreprocessingFilter.AutoSkew()](../../com.aspose.ocr/preprocessingfilter/\#AutoSkew) (boolean)\} özellikleri yok sayılacaktır. DetectAreas ve AutoSkew'i devre dışı bırakır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Tanıma için dikdörtgenler. |

### setRecognizeSingleLine(boolean recognizeSingleLine) {#setRecognizeSingleLine-boolean}
```
public void setRecognizeSingleLine(boolean recognizeSingleLine)
```


Tek satır görüntü tanımasını ayarlar. Varsayılan olarak devre dışı (false). Satırlara bölme ile ilgili tüm işleme adımlarını devre dışı bırakır. Görüntünüz yalnızca bir satır içeriyorsa bu parametreyi true olarak ayarlayın. [setRecognitionAreas(ArrayList)](../../com.aspose.ocr/recognitionsettings/\#setRecognitionAreas-ArrayList) ayarlarını devre dışı bırakır, böylece tüm alan ayarları yok sayılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recognizeSingleLine | boolean | Tek satır görüntü için Doğru |

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
| upscaleSmallFont | boolean | boolean değer içerir - upscaleSmallFont ayarlanmıştır. |

### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String