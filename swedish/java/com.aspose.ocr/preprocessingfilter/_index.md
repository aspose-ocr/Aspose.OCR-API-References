---
title: "PreprocessingFilter"
second_title: "Aspose.OCR för Java API-referens"
description: "Basklass för bildbehandlingskommandon"
type: docs
weight: 24
url: /sv/java/com.aspose.ocr/preprocessingfilter/
---

**Inheritance:**
java.lang.Object
```
public class PreprocessingFilter
```

Basisklass för bildbehandlingskommandon.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PreprocessingFilter()](#PreprocessingFilter) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Empty](#Empty) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AutoDenoising()](#AutoDenoising) | Aktiverar användning av ett extra neuralt nätverk för att förbättra bilden – minska brus. |
| [AutoDenoising(Rectangle area)](#AutoDenoising-java.awt.Rectangle) | Aktiverar användning av ett extra neuralt nätverk för att förbättra bilddelen – minska brus. |
| [AutoDewarping()](#AutoDewarping) | Korrigerar automatiskt geometriska förvrängningar i bilden. |
| [AutoSkew()](#AutoSkew) | Aktiverar automatisk korrigering av bildskevhet. |
| [AutoSkew(Rectangle area)](#AutoSkew-java.awt.Rectangle) | Aktiverar automatisk korrigering av bilddelens skevhet. |
| [Binarize()](#Binarize) | Konverterar en bild till svart‑vit bild. |
| [Binarize(Rectangle area)](#Binarize-java.awt.Rectangle) | Konverterar en del av bilden till svart‑vit bild. |
| [BinarizeAndDilate()](#BinarizeAndDilate) | Dilatering lägger till pixlar på gränserna av objekt i en bild. |
| [BinarizeAndDilate(Rectangle area)](#BinarizeAndDilate-java.awt.Rectangle) | Dilatering lägger till pixlar på gränserna av objekt i en del av bilden. |
| [ContrastCorrection()](#ContrastCorrection) | Kontrastkorrigeringsfilter. |
| [ContrastCorrection(Rectangle area)](#ContrastCorrection-java.awt.Rectangle) | Kontrastkorrigeringsfilter för bilddelen. |
| [Invert()](#Invert) | Inverterar automatiskt färger i en dokumentbild. |
| [Invert(Rectangle area)](#Invert-java.awt.Rectangle) | Inverterar automatiskt färger i en del av bilden. |
| [Median()](#Median) | Medianfiltret går igenom varje element i bilden och ersätter varje pixel med medianen av dess närliggande pixlar. |
| [Median(Rectangle area)](#Median-java.awt.Rectangle) | Medianfiltret går igenom varje element i bilddelen och ersätter varje pixel med medianen av dess närliggande pixlar. |
| [Resize(int width, int height)](#Resize-int-int) | Skala om bild - Höj eller sänk bildens upplösning. |
| [Resize(int width, int height, InterpolationFilterType type)](#Resize-int-int-com.aspose.ocr.InterpolationFilterType) | Skala om bild - höj eller sänk bildens upplösning. |
| [Rotate(float angle)](#Rotate-float) | Rotera originalbilden. |
| [Rotate(float angle, Rectangle area)](#Rotate-float-java.awt.Rectangle) | Rotera bilddelen. |
| [Scale(float ratio)](#Scale-float) | Skala om bild - Höj eller sänk bildens upplösning. |
| [Scale(float ratio, InterpolationFilterType type)](#Scale-float-com.aspose.ocr.InterpolationFilterType) | Skala om bild - Höj eller sänk bildens upplösning. |
| [Threshold(int value)](#Threshold-int) | Skapa en binär bild baserad på att sätta ett tröskelvärde på pixelintensiteten i originalbilden. |
| [Threshold(int value, Rectangle area)](#Threshold-int-java.awt.Rectangle) | Skapa en binär bilddel baserad på att sätta ett tröskelvärde på pixelintensiteten i originalbilddelen. |
| [ToGrayscale()](#ToGrayscale) | Konverterar en bild till en gråskalebild. |
| [add(PreprocessingFilter filter)](#add-com.aspose.ocr.PreprocessingFilter) | Lägg till det nya filtret i samlingen för att vidare köra alla operationer. |
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


Möjliggör användning av ett extra neuralt nätverk för att förbättra bilden – minska brus. Användbart för bilder med skanningsartefakter, förvrängning, fläckar, bländningar, gradienter, främmande element.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDenoising(Rectangle area) {#AutoDenoising-java.awt.Rectangle}
```
public static PreprocessingFilter AutoDenoising(Rectangle area)
```


Möjliggör användning av ett extra neuralt nätverk för att förbättra bilddelen – minska brus. Användbart för bilder med skanningsartefakter, förvrängning, fläckar, bländningar, gradienter, främmande element.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| område | java.awt.Rectangle | Rektangel att förbehandla. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDewarping() {#AutoDewarping}
```
public static PreprocessingFilter AutoDewarping()
```


Korrigerar automatiskt geometriska förvrängningar i bilden. Extremt resurskrävande!

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDewarpingFilter object.
### AutoSkew() {#AutoSkew}
```
public static PreprocessingFilter AutoSkew()
```


Aktiverar automatisk korrigering av bildskevhet.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### AutoSkew(Rectangle area) {#AutoSkew-java.awt.Rectangle}
```
public static PreprocessingFilter AutoSkew(Rectangle area)
```


Aktiverar automatisk korrigering av bilddelens skevhet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| område | java.awt.Rectangle | Rektangel att förbehandla. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### Binarize() {#Binarize}
```
public static PreprocessingFilter Binarize()
```


Konverterar en bild till en svartvit bild. Binära bilder är bilder vars pixlar har endast två möjliga intensitetsvärden. De visas normalt som svart och vit. Numeriskt är de två värdena ofta 0 för svart och 255 för vitt. Binära bilder skapas genom automatisk tröskelvärdesättning av en bild.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Binarize(Rectangle area) {#Binarize-java.awt.Rectangle}
```
public static PreprocessingFilter Binarize(Rectangle area)
```


Konverterar en del av bilden till en svartvit bild. Binära bilder är bilder vars pixlar har endast två möjliga intensitetsvärden. De visas normalt som svart och vit. Numeriskt är de två värdena ofta 0 för svart och 255 för vitt. Binära bilder skapas genom automatisk tröskelvärdesättning av en bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| område | java.awt.Rectangle | Rektangel att förbehandla. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### BinarizeAndDilate() {#BinarizeAndDilate}
```
public static PreprocessingFilter BinarizeAndDilate()
```


Dilatering lägger till pixlar på gränserna av objekt i en bild.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### BinarizeAndDilate(Rectangle area) {#BinarizeAndDilate-java.awt.Rectangle}
```
public static PreprocessingFilter BinarizeAndDilate(Rectangle area)
```


Dilatering lägger till pixlar på gränserna av objekt i en del av bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| område | java.awt.Rectangle | Rektangel att förbehandla. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### ContrastCorrection() {#ContrastCorrection}
```
public static PreprocessingFilter ContrastCorrection()
```


Kontrastkorrigeringsfilter.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### ContrastCorrection(Rectangle area) {#ContrastCorrection-java.awt.Rectangle}
```
public static PreprocessingFilter ContrastCorrection(Rectangle area)
```


Kontrastkorrigeringsfilter för bilddelen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| område | java.awt.Rectangle | Rektangel att förbehandla. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### Invert() {#Invert}
```
public static PreprocessingFilter Invert()
```


Inverterar automatiskt färger i en dokumentbild.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Invert(Rectangle area) {#Invert-java.awt.Rectangle}
```
public static PreprocessingFilter Invert(Rectangle area)
```


Inverterar automatiskt färger i en del av bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| område | java.awt.Rectangle | Rektangel att förbehandla. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Median() {#Median}
```
public static PreprocessingFilter Median()
```


Medianfiltret går igenom varje element i bilden och ersätter varje pixel med medianen av dess närliggande pixlar.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Median(Rectangle area) {#Median-java.awt.Rectangle}
```
public static PreprocessingFilter Median(Rectangle area)
```


Medianfiltret går igenom varje element i bilddelen och ersätter varje pixel med medianen av dess närliggande pixlar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| område | java.awt.Rectangle | Rektangel att förbehandla. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Resize(int width, int height) {#Resize-int-int}
```
public static PreprocessingFilter Resize(int width, int height)
```


Skala om bild - Höj eller sänk bildens upplösning. InterpolationFilterType = bilinear eller närmaste granne @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Den nya bredden på bilden. |
| höjd | int | Den nya höjden på bilden. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Resize(int width, int height, InterpolationFilterType type) {#Resize-int-int-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Resize(int width, int height, InterpolationFilterType type)
```


Skala om bild - höj eller sänk bildens upplösning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Den nya bredden på bilden. |
| höjd | int | Den nya höjden på bilden. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Rotate(float angle) {#Rotate-float}
```
public static PreprocessingFilter Rotate(float angle)
```


Rotera originalbilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vinkel | float | Rotationsvinkel. Värde från -360 till 360. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Rotate(float angle, Rectangle area) {#Rotate-float-java.awt.Rectangle}
```
public static PreprocessingFilter Rotate(float angle, Rectangle area)
```


Rotera bilddelen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vinkel | float | Rotationsvinkel. Värde från -360 till 360. |
| område | java.awt.Rectangle | Rektangel att förbehandla. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Scale(float ratio) {#Scale-float}
```
public static PreprocessingFilter Scale(float ratio)
```


Skala om bild - Höj eller sänk bildens upplösning. InterpolationFilterType standard bilinear eller närmaste granne @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| förhållande | float | Skalfaktorn. Rekommenderat värde från 0,1 till 1 för att krympa. Från 1 till 10 för att förstora. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Scale(float ratio, InterpolationFilterType type) {#Scale-float-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Scale(float ratio, InterpolationFilterType type)
```


Skala om bild - Höj eller sänk bildens upplösning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| förhållande | float | Skalfaktorn. Rekommenderat värde från 0,1 till 1 för att krympa. Från 1 till 10 för att förstora. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Threshold(int value) {#Threshold-int}
```
public static PreprocessingFilter Threshold(int value)
```


Skapa en binär bild baserad på att sätta ett tröskelvärde på pixelintensiteten i originalbilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Det maximala värdet. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Threshold(int value, Rectangle area) {#Threshold-int-java.awt.Rectangle}
```
public static PreprocessingFilter Threshold(int value, Rectangle area)
```


Skapa en binär bilddel baserad på att sätta ett tröskelvärde på pixelintensiteten i originalbilddelen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Det maximala värdet. |
| område | java.awt.Rectangle | Rektangel att förbehandla. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### ToGrayscale() {#ToGrayscale}
```
public static PreprocessingFilter ToGrayscale()
```


Konverterar en bild till gråskala. Gråskalebilden har 256 nivåer av ljus i bilden (0 till 255).

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - GrayscaleFilter object.
### add(PreprocessingFilter filter) {#add-com.aspose.ocr.PreprocessingFilter}
```
public void add(PreprocessingFilter filter)
```


Lägg till det nya filtret i samlingen för att fortsätta köra alla operationer. Konsistens i samlingen är viktigt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filter | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Ny operation att lägga till i filterlistan. |

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

