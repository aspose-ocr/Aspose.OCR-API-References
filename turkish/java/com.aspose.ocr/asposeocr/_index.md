---
title: "AsposeOCR"
second_title: "Aspose.OCR for Java API Referansı"
description: "Görüntülerden metin tanıma için ana sınıf"
type: docs
weight: 10
url: /tr/java/com.aspose.ocr/asposeocr/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public class AsposeOCR implements AutoCloseable
```

Görüntülerden metin tanıma için ana sınıf.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [AsposeOCR()](#AsposeOCR) | Genel yapıcı. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [DebugMode](#DebugMode) | Hata ayıklama modunu etkinleştirir. |
| [DebugModeSaveDirectory](#DebugModeSaveDirectory) | Hata ayıklama sonuçlarının kaydedileceği dizin. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CalculateSkew(OcrInput input)](#CalculateSkew-com.aspose.ocr.OcrInput) | Görüntülerin eğim açılarını hesaplar. |
| [CompareImageTexts(String fullPath1, String fullPath2)](#CompareImageTexts-java.lang.String-java.lang.String) | İki görüntünün aynı metni içerip içermediğini kontrol eder. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | İki görüntünün aynı metni içerip içermediğini kontrol eder. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | İki görüntünün aynı metni içerip içermediğini kontrol eder. |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Metni düzeltir (yanlış yazılmış kelimeleri değiştirir). |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String) | Metni düzeltir (yanlış yazılmış kelimeleri değiştirir). |
| [DetectDefects(OcrInput input, DefectType defectType)](#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType) | OCR doğruluğunu önemli ölçüde etkileyebilecek bir görüntünün sorunlu alanlarını otomatik olarak bulur. |
| [DetectDocumentLayout(OcrInput input)](#DetectDocumentLayout-com.aspose.ocr.OcrInput) | Görüntüyü analiz eder ve içindeki farklı içerik alanı türlerini belirler. |
| [DetectLanguages(OcrInput input)](#DetectLanguages-com.aspose.ocr.OcrInput) | Görüntü üzerindeki metni analiz eder ve hangi dillerde yazıldığını belirler. |
| [DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)](#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean) | Görüntülerdeki metin alanlarını algılar. |
| [DetectTables(OcrInput images)](#DetectTables-com.aspose.ocr.OcrInput) | Görüntülerdeki tablo bölgelerini algılar. |
| [ImageHasText(String fullPath, String text)](#ImageHasText-java.lang.String-java.lang.String) | Görüntünün sağlanan metin parçacığını büyük/küçük harf duyarsız aramayla içerip içermediğini kontrol eder. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Görüntünün sağlanan metin parçacığını büyük/küçük harf duyarsız aramayla içerip içermediğini kontrol eder. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Görüntünün sağlanan metin parçacığını içerip içermediğini kontrol eder. |
| [ImageHasText(String fullPath, Pattern regex)](#ImageHasText-java.lang.String-java.util.regex.Pattern) | Görüntü metninin sağlanan düzenli ifadeye uyup uymadığını kontrol eder. |
| [ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings) | Görüntü metninin sağlanan düzenli ifadeye uyup uymadığını kontrol eder. |
| [ImageTextDiff(String fullPath1, String fullPath2)](#ImageTextDiff-java.lang.String-java.lang.String) | İki görüntünün üzerindeki metinleri karşılaştırır ve benzerliklerini (0 ile 1 arasında) temsil eden bir sayı döndürür. |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | İki görüntünün üzerindeki metinleri karşılaştırır ve benzerliklerini (0 ile 1 arasında) temsil eden bir sayı döndürür. |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | İki görüntünün üzerindeki metinleri karşılaştırır ve benzerliklerini (0 ile 1 arasında) temsil eden bir sayı döndürür. |
| [Recognize(OcrInput input)](#Recognize-com.aspose.ocr.OcrInput) | Görüntüyü tanır ve GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 desteklerini belirleme yeteneğine sahiptir. |
| [Recognize(OcrInput input, RecognitionSettings settings)](#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings) | Görüntüyü tanır ve GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 desteklerini belirleme yeteneğine sahiptir. |
| [RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)](#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings) | Araç plakalarını tanır ve GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 desteklerini belirleme yeteneğine sahiptir. |
| [RecognizeCharacters(OcrInput input)](#RecognizeCharacters-com.aspose.ocr.OcrInput) | Görüntülerdeki sembolleri algılar. |
| [RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)](#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language) | Görüntülerdeki sembolleri algılar. |
| [RecognizeFast(OcrInput input)](#RecognizeFast-com.aspose.ocr.OcrInput) | İyi kalite görüntüdeki metni tanır. |
| [RecognizeFormula(OcrInput input, boolean detectAreas)](#RecognizeFormula-com.aspose.ocr.OcrInput-boolean) | Sağlanan giriş görüntülerinden matematiksel formülleri tanır. |
| [RecognizeHandwrittenText(OcrInput input)](#RecognizeHandwrittenText-com.aspose.ocr.OcrInput) | Görüntülerdeki el yazısı metni tanır. |
| [RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)](#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings) | Kimlik kartını tanır ve GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 desteklerini belirleme yeteneğine sahiptir. |
| [RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)](#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings) | Faturayı tanır ve GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 desteklerini belirleme yeteneğine sahiptir. |
| [RecognizePassport(OcrInput input, PassportRecognitionSettings settings)](#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings) | Belirleme yeteneğiyle pasaportu tanır. |
| [RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)](#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings) | Belirleme yeteneğiyle makbuzları tanır. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 destekler. |
| [RecognizeTables(OcrInput input, Language language)](#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language) | Tabloları ve yapıyı algılar, metin hücrelerini tanır. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | RecognitionResult nesnelerinin listesinden çok sayfalı belge almayı sağlar. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | RecognitionResult nesnelerinin listesinden çok sayfalı belge almayı sağlar. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | RecognitionResult nesnelerinin listesinden çok sayfalı belge almayı sağlar. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | RecognitionResult nesnelerinin listesinden çok sayfalı belge almayı sağlar. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage) | RecognitionResult nesnelerinin listesinden imla denetimi düzeltmesiyle çok sayfalı belge almayı sağlar. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | RecognitionResult nesnelerinin listesinden çok sayfalı belge almayı sağlar. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | RecognitionResult nesnelerinin listesinden çok sayfalı belge almayı sağlar. |
| [close()](#close) |  |

### AsposeOCR() {#AsposeOCR}
```
public AsposeOCR()
```


Genel yapıcı.

### DebugMode {#DebugMode}
```
public static boolean DebugMode
```


Hata ayıklama modunu etkinleştirir. Etkinleştirildiğinde, sistem ön işlenmiş görüntüler ve metin satırı dikdörtgenleri çizilmiş görüntüler gibi ara görüntü işleme sonuçlarını kaydeder.

### DebugModeSaveDirectory {#DebugModeSaveDirectory}
```
public static String DebugModeSaveDirectory
```


Hata ayıklama sonuçlarının kaydedileceği dizin. Ayarlanmazsa, varsayılan olarak geçerli çalışma dizini kullanılır.

### CalculateSkew(OcrInput input) {#CalculateSkew-com.aspose.ocr.OcrInput}
```
public ArrayList<SkewOutput> CalculateSkew(OcrInput input)
```


Görüntülerin eğim açılarını hesaplar. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 destekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Kaynaklarla birlikte kapsayıcı.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.SkewOutput> - Derece cinsinden eğim açıları ArrayList'i [SkewOutput](../../com.aspose.ocr.models/skewoutput/)
### CompareImageTexts(String fullPath1, String fullPath2) {#CompareImageTexts-java.lang.String-java.lang.String}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2)
```


İki görüntünün aynı metni içerip içermediğini kontrol eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullPath1 | java.lang.String | İlk görüntünün yolu. |
| fullPath2 | java.lang.String | İkinci görüntünün yolu. |

**Returns:**
boolean - Görüntüler aynı metne (%90 benzerlik) sahipse True.
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)
```


İki görüntünün aynı metni içerip içermediğini kontrol eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullPath1 | java.lang.String | İlk görüntünün yolu. |
| fullPath2 | java.lang.String | İkinci görüntünün yolu. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Tanıma ayarları. |

**Returns:**
boolean - Görüntüler aynı metne (%90 benzerlik) sahipse True.
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


İki görüntünün aynı metni içerip içermediğini kontrol eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullPath1 | java.lang.String | İlk görüntünün yolu. |
| fullPath2 | java.lang.String | İkinci görüntünün yolu. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Tanıma ayarları. |
| ignoreCase | boolean | True - büyük/küçük harf duyarsız bir arama anlamına gelir. |

**Returns:**
boolean - Görüntüler aynı metne (%90 benzerlik) sahipse True.
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)
```


Metni düzeltir (yanlış yazılmış kelimeleri değiştirir).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Düzeltme için metin. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Kullanılacak sözlük [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |

**Returns:**
java.lang.String - Değiştirilen kelimelerle metin.
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)
```


Metni düzeltir (yanlış yazılmış kelimeleri değiştirir).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Düzeltme için metin. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Kullanılacak sözlük [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |
| dictionaryPath | java.lang.String | Kullanıcı sözlüğünün (frekans sözlüğü) tam yolu. Sözlük dosya biçimi: UTF-8 kodlamalı düz metin dosyası. Kelime ve Kelime Frekansı virgülle ayrılır, kelime ilk sütunda, frekans ikinci sütunda bulunur. Her kelime-frekans çifti ayrı bir satırda yer alır. Bir satır, karakter dizisinin ardından satır beslemesi ("\\n"), satır dönüşü ("\\r") veya satır dönüşünün hemen ardından satır beslemesi ("\\r\\n") ile tanımlanır. Her kelime küçük harfle olmalıdır. |

**Returns:**
java.lang.String - Değiştirilen kelimelerle metin.
### DetectDefects(OcrInput input, DefectType defectType) {#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType}
```
public ArrayList<DefectOutput> DetectDefects(OcrInput input, DefectType defectType)
```


OCR doğruluğunu önemli ölçüde etkileyebilecek bir görüntünün sorunlu alanlarını otomatik olarak bulur. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 destekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Kaynaklarla birlikte kapsayıcı.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| defectType | [DefectType](../../com.aspose.ocr.models/defecttype/) | Tanımlanacak kusur türleri [DefectType](../../com.aspose.ocr.models/defecttype/). |

**Returns:**
java.util.ArrayList<com.aspose.ocr.DefectOutput> - Algılanan metin alanları veya satırları içeren [DefectOutput](../../com.aspose.ocr/defectoutput/) ArrayList'i.
### DetectDocumentLayout(OcrInput input) {#DetectDocumentLayout-com.aspose.ocr.OcrInput}
```
public ArrayList<LayoutOutput> DetectDocumentLayout(OcrInput input)
```


Görüntüyü analiz eder ve içindeki farklı içerik alanı türlerini belirler. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 desteklenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Kaynaklarla birlikte kapsayıcı.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LayoutOutput> - Algılanan içerik alanları. [LayoutOutput](../../com.aspose.ocr.models/layoutoutput/) ArrayList'i.
### DetectLanguages(OcrInput input) {#DetectLanguages-com.aspose.ocr.OcrInput}
```
public ArrayList<LanguageDetectionOutput> DetectLanguages(OcrInput input)
```


Görüntü üzerindeki metni analiz ederek hangi dillerde yazıldığını belirler. Bu, en uygun tanıma dilini seçmeye olanak tanır ve imla denetimi veya çeviri gibi sonraki metin işleme görevlerine yardımcı olur. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 desteklenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Kaynaklarla birlikte kapsayıcı.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LanguageDetectionOutput> - Olasılık sırasına göre sıralanmış en olası dillerin listesini döndürür. [LanguageDetectionOutput](../../com.aspose.ocr.models/languagedetectionoutput/) ArrayList'i.
### DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas) {#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean}
```
public ArrayList<RectangleOutput> DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)
```


Görüntülerde metin alanlarını algılar. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 desteklenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Kaynaklarla birlikte kapsayıcı.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| areasType | [AreasType](../../com.aspose.ocr.models/areastype/) | Hangi dikdörtgenlerin döndürüleceğini belirler - satır mı yoksa paragraf mı. |
| isDetectAreas | boolean | Otomatik metin alanı algılamayı etkinleştir. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - Algılanan metin alanları veya satırları içeren [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) ArrayList'i.
### DetectTables(OcrInput images) {#DetectTables-com.aspose.ocr.OcrInput}
```
public ArrayList<RectangleOutput> DetectTables(OcrInput images)
```


Görüntülerde tablo bölgelerini algılar. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 desteklenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Kaynaklarla birlikte kapsayıcı.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - Algılanan tablo alanlarını içeren [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) ArrayList'i.
### ImageHasText(String fullPath, String text) {#ImageHasText-java.lang.String-java.lang.String}
```
public boolean ImageHasText(String fullPath, String text)
```


Görüntünün sağlanan metin parçacığını büyük/küçük harf duyarsız aramayla içerip içermediğini kontrol eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullPath | java.lang.String | Görüntünün yolu. |
| text | java.lang.String | Görüntü üzerinde arama yapmak için metin parçacığı. |

**Returns:**
boolean - Görüntü metin parçacığı içeriyorsa True. False - görüntü metin parçacığı içermiyorsa.
### ImageHasText(String fullPath, String text, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings)
```


Görüntünün sağlanan metin parçacığını büyük/küçük harf duyarsız aramayla içerip içermediğini kontrol eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullPath | java.lang.String | Görüntünün yolu. |
| text | java.lang.String | Görüntü üzerinde arama yapmak için metin parçacığı. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Tanıma ayarları. |

**Returns:**
boolean - Görüntü metin parçacığı içeriyorsa True. False - görüntü metin parçacığı içermiyorsa.
### ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)
```


Görüntünün sağlanan metin parçacığını içerip içermediğini kontrol eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullPath | java.lang.String | Görüntünün yolu. |
| text | java.lang.String | Görüntü üzerinde arama yapmak için metin parçacığı. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Tanıma ayarları. |
| ignoreCase | boolean | True - büyük/küçük harf duyarsız bir arama anlamına gelir. |

**Returns:**
boolean - Görüntü metin parçacığı içeriyorsa True. False - görüntü metin parçacığı içermiyorsa.
### ImageHasText(String fullPath, Pattern regex) {#ImageHasText-java.lang.String-java.util.regex.Pattern}
```
public boolean ImageHasText(String fullPath, Pattern regex)
```


Görüntü metninin sağlanan düzenli ifadeye uyup uymadığını kontrol eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullPath | java.lang.String | Görüntünün yolu. |
| regex | java.util.regex.Pattern | Sağlanan desen ve seçeneklere sahip java.util.regex.Pattern nesnesi. |

**Returns:**
boolean - Görüntü metni sağlanan düzenli ifadeye eşleşiyorsa True.
### ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)
```


Görüntü metninin sağlanan düzenli ifadeye uyup uymadığını kontrol eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullPath | java.lang.String | Görüntünün yolu. |
| regex | java.util.regex.Pattern | Sağlanan desen ve seçeneklere sahip java.util.regex.Pattern nesnesi. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Tanıma ayarları. |

**Returns:**
boolean - Görüntü metni sağlanan düzenli ifadeye eşleşiyorsa True.
### ImageTextDiff(String fullPath1, String fullPath2) {#ImageTextDiff-java.lang.String-java.lang.String}
```
public float ImageTextDiff(String fullPath1, String fullPath2)
```


İki görüntünün üzerindeki metinleri karşılaştırır ve benzerliklerini (0 ile 1 arasında) temsil eden bir sayı döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullPath1 | java.lang.String | İlk görüntünün yolu. |
| fullPath2 | java.lang.String | İkinci görüntünün yolu. |

**Returns:**
float - 0, metinlerin tamamen farklı olduğunu; 1, metinlerin aynı olduğunu gösterir.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)
```


İki görüntünün üzerindeki metinleri karşılaştırır ve benzerliklerini (0 ile 1 arasında) temsil eden bir sayı döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullPath1 | java.lang.String | İlk görüntünün yolu. |
| fullPath2 | java.lang.String | İkinci görüntünün yolu. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Tanıma ayarları. |

**Returns:**
float - 0, metinlerin tamamen farklı olduğunu; 1, metinlerin aynı olduğunu gösterir.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


İki görüntünün üzerindeki metinleri karşılaştırır ve benzerliklerini (0 ile 1 arasında) temsil eden bir sayı döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullPath1 | java.lang.String | İlk görüntünün yolu. |
| fullPath2 | java.lang.String | İkinci görüntünün yolu. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Tanıma ayarları. |
| ignoreCase | boolean | True - büyük/küçük harf duyarsız bir arama anlamına gelir. |

**Returns:**
float - 0, metinlerin tamamen farklı olduğunu; 1, metinlerin aynı olduğunu gösterir.
### Recognize(OcrInput input) {#Recognize-com.aspose.ocr.OcrInput}
```
public OcrOutput Recognize(OcrInput input)
```


Görüntüyü tanır ve GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 desteklerini belirleme yeteneğine sahiptir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). örneği. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### Recognize(OcrInput input, RecognitionSettings settings) {#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings}
```
public OcrOutput Recognize(OcrInput input, RecognitionSettings settings)
```


Görüntüyü tanır ve GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 desteklerini belirleme yeteneğine sahiptir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). örneği. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings) {#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings}
```
public OcrOutput RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)
```


Araç plakalarını tanır ve GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 desteklerini belirleme yeteneğine sahiptir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). örneği. |
| settings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCharacters(OcrInput input) {#RecognizeCharacters-com.aspose.ocr.OcrInput}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input)
```


Görüntülerdeki sembolleri algılar. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 formatlarını destekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Kaynaklarla birlikte kapsayıcı.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - Her görüntü için algılanan sembol verileri içeren [Character](../../com.aspose.ocr.models/character/) ArrayList'i.
### RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language) {#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)
```


Görüntülerdeki sembolleri algılar. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 formatlarını destekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Kaynaklarla birlikte kapsayıcı.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | Alan tespiti için kullanılan sinir ağı türünü belirler. |
| language | [Language](../../com.aspose.ocr.models/language/) | OCR için kullanılan dil. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - Algılanan sembol verileri içeren [Character](../../com.aspose.ocr.models/character/) ArrayList'i.
### RecognizeFast(OcrInput input) {#RecognizeFast-com.aspose.ocr.OcrInput}
```
public ArrayList<String> RecognizeFast(OcrInput input)
```


İyi kalite görüntüdeki metni tanır. Otomatik görüntü eğimi düzeltmesi ve metin alanı tespiti kullanılmaz. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 formatlarını destekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/) örneği. |

**Returns:**
java.util.ArrayList<java.lang.String> - Tanınan metinleri içeren ArrayList.
### RecognizeFormula(OcrInput input, boolean detectAreas) {#RecognizeFormula-com.aspose.ocr.OcrInput-boolean}
```
public OcrOutput RecognizeFormula(OcrInput input, boolean detectAreas)
```


Sağlanan giriş görüntülerinden matematiksel formülleri tanır. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 formatlarını destekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). örneği. |
| detectAreas | boolean | True olarak ayarlanırsa, tanıma işleminden önce formül bölgelerini otomatik olarak algılar ve izole eder. False olarak ayarlanırsa, tüm görüntüyü bir formül olarak işler. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - OcrOutput list with images recognition results [OcrOutput](../../com.aspose.ocr/ocroutput/)
### RecognizeHandwrittenText(OcrInput input) {#RecognizeHandwrittenText-com.aspose.ocr.OcrInput}
```
public OcrOutput RecognizeHandwrittenText(OcrInput input)
```


Görüntülerde el yazısı metni tanır. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 formatlarını destekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). Kaynakları içeren kapsayıcı.. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings) {#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings}
```
public OcrOutput RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)
```


Kimlik kartını tanır ve GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 desteklerini belirleme yeteneğine sahiptir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). örneği. |
| settings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings) {#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings}
```
public OcrOutput RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)
```


Faturayı tanır ve GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 desteklerini belirleme yeteneğine sahiptir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). örneği. |
| settings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizePassport(OcrInput input, PassportRecognitionSettings settings) {#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings}
```
public OcrOutput RecognizePassport(OcrInput input, PassportRecognitionSettings settings)
```


Belirtilen özelliklerle pasaportu tanır. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 formatlarını destekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). örneği. |
| settings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings) {#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings}
```
public OcrOutput RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)
```


Belirleme yeteneğiyle makbuzları tanır. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 destekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). örneği. |
| settings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeTables(OcrInput input, Language language) {#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language}
```
public ArrayList<OCRTablePage> RecognizeTables(OcrInput input, Language language)
```


Tabloları ve yapıyı algılar, metin hücrelerini tanır. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, klasör, dizi, zip arşivi, URL, base64 formatlarını destekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). örneği. |
| language | [Language](../../com.aspose.ocr.models/language/) | Tanıma sırasında kullanılan alfabeyi belirler. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.OCRTablePage> - Tablolardaki tanınan metinleri içeren OCRTablePage liste nesneleri. [OCRTablePage](../../com.aspose.ocr.models/ocrtablepage/)
### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)
```


RecognitionResult nesnelerinin listesinden çok sayfalı belge almayı sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.OutputStream | Seçilen formatta tanıma sonucunu kaydetmek için OutputStream. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Belge formatı (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste of [RecognitionResult](../../com.aspose.ocr/recognitionresult/). nesneleri. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


RecognitionResult nesnelerinin listesinden çok sayfalı belge almayı sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.OutputStream | Seçilen formatta tanıma sonucunu kaydetmek için OutputStream. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Belge formatı (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste of [RecognitionResult](../../com.aspose.ocr/recognitionresult/). nesneleri. |
| embeddedFontPath | java.lang.String | İsteğe bağlı. Kullanıcı yazı tipine tam yol. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


RecognitionResult nesnelerinin listesinden çok sayfalı belge almayı sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.OutputStream | Seçilen formatta tanıma sonucunu kaydetmek için OutputStream. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Belge formatı (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste of [RecognitionResult](../../com.aspose.ocr/recognitionresult/). nesneleri. |
| embeddedFontPath | java.lang.String | İsteğe bağlı. Kullanıcı yazı tipine tam yol. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Arka plan görüntülerinin kalitesini düşürerek PDF dosya boyutunu azaltın. Varsayılan olarak, orijinal görüntü kalitesi korunur. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)
```


RecognitionResult nesnelerinin listesinden çok sayfalı belge almayı sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullFileName | java.lang.String | Seçilen formatta tanıma sonucunu kaydetmek için yol içeren dosya adı. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Belge formatı (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste of [RecognitionResult](../../com.aspose.ocr/recognitionresult/). nesneleri. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)
```


RecognitionResult nesnelerinin listesinden imla denetimi düzeltmesiyle çok sayfalı belge almayı sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullFileName | java.lang.String | Seçilen formatta tanıma sonucunu kaydetmek için yol içeren dosya adı. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Belge formatı (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste of [RecognitionResult](../../com.aspose.ocr/recognitionresult/). nesneleri. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) enum değeri. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


RecognitionResult nesnelerinin listesinden çok sayfalı belge almayı sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullFileName | java.lang.String | Seçilen formatta tanıma sonucunu kaydetmek için yol içeren dosya adı. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Belge formatı (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste of [RecognitionResult](../../com.aspose.ocr/recognitionresult/). nesneleri. |
| embeddedFontPath | java.lang.String | İsteğe bağlı. Kullanıcı yazı tipine tam yol. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


RecognitionResult nesnelerinin listesinden çok sayfalı belge almayı sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullFileName | java.lang.String | Seçilen formatta tanıma sonucunu kaydetmek için yol içeren dosya adı. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Belge formatı (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste of [RecognitionResult](../../com.aspose.ocr/recognitionresult/). nesneleri. |
| embeddedFontPath | java.lang.String | İsteğe bağlı. Kullanıcı yazı tipine tam yol. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Arka plan görüntülerinin kalitesini düşürerek PDF dosya boyutunu azaltın. Varsayılan olarak, orijinal görüntü kalitesi korunur. |

### close() {#close}
```
public void close()
```