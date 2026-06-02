---
title: "PreprocessingFilter"
second_title: "Aspose.OCR for Java API Referansı"
description: "Görüntü işleme komutları için temel sınıf"
type: docs
weight: 24
url: /tr/java/com.aspose.ocr/preprocessingfilter/
---

**Inheritance:**
java.lang.Object
```
public class PreprocessingFilter
```

Görüntü işleme komutları için temel sınıf.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PreprocessingFilter()](#PreprocessingFilter) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Empty](#Empty) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AutoDenoising()](#AutoDenoising) | Görüntüyü iyileştirmek için ek bir sinir ağı kullanımını etkinleştirir - gürültüyü azaltır. |
| [AutoDenoising(Rectangle area)](#AutoDenoising-java.awt.Rectangle) | Görüntünün bir bölümünü iyileştirmek için ek bir sinir ağı kullanımını etkinleştirir - gürültüyü azaltır. |
| [AutoDewarping()](#AutoDewarping) | Görüntüdeki geometrik bozulmaları otomatik olarak düzeltir. |
| [AutoSkew()](#AutoSkew) | Görüntünün otomatik eğim düzeltmesini etkinleştirir. |
| [AutoSkew(Rectangle area)](#AutoSkew-java.awt.Rectangle) | Görüntünün bir bölümünün otomatik eğim düzeltmesini etkinleştirir. |
| [Binarize()](#Binarize) | Bir görüntüyü siyah-beyaz görüntüye dönüştürür. |
| [Binarize(Rectangle area)](#Binarize-java.awt.Rectangle) | Görüntünün bir bölümünü siyah-beyaz görüntüye dönüştürür. |
| [BinarizeAndDilate()](#BinarizeAndDilate) | Genişletme, bir görüntüdeki nesnelerin sınırlarına piksel ekler. |
| [BinarizeAndDilate(Rectangle area)](#BinarizeAndDilate-java.awt.Rectangle) | Genişletme, görüntünün bir bölümündeki nesnelerin sınırlarına piksel ekler. |
| [ContrastCorrection()](#ContrastCorrection) | Kontrast düzeltme filtresi. |
| [ContrastCorrection(Rectangle area)](#ContrastCorrection-java.awt.Rectangle) | Görüntünün bir bölümü için kontrast düzeltme filtresi. |
| [Invert()](#Invert) | Bir belge görüntüsündeki renkleri otomatik olarak tersine çevirir. |
| [Invert(Rectangle area)](#Invert-java.awt.Rectangle) | Görüntünün bir bölümündeki renkleri otomatik olarak tersine çevirir. |
| [Median()](#Median) | Median filtresi, görüntünün her elemanını tarar ve her pikseli komşu piksellerin medyanı ile değiştirir. |
| [Median(Rectangle area)](#Median-java.awt.Rectangle) | Orta değer filtresi, görüntünün bölümündeki her öğeyi tarar ve her pikseli komşu piksellerin ortanca değeriyle değiştirir. |
| [Resize(int width, int height)](#Resize-int-int) | Görüntüyü yeniden ölçekle - Görüntü çözünürlüğünü artır veya azalt. |
| [Resize(int width, int height, InterpolationFilterType type)](#Resize-int-int-com.aspose.ocr.InterpolationFilterType) | Görüntüyü yeniden ölçekle - çözünürlüğü artır veya azalt. |
| [Rotate(float angle)](#Rotate-float) | Orijinal görüntüyü döndür. |
| [Rotate(float angle, Rectangle area)](#Rotate-float-java.awt.Rectangle) | Görüntünün bölümünü döndür. |
| [Scale(float ratio)](#Scale-float) | Görüntüyü yeniden ölçekle - Görüntü çözünürlüğünü artır veya azalt. |
| [Scale(float ratio, InterpolationFilterType type)](#Scale-float-com.aspose.ocr.InterpolationFilterType) | Görüntüyü yeniden ölçekle - Görüntü çözünürlüğünü artır veya azalt. |
| [Threshold(int value)](#Threshold-int) | Orijinal görüntünün piksel yoğunluğuna eşik değeri ayarlayarak ikili bir görüntü oluştur. |
| [Threshold(int value, Rectangle area)](#Threshold-int-java.awt.Rectangle) | Orijinal görüntünün bölümünün piksel yoğunluğuna eşik değeri ayarlayarak ikili bir görüntü bölümü oluştur. |
| [ToGrayscale()](#ToGrayscale) | Bir görüntüyü gri tonlamalı görüntüye dönüştürür. |
| [add(PreprocessingFilter filter)](#add-com.aspose.ocr.PreprocessingFilter) | Yeni filtreyi koleksiyona ekleyerek tüm işlemleri daha ileri çalıştır. |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### PreprocessingFilter() {#PreprocessingFilter}
```
public PreprocessingFilter()
```


### Empty {#Empty}
```
public static final PreprocessingFilter Empty
```


### AutoDenoising() {#AutoDenoising}
```
public static PreprocessingFilter AutoDenoising()
```


Görüntüyü iyileştirmek için ek bir sinir ağının kullanılmasını sağlar - gürültüyü azaltır. Tarama artefaktları, bozulma, lekeler, parlamalar, gradyanlar, yabancı öğeler içeren görüntüler için faydalıdır.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDenoising(Rectangle area) {#AutoDenoising-java.awt.Rectangle}
```
public static PreprocessingFilter AutoDenoising(Rectangle area)
```


Görüntünün bölümünü iyileştirmek için ek bir sinir ağının kullanılmasını sağlar - gürültüyü azaltır. Tarama artefaktları, bozulma, lekeler, parlamalar, gradyanlar, yabancı öğeler içeren görüntüler için faydalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alan | java.awt.Rectangle | Ön işleme için dikdörtgen. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDewarping() {#AutoDewarping}
```
public static PreprocessingFilter AutoDewarping()
```


Görüntüdeki geometrik bozulmaları otomatik olarak düzeltir. Son derece kaynak yoğun!

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDewarpingFilter object.
### AutoSkew() {#AutoSkew}
```
public static PreprocessingFilter AutoSkew()
```


Görüntünün otomatik eğim düzeltmesini etkinleştirir.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### AutoSkew(Rectangle area) {#AutoSkew-java.awt.Rectangle}
```
public static PreprocessingFilter AutoSkew(Rectangle area)
```


Görüntünün bir bölümünün otomatik eğim düzeltmesini etkinleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alan | java.awt.Rectangle | Ön işleme için dikdörtgen. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### Binarize() {#Binarize}
```
public static PreprocessingFilter Binarize()
```


Bir görüntüyü siyah-beyaz görüntüye dönüştürür. İkili görüntüler, piksellerinin yalnızca iki olası yoğunluk değerine sahip olduğu görüntülerdir. Normalde siyah ve beyaz olarak gösterilirler. Sayısal olarak, iki değer genellikle siyah için 0, beyaz için 255'tir. İkili görüntüler, bir görüntünün otomatik eşiklenmesiyle üretilir.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Binarize(Rectangle area) {#Binarize-java.awt.Rectangle}
```
public static PreprocessingFilter Binarize(Rectangle area)
```


Görüntünün bir bölümünü siyah-beyaz görüntüye dönüştürür. İkili görüntüler, piksellerinin yalnızca iki olası yoğunluk değerine sahip olduğu görüntülerdir. Normalde siyah ve beyaz olarak gösterilirler. Sayısal olarak, iki değer genellikle siyah için 0, beyaz için 255'tir. İkili görüntüler, bir görüntünün otomatik eşiklenmesiyle üretilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alan | java.awt.Rectangle | Ön işleme için dikdörtgen. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### BinarizeAndDilate() {#BinarizeAndDilate}
```
public static PreprocessingFilter BinarizeAndDilate()
```


Genişletme, bir görüntüdeki nesnelerin sınırlarına piksel ekler.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### BinarizeAndDilate(Rectangle area) {#BinarizeAndDilate-java.awt.Rectangle}
```
public static PreprocessingFilter BinarizeAndDilate(Rectangle area)
```


Genişletme, görüntünün bir bölümündeki nesnelerin sınırlarına piksel ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alan | java.awt.Rectangle | Ön işleme için dikdörtgen. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### ContrastCorrection() {#ContrastCorrection}
```
public static PreprocessingFilter ContrastCorrection()
```


Kontrast düzeltme filtresi.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### ContrastCorrection(Rectangle area) {#ContrastCorrection-java.awt.Rectangle}
```
public static PreprocessingFilter ContrastCorrection(Rectangle area)
```


Görüntünün bir bölümü için kontrast düzeltme filtresi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alan | java.awt.Rectangle | Ön işleme için dikdörtgen. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### Invert() {#Invert}
```
public static PreprocessingFilter Invert()
```


Bir belge görüntüsündeki renkleri otomatik olarak tersine çevirir.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Invert(Rectangle area) {#Invert-java.awt.Rectangle}
```
public static PreprocessingFilter Invert(Rectangle area)
```


Görüntünün bir bölümündeki renkleri otomatik olarak tersine çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alan | java.awt.Rectangle | Ön işleme için dikdörtgen. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Median() {#Median}
```
public static PreprocessingFilter Median()
```


Median filtresi, görüntünün her elemanını tarar ve her pikseli komşu piksellerin medyanı ile değiştirir.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Median(Rectangle area) {#Median-java.awt.Rectangle}
```
public static PreprocessingFilter Median(Rectangle area)
```


Orta değer filtresi, görüntünün bölümündeki her öğeyi tarar ve her pikseli komşu piksellerin ortanca değeriyle değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alan | java.awt.Rectangle | Ön işleme için dikdörtgen. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Resize(int width, int height) {#Resize-int-int}
```
public static PreprocessingFilter Resize(int width, int height)
```


Görüntüyü yeniden ölçekle - Görüntü çözünürlüğünü artır veya azalt. InterpolationFilterType = bilinear veya en yakın komşu @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Görüntünün yeni genişliği. |
| yükseklik | int | Görüntünün yeni yüksekliği. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Resize(int width, int height, InterpolationFilterType type) {#Resize-int-int-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Resize(int width, int height, InterpolationFilterType type)
```


Görüntüyü yeniden ölçekle - çözünürlüğü artır veya azalt.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Görüntünün yeni genişliği. |
| yükseklik | int | Görüntünün yeni yüksekliği. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Rotate(float angle) {#Rotate-float}
```
public static PreprocessingFilter Rotate(float angle)
```


Orijinal görüntüyü döndür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | float | Dönme açısı. Değer -360 ile 360 arasında. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Rotate(float angle, Rectangle area) {#Rotate-float-java.awt.Rectangle}
```
public static PreprocessingFilter Rotate(float angle, Rectangle area)
```


Görüntünün bölümünü döndür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | float | Dönme açısı. Değer -360 ile 360 arasında. |
| alan | java.awt.Rectangle | Ön işleme için dikdörtgen. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Scale(float ratio) {#Scale-float}
```
public static PreprocessingFilter Scale(float ratio)
```


Görüntüyü yeniden ölçekle - Görüntü çözünürlüğünü yükselt veya düşür. InterpolationFilterType varsayılan ikili ya da en yakın komşu @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oran | float | Ölçekleme faktörü. Küçültmek için önerilen değer 0.1 ile 1 arasındadır. Büyütmek için 1 ile 10 arasındadır. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Scale(float ratio, InterpolationFilterType type) {#Scale-float-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Scale(float ratio, InterpolationFilterType type)
```


Görüntüyü yeniden ölçekle - Görüntü çözünürlüğünü artır veya azalt.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oran | float | Ölçekleme faktörü. Küçültmek için önerilen değer 0.1 ile 1 arasındadır. Büyütmek için 1 ile 10 arasındadır. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Threshold(int value) {#Threshold-int}
```
public static PreprocessingFilter Threshold(int value)
```


Orijinal görüntünün piksel yoğunluğuna eşik değeri ayarlayarak ikili bir görüntü oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Azami değer. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Threshold(int value, Rectangle area) {#Threshold-int-java.awt.Rectangle}
```
public static PreprocessingFilter Threshold(int value, Rectangle area)
```


Orijinal görüntünün bölümünün piksel yoğunluğuna eşik değeri ayarlayarak ikili bir görüntü bölümü oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Azami değer. |
| alan | java.awt.Rectangle | Ön işleme için dikdörtgen. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### ToGrayscale() {#ToGrayscale}
```
public static PreprocessingFilter ToGrayscale()
```


Bir görüntüyü gri tonlamalı görüntüye dönüştürür. Gri tonlamalı görüntü, görüntüde 256 ışık seviyesine (0 ile 255) sahiptir.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - GrayscaleFilter object.
### add(PreprocessingFilter filter) {#add-com.aspose.ocr.PreprocessingFilter}
```
public void add(PreprocessingFilter filter)
```


Yeni filtreyi koleksiyona ekleyerek tüm işlemleri daha sonra çalıştırın. Koleksiyondaki tutarlılık önemlidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filter | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Filtre listesine eklenecek yeni işlem. |

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
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




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

