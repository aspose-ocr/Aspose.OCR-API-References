---
title: "OcrInput"
second_title: "Aspose.OCR for Java API Referansı"
description: "Görüntülerden metin tanıma için ana sınıf"
type: docs
weight: 20
url: /tr/java/com.aspose.ocr/ocrinput/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class OcrInput implements Iterable<ImageData>
```

Görüntülerden metin tanıma için ana sınıf.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OcrInput(InputType type, PreprocessingFilter filters)](#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter) | Konteyner oluşturmak ve görüntü / belge türünü ve sonraki işleme / tanıma için filtreleri ayarlamak için yapıcı. |
| [OcrInput(InputType type)](#OcrInput-com.aspose.ocr.InputType) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add(int[] pixels, int width, int height, int bitsPerPixel)](#add-int---int-int-int) | Çözülmüş görüntüyü tanıma / işleme listesine ekle. |
| [add(BufferedImage image)](#add-java.awt.image.BufferedImage) | Tanıma / işleme için görüntüyü içeren BufferedImage'i ekle. |
| [add(BufferedImage image, int startPage, int pagesCount)](#add-java.awt.image.BufferedImage-int-int) | Tanıma / işleme için çok sayfalı görüntüyü içeren BufferedImage'i ekle. |
| [add(InputStream stream)](#add-java.io.InputStream) | Tanıma / işleme için görüntüyü içeren InputStream'i ekle. |
| [add(InputStream stream, int startPage, int pagesCount)](#add-java.io.InputStream-int-int) | Tanıma / işleme için çok sayfalı görüntüyü içeren InputStream'i ekle. |
| [add(String fullPath)](#add-java.lang.String) | Tanıma / işleme için görüntüyü içeren yolu veya URI'yi ekle. |
| [add(String fullPath, int startPage, int pagesCount)](#add-java.lang.String-int-int) | Tanıma / işleme için çok sayfalı görüntüleri / belgeleri ekle. |
| [addBase64(String base64)](#addBase64-java.lang.String) | Tanıma / işleme için görüntüyü içeren base64 dizesini ekle. |
| [clear()](#clear) | İşleme / tanıma için öğe sayısını 0 olarak ayarla. |
| [clearFilters()](#clearFilters) | Tüm filtreleri kaldır. |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [get(int index)](#get-int) | İşlenen / tanınan görüntü hakkında bilgi döndürür. |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [iterator()](#iterator) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [replaceFilters(PreprocessingFilter filters)](#replaceFilters-com.aspose.ocr.PreprocessingFilter) | Eski filtreleri kaldır ve yenilerini ayarla. |
| [size()](#size) | İşleme / tanıma için öğe sayısı. |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OcrInput(InputType type, PreprocessingFilter filters) {#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter}
```
public OcrInput(InputType type, PreprocessingFilter filters)
```


Konteyner oluşturmak ve görüntü / belge türünü ve sonraki işleme / tanıma için filtreleri ayarlamak için yapıcı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) | Konteynere eklenecek görüntü/döküman türünü ayarla. |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | İşleme filtrelerini ayarla; bunlar sonraki işleme veya tanıma uygulanacaktır. |

### OcrInput(InputType type) {#OcrInput-com.aspose.ocr.InputType}
```
public OcrInput(InputType type)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) |  |

### add(int[] pixels, int width, int height, int bitsPerPixel) {#add-int---int-int-int}
```
public void add(int[] pixels, int width, int height, int bitsPerPixel)
```


Çözülmüş görüntüyü tanıma / işleme listesine ekle. Görüntünün türü, yapıcıda belirtilen türe (SingleImage) uygun olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| piksel | int[] | Piksel değerleri 32-bit tamsayı (rgb) olarak temsil edilir. |
| genişlik | int | Görüntü genişliği. |
| yükseklik | int | Görüntü yüksekliği. |
| bitsPerPixel | int | 1-32 bit destekler. |

### add(BufferedImage image) {#add-java.awt.image.BufferedImage}
```
public void add(BufferedImage image)
```


Tanıma / işleme için görüntüyü içeren BufferedImage'i ekle. Görüntünün türü, yapıcıda belirtilen türe uygun olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | java.awt.image.BufferedImage | Görüntü veya belgeyi içeren BufferedImage. |

### add(BufferedImage image, int startPage, int pagesCount) {#add-java.awt.image.BufferedImage-int-int}
```
public void add(BufferedImage image, int startPage, int pagesCount)
```


Tanıma / işleme için çok sayfalı görüntüyü içeren BufferedImage'i ekle. Görüntünün türü, yapıcıda belirtilen türe uygun olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | java.awt.image.BufferedImage | Çok sayfalı belgeyi içeren BufferedImage. |
| startPage | int | İşleme / tanıma için ilk sayfa/görüntü. Belgeler için kullanın. |
| pagesCount | int | İşleme / tanıma için toplam sayfa/görüntü sayısı. Belgeler için kullanın. Varsayılan = tümü. |

### add(InputStream stream) {#add-java.io.InputStream}
```
public void add(InputStream stream)
```


Tanıma / işleme için görüntüyü içeren InputStream'i ekle. Görüntünün türü, yapıcıda belirtilen türe uygun olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Görüntüyü veya belgeyi içeren InputStream. |

### add(InputStream stream, int startPage, int pagesCount) {#add-java.io.InputStream-int-int}
```
public void add(InputStream stream, int startPage, int pagesCount)
```


Tanıma / işleme için çok sayfalı görüntüyü içeren InputStream'i ekleyin. Görüntünün türü, yapıcıda belirtilen türe karşılık gelmelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Çok sayfalı belgeyi içeren InputStream. |
| startPage | int | İşleme / tanıma için ilk sayfa/görüntü. Belgeler için kullanın. |
| pagesCount | int | İşleme / tanıma için toplam sayfa/görüntü sayısı. Belgeler için kullanın. Varsayılan = tümü. |

### add(String fullPath) {#add-java.lang.String}
```
public void add(String fullPath)
```


Tanıma / işleme için görüntüyü içeren yolu veya URI'yi ekleyin. Görüntünün türü, yapıcıda belirtilen türe karşılık gelmelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullPath | java.lang.String | Görüntü / belge / klasör / arşiv yolu. |

### add(String fullPath, int startPage, int pagesCount) {#add-java.lang.String-int-int}
```
public void add(String fullPath, int startPage, int pagesCount)
```


Tanıma / işleme için çok sayfalı görüntüleri / belgeleri ekleyin. Görüntünün türü, yapıcıda belirtilen türe karşılık gelmelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullPath | java.lang.String | Görüntü / belge / klasör / arşiv yolu. |
| startPage | int | İşleme / tanıma için ilk sayfa/görüntü. Belgeler, zip, klasörler için kullanın. |
| pagesCount | int | İşleme / tanıma için toplam sayfa/görüntü sayısı. Belgeler, zip, klasörler için kullanın. Varsayılan = tümü. |

### addBase64(String base64) {#addBase64-java.lang.String}
```
public void addBase64(String base64)
```


Tanıma / işleme için görüntüyü içeren base64 dizesini ekleyin. Görüntünün türü, yapıcıda belirtilen türe karşılık gelmelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| base64 | java.lang.String | Tek görüntülü Base64 dizesi. |

### clear() {#clear}
```
public void clear()
```


İşleme / tanıma için öğe sayısını 0 olarak ayarlayın. Koleksiyonu temizleyin.

### clearFilters() {#clearFilters}
```
public void clearFilters()
```


Tüm filtreleri kaldır.

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int}
```
public ImageData get(int index)
```


İşlenen / tanınan görüntü hakkında bilgi döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Listedeki görüntünün konumu. |

**Returns:**
[ImageData](../../com.aspose.ocr/imagedata/) - The object of @see [ImageData](../../com.aspose.ocr/imagedata/)
### getClass() {#getClass}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator}
```
public Iterator<ImageData> iterator()
```




**Returns:**
java.util.Iterator<com.aspose.ocr.ImageData>
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




### replaceFilters(PreprocessingFilter filters) {#replaceFilters-com.aspose.ocr.PreprocessingFilter}
```
public void replaceFilters(PreprocessingFilter filters)
```


Eski filtreleri kaldır ve yenilerini ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | İşleme filtreleri, sonraki işleme veya tanıma için uygulanacaktır. |

### size() {#size}
```
public int size()
```


İşleme / tanıma için öğe sayısı.

**Returns:**
int - Öğelerin sayısı.
### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait}
```
public final void wait()
```




### wait(long arg0) {#wait-long}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

