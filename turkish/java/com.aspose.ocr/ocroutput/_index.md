---
title: "OcrOutput"
second_title: "Aspose.OCR for Java API Referansı"
description: 
type: docs
weight: 21
url: /tr/java/com.aspose.ocr/ocroutput/
---

**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList
```
public class OcrOutput extends ArrayList<RecognitionResult>
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OcrOutput()](#OcrOutput) | OcrOutput sınıfının boş bir koleksiyonla yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |

| [getTableData()](#getTableData) | Tüm tanınan sayfalardan çıkarılan yapılandırılmış tablo verilerini döndürür. |
| [save(OutputStream stream)](#save-java.io.OutputStream) | Tüm tanıma sonuçlarını belirtilen formatta bir bellek akışına kaydeder. |
| [save(OutputStream stream, Format saveFormat)](#save-java.io.OutputStream-com.aspose.ocr.models.Format) | Tüm tanıma sonuçlarını belirtilen formatta bir bellek akışına kaydeder. |
| [save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Tüm tanıma sonuçlarını belirtilen formatta bir bellek akışına kaydeder. |
| [save(String fullFileName)](#save-java.lang.String) | Tüm tanıma sonuçlarını bir dosyaya kaydedin. |
| [save(String fullFileName, Format saveFormat)](#save-java.lang.String-com.aspose.ocr.models.Format) | Tüm tanıma sonuçlarını bir dosyaya kaydedin. |
| [save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Tüm tanıma sonuçlarını bir dosyaya kaydedin. |
| [savePdf(OutputStream stream)](#savePdf-java.io.OutputStream) | Tüm tanıma sonuçlarını bellekteki aranabilir PDF belgesine kaydedin, orijinal görüntüleri arka plan olarak gömerek. |
| [savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Tüm tanıma sonuçlarını bellekteki aranabilir PDF belgesine kaydedin, orijinal görüntüleri arka plan olarak gömerek. |
| [savePdf(String fullFileName)](#savePdf-java.lang.String) | Tüm tanıma sonuçlarını aranabilir bir PDF dosyasına kaydedin, orijinal görüntüler arka plan olarak ayarlanmış şekilde. |
| [savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Tüm tanıma sonuçlarını aranabilir bir PDF dosyasına kaydedin, orijinal görüntüler arka plan olarak ayarlanmış şekilde. |

### getTableData() {#getTableData}
```
public OCRTable getTableData()
```


Tüm tanınan sayfalardan çıkarılan yapılandırılmış tablo verilerini döndürür.

Her sayfa satırlar içerir ve her satır tanınan metin ve isteğe bağlı konum bilgisi içeren hücreler içerir.

**Returns:**
[OCRTable](../../com.aspose.ocr.models/ocrtable/) - an [OCRTable](../../com.aspose.ocr.models/ocrtable/) structure representing all tables in the document


### save(OutputStream stream) {#save-java.io.OutputStream}
```
public void save(OutputStream stream)
```


Tüm tanıma sonuçlarını belirtilen formatta bir bellek akışına kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.OutputStream | Seçilen formatta tanıma sonucunu kaydetmek için OutputStream. |

### save(OutputStream stream, Format saveFormat) {#save-java.io.OutputStream-com.aspose.ocr.models.Format}
```
public void save(OutputStream stream, Format saveFormat)
```


Tüm tanıma sonuçlarını belirtilen formatta bir bellek akışına kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.OutputStream | Seçilen formatta tanıma sonucunu kaydetmek için OutputStream. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Belge formatı (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Tüm tanıma sonuçlarını belirtilen formatta bir bellek akışına kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.OutputStream | Seçilen formatta tanıma sonucunu kaydetmek için OutputStream. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Belge formatı (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | İsteğe bağlı. Kullanıcı yazı tipinin tam yolu. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Arka plan görüntülerinin kalitesini düşürerek PDF dosya boyutunu azaltın. Varsayılan olarak, orijinal görüntü kalitesi korunur. |

### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Tüm tanıma sonuçlarını bir dosyaya kaydedin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullFileName | java.lang.String | Seçilen formatta tanıma sonucunu kaydetmek için yol içeren dosya adı. |

### save(String fullFileName, Format saveFormat) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format saveFormat)
```


Tüm tanıma sonuçlarını bir dosyaya kaydedin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullFileName | java.lang.String | Seçilen formatta tanıma sonucunu kaydetmek için yol içeren dosya adı. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Belge formatı (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Tüm tanıma sonuçlarını bir dosyaya kaydedin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullFileName | java.lang.String | Seçilen formatta tanıma sonucunu kaydetmek için yol içeren dosya adı. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Belge formatı (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | İsteğe bağlı. Kullanıcı yazı tipinin tam yolu. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Arka plan görüntülerinin kalitesini düşürerek PDF dosya boyutunu azaltın. Varsayılan olarak, orijinal görüntü kalitesi korunur. |

### savePdf(OutputStream stream) {#savePdf-java.io.OutputStream}
```
public void savePdf(OutputStream stream)
```


Tüm tanıma sonuçlarını bellekteki aranabilir PDF belgesine kaydedin, orijinal görüntüleri arka plan olarak gömerek.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.OutputStream | Seçilen formatta tanıma sonucunu kaydetmek için OutputStream. |

### savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Tüm tanıma sonuçlarını bellekteki aranabilir PDF belgesine kaydedin, orijinal görüntüleri arka plan olarak gömerek.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.OutputStream | Seçilen formatta tanıma sonucunu kaydetmek için OutputStream. |
| embeddedFontPath | java.lang.String | İsteğe bağlı. Kullanıcı yazı tipinin tam yolu. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Arka plan görüntülerinin kalitesini düşürerek PDF dosya boyutunu azaltın. Varsayılan olarak, orijinal görüntü kalitesi korunur. |

### savePdf(String fullFileName) {#savePdf-java.lang.String}
```
public void savePdf(String fullFileName)
```


Tüm tanıma sonuçlarını aranabilir bir PDF dosyasına kaydedin, orijinal görüntüler arka plan olarak ayarlanmış şekilde.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullFileName | java.lang.String | Seçilen formatta tanıma sonucunu kaydetmek için yol içeren dosya adı. |

### savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Tüm tanıma sonuçlarını aranabilir bir PDF dosyasına kaydedin, orijinal görüntüler arka plan olarak ayarlanmış şekilde.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullFileName | java.lang.String | Seçilen formatta tanıma sonucunu kaydetmek için yol içeren dosya adı. |
| embeddedFontPath | java.lang.String | İsteğe bağlı. Kullanıcı yazı tipinin tam yolu. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Arka plan görüntülerinin kalitesini düşürerek PDF dosya boyutunu azaltın. Varsayılan olarak, orijinal görüntü kalitesi korunur. |

### size() {#size}
```
public int size()
```




**Returns:**
int
