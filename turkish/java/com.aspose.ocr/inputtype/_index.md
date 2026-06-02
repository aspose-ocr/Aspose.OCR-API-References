---
title: "InputType"
second_title: "Aspose.OCR for Java API Referansı"
description: "İşleme / tanıma için görüntü / belge türleri"
type: docs
weight: 38
url: /tr/java/com.aspose.ocr/inputtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum InputType extends Enum<InputType>
```

İşleme / tanıma için görüntü/ belge türleri.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Base64](#Base64) | Görüntüyü içeren base64 dizesi veya base64 içeriğine sahip .txt dosyasının yolu. |
| [Directory](#Directory) | Dizine yol. |
| [PDF](#PDF) | Dosyadan veya InputStream'den taranmış PDF belgesi. |
| [SingleImage](#SingleImage) | GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage desteklenir. |
| [TIFF](#TIFF) | Dosyadan veya InputStream'den çok sayfalı TIFF, TIF belgesi. |
| [URL](#URL) | Görüntüye bağlantı. |
| [Zip](#Zip) | ZIP arşivinin tam adı. |

### Base64 {#Base64}
```
public static final InputType Base64
```


Görüntüyü içeren base64 dizesi veya base64 içeriğine sahip .txt dosyasının yolu. GIF, PNG, JPEG, BMP, TIFF desteklenir.

### Directory {#Directory}
```
public static final InputType Directory
```


Dizine yol. İç içe arşivler ve klasörler desteklenmez. GIF, PNG, JPEG, BMP, TIFF desteklenir. Varsayılan işlenen görüntü sayısı tümüdür.

### PDF {#PDF}
```
public static final InputType PDF
```


Dosyadan veya InputStream'den taranmış PDF belgesi.

### SingleImage {#SingleImage}
```
public static final InputType SingleImage
```


GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage desteklenir.

### TIFF {#TIFF}
```
public static final InputType TIFF
```


Dosyadan veya InputStream'den çok sayfalı TIFF, TIF belgesi.

### URL {#URL}
```
public static final InputType URL
```


Görüntüye bağlantı. GIF, PNG, JPEG, BMP, TIFF desteklenir.

### Zip {#Zip}
```
public static final InputType Zip
```


ZIP arşivinin tam adı. İç içe arşivler ve klasörler desteklenmez. GIF, PNG, JPEG, BMP, TIFF, JFIF desteklenir. Varsayılan işlenen görüntü sayısı tümüdür.
