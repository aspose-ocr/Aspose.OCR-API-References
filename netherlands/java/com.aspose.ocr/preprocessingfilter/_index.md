---
title: "PreprocessingFilter"
second_title: "Aspose.OCR for Java API-referentie"
description: "Basisklasse voor beeldverwerkingsopdrachten"
type: docs
weight: 24
url: /nl/java/com.aspose.ocr/preprocessingfilter/
---

**Inheritance:**
java.lang.Object
```
public class PreprocessingFilter
```

Basisklasse voor beeldverwerkingsopdrachten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PreprocessingFilter()](#PreprocessingFilter) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Empty](#Empty) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [AutoDenoising()](#AutoDenoising) | Schakelt het gebruik van een extra neuraal netwerk in om de afbeelding te verbeteren - ruis te verminderen. |
| [AutoDenoising(Rectangle area)](#AutoDenoising-java.awt.Rectangle) | Schakelt het gebruik van een extra neuraal netwerk in om het deel van de afbeelding te verbeteren - ruis te verminderen. |
| [AutoDewarping()](#AutoDewarping) | Corrigeert automatisch geometrische vervormingen in de afbeelding. |
| [AutoSkew()](#AutoSkew) | Schakelt de automatische scheefstandcorrectie van de afbeelding in. |
| [AutoSkew(Rectangle area)](#AutoSkew-java.awt.Rectangle) | Schakelt de automatische scheefstandcorrectie van het afbeeldingsdeel in. |
| [Binarize()](#Binarize) | Converteert een afbeelding naar een zwart-wit afbeelding. |
| [Binarize(Rectangle area)](#Binarize-java.awt.Rectangle) | Converteert een deel van de afbeelding naar een zwart-wit afbeelding. |
| [BinarizeAndDilate()](#BinarizeAndDilate) | Dilatie voegt pixels toe aan de randen van objecten in een afbeelding. |
| [BinarizeAndDilate(Rectangle area)](#BinarizeAndDilate-java.awt.Rectangle) | Dilatie voegt pixels toe aan de randen van objecten in een deel van de afbeelding. |
| [ContrastCorrection()](#ContrastCorrection) | Contrastcorrectiefilter. |
| [ContrastCorrection(Rectangle area)](#ContrastCorrection-java.awt.Rectangle) | Contrastcorrectiefilter voor het deel van de afbeelding. |
| [Invert()](#Invert) | Keert automatisch de kleuren om in een documentafbeelding. |
| [Invert(Rectangle area)](#Invert-java.awt.Rectangle) | Keert automatisch de kleuren om in een deel van de afbeelding. |
| [Median()](#Median) | Het medianfilter loopt door elk element van de afbeelding en vervangt elke pixel door de mediaan van de naburige pixels. |
| [Median(Rectangle area)](#Median-java.awt.Rectangle) | Het medianfilter loopt door elk element van het deel van de afbeelding en vervangt elke pixel door de mediaan van de aangrenzende pixels. |
| [Resize(int width, int height)](#Resize-int-int) | Afbeelding herschalen - vergroten of verkleinen van de resolutie van de afbeelding. |
| [Resize(int width, int height, InterpolationFilterType type)](#Resize-int-int-com.aspose.ocr.InterpolationFilterType) | Afbeelding herschalen - vergroten of verkleinen van de resolutie van de afbeelding. |
| [Rotate(float angle)](#Rotate-float) | Originele afbeelding roteren. |
| [Rotate(float angle, Rectangle area)](#Rotate-float-java.awt.Rectangle) | Het deel van de afbeelding roteren. |
| [Scale(float ratio)](#Scale-float) | Afbeelding herschalen - vergroten of verkleinen van de resolutie van de afbeelding. |
| [Scale(float ratio, InterpolationFilterType type)](#Scale-float-com.aspose.ocr.InterpolationFilterType) | Afbeelding herschalen - vergroten of verkleinen van de resolutie van de afbeelding. |
| [Threshold(int value)](#Threshold-int) | Maak een binaire afbeelding op basis van het instellen van een drempelwaarde op de pixelintensiteit van de originele afbeelding. |
| [Threshold(int value, Rectangle area)](#Threshold-int-java.awt.Rectangle) | Maak een binaire afbeelding van een deel op basis van het instellen van een drempelwaarde op de pixelintensiteit van het originele afbeeldingsdeel. |
| [ToGrayscale()](#ToGrayscale) | Converteert een afbeelding naar een grijswaardenafbeelding. |
| [add(PreprocessingFilter filter)](#add-com.aspose.ocr.PreprocessingFilter) | Voeg het nieuwe filter toe aan de collectie om alle bewerkingen verder uit te voeren. |
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


Staat het gebruik van een extra neuraal netwerk toe om de afbeelding te verbeteren - ruis te verminderen. Handig voor afbeeldingen met scanartefacten, vervormingen, vlekken, schitteringen, gradiënten, vreemde elementen.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDenoising(Rectangle area) {#AutoDenoising-java.awt.Rectangle}
```
public static PreprocessingFilter AutoDenoising(Rectangle area)
```


Staat het gebruik van een extra neuraal netwerk toe om het deel van de afbeelding te verbeteren - ruis te verminderen. Handig voor afbeeldingen met scanartefacten, vervormingen, vlekken, schitteringen, gradiënten, vreemde elementen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gebied | java.awt.Rectangle | Rechthoek om voor te verwerken. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDewarping() {#AutoDewarping}
```
public static PreprocessingFilter AutoDewarping()
```


Corrigeert automatisch geometrische vervormingen in de afbeelding. Zeer resource-intensief!

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDewarpingFilter object.
### AutoSkew() {#AutoSkew}
```
public static PreprocessingFilter AutoSkew()
```


Schakelt de automatische scheefstandcorrectie van de afbeelding in.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### AutoSkew(Rectangle area) {#AutoSkew-java.awt.Rectangle}
```
public static PreprocessingFilter AutoSkew(Rectangle area)
```


Schakelt de automatische scheefstandcorrectie van het afbeeldingsdeel in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gebied | java.awt.Rectangle | Rechthoek om voor te verwerken. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### Binarize() {#Binarize}
```
public static PreprocessingFilter Binarize()
```


Converteert een afbeelding naar een zwart-wit afbeelding. Binaire afbeeldingen zijn afbeeldingen waarvan de pixels slechts twee mogelijke intensiteitswaarden hebben. Ze worden normaal weergegeven als zwart en wit. Numeriek zijn de twee waarden vaak 0 voor zwart en 255 voor wit. Binaire afbeeldingen worden geproduceerd door automatische drempelbepaling van een afbeelding.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Binarize(Rectangle area) {#Binarize-java.awt.Rectangle}
```
public static PreprocessingFilter Binarize(Rectangle area)
```


Converteert een deel van de afbeelding naar een zwart-wit afbeelding. Binaire afbeeldingen zijn afbeeldingen waarvan de pixels slechts twee mogelijke intensiteitswaarden hebben. Ze worden normaal weergegeven als zwart en wit. Numeriek zijn de twee waarden vaak 0 voor zwart en 255 voor wit. Binaire afbeeldingen worden geproduceerd door automatische drempelbepaling van een afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gebied | java.awt.Rectangle | Rechthoek om voor te verwerken. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### BinarizeAndDilate() {#BinarizeAndDilate}
```
public static PreprocessingFilter BinarizeAndDilate()
```


Dilatie voegt pixels toe aan de randen van objecten in een afbeelding.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### BinarizeAndDilate(Rectangle area) {#BinarizeAndDilate-java.awt.Rectangle}
```
public static PreprocessingFilter BinarizeAndDilate(Rectangle area)
```


Dilatie voegt pixels toe aan de randen van objecten in een deel van de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gebied | java.awt.Rectangle | Rechthoek om voor te verwerken. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### ContrastCorrection() {#ContrastCorrection}
```
public static PreprocessingFilter ContrastCorrection()
```


Contrastcorrectiefilter.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### ContrastCorrection(Rectangle area) {#ContrastCorrection-java.awt.Rectangle}
```
public static PreprocessingFilter ContrastCorrection(Rectangle area)
```


Contrastcorrectiefilter voor het deel van de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gebied | java.awt.Rectangle | Rechthoek om voor te verwerken. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### Invert() {#Invert}
```
public static PreprocessingFilter Invert()
```


Keert automatisch de kleuren om in een documentafbeelding.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Invert(Rectangle area) {#Invert-java.awt.Rectangle}
```
public static PreprocessingFilter Invert(Rectangle area)
```


Keert automatisch de kleuren om in een deel van de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gebied | java.awt.Rectangle | Rechthoek om voor te verwerken. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Median() {#Median}
```
public static PreprocessingFilter Median()
```


Het medianfilter loopt door elk element van de afbeelding en vervangt elke pixel door de mediaan van de naburige pixels.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Median(Rectangle area) {#Median-java.awt.Rectangle}
```
public static PreprocessingFilter Median(Rectangle area)
```


Het medianfilter loopt door elk element van het deel van de afbeelding en vervangt elke pixel door de mediaan van de aangrenzende pixels.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gebied | java.awt.Rectangle | Rechthoek om voor te verwerken. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Resize(int width, int height) {#Resize-int-int}
```
public static PreprocessingFilter Resize(int width, int height)
```


Afbeelding herschalen - vergroten of verkleinen van de resolutie van de afbeelding. InterpolationFilterType = bilineair of dichtstbijzijnde buur @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| breedte | int | De nieuwe breedte van de afbeelding. |
| hoogte | int | De nieuwe hoogte van de afbeelding. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Resize(int width, int height, InterpolationFilterType type) {#Resize-int-int-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Resize(int width, int height, InterpolationFilterType type)
```


Afbeelding herschalen - vergroten of verkleinen van de resolutie van de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| breedte | int | De nieuwe breedte van de afbeelding. |
| hoogte | int | De nieuwe hoogte van de afbeelding. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Rotate(float angle) {#Rotate-float}
```
public static PreprocessingFilter Rotate(float angle)
```


Originele afbeelding roteren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hoek | float | Hoek van rotatie. Waarde van -360 tot 360. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Rotate(float angle, Rectangle area) {#Rotate-float-java.awt.Rectangle}
```
public static PreprocessingFilter Rotate(float angle, Rectangle area)
```


Het deel van de afbeelding roteren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hoek | float | Hoek van rotatie. Waarde van -360 tot 360. |
| gebied | java.awt.Rectangle | Rechthoek om voor te verwerken. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Scale(float ratio) {#Scale-float}
```
public static PreprocessingFilter Scale(float ratio)
```


Afbeelding herschalen - Afbeeldingsresolutie vergroten of verkleinen. InterpolationFilterType standaard bilineair of dichtstbijzijnde buur @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| verhouding | float | De schaalfactor. Aanbevolen waarde van 0,1 tot 1 om te verkleinen. Van 1 tot 10 om te vergroten. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Scale(float ratio, InterpolationFilterType type) {#Scale-float-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Scale(float ratio, InterpolationFilterType type)
```


Afbeelding herschalen - vergroten of verkleinen van de resolutie van de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| verhouding | float | De schaalfactor. Aanbevolen waarde van 0,1 tot 1 om te verkleinen. Van 1 tot 10 om te vergroten. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Threshold(int value) {#Threshold-int}
```
public static PreprocessingFilter Threshold(int value)
```


Maak een binaire afbeelding op basis van het instellen van een drempelwaarde op de pixelintensiteit van de originele afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De maximale waarde. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Threshold(int value, Rectangle area) {#Threshold-int-java.awt.Rectangle}
```
public static PreprocessingFilter Threshold(int value, Rectangle area)
```


Maak een binaire afbeelding van een deel op basis van het instellen van een drempelwaarde op de pixelintensiteit van het originele afbeeldingsdeel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De maximale waarde. |
| gebied | java.awt.Rectangle | Rechthoek om voor te verwerken. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### ToGrayscale() {#ToGrayscale}
```
public static PreprocessingFilter ToGrayscale()
```


Converteert een afbeelding naar een grijswaardenafbeelding. Een grijswaardenafbeelding heeft 256 lichtniveaus in de afbeelding (0 tot 255).

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - GrayscaleFilter object.
### add(PreprocessingFilter filter) {#add-com.aspose.ocr.PreprocessingFilter}
```
public void add(PreprocessingFilter filter)
```


Voeg het nieuwe filter toe aan de collectie om alle bewerkingen verder uit te voeren. Consistentie in de collectie is belangrijk.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filter | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Nieuwe bewerking om toe te voegen aan de filterlijst. |

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

