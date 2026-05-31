---
title: "PreprocessingFilter"
second_title: "Aspose.OCR für Java API-Referenz"
description: "Basisklasse für Bildverarbeitungsbefehle"
type: docs
weight: 24
url: /de/java/com.aspose.ocr/preprocessingfilter/
---

**Inheritance:**
java.lang.Object
```
public class PreprocessingFilter
```

Basisklasse für Bildverarbeitungsbefehle.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PreprocessingFilter()](#PreprocessingFilter) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Empty](#Empty) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [AutoDenoising()](#AutoDenoising) | Ermöglicht die Verwendung eines zusätzlichen neuronalen Netzwerks zur Verbesserung des Bildes – Rauschen reduzieren. |
| [AutoDenoising(Rectangle area)](#AutoDenoising-java.awt.Rectangle) | Ermöglicht die Verwendung eines zusätzlichen neuronalen Netzwerks zur Verbesserung des Bildausschnitts – Rauschen reduzieren. |
| [AutoDewarping()](#AutoDewarping) | Korrigiert automatisch geometrische Verzerrungen im Bild. |
| [AutoSkew()](#AutoSkew) | Ermöglicht die automatische Korrektur der Bildschräglage. |
| [AutoSkew(Rectangle area)](#AutoSkew-java.awt.Rectangle) | Ermöglicht die automatische Korrektur der Schräglage des Bildausschnitts. |
| [Binarize()](#Binarize) | Konvertiert ein Bild in ein Schwarz‑weiß‑Bild. |
| [Binarize(Rectangle area)](#Binarize-java.awt.Rectangle) | Konvertiert einen Teil des Bildes in ein Schwarz‑weiß‑Bild. |
| [BinarizeAndDilate()](#BinarizeAndDilate) | Die Dilatation fügt Pixel zu den Grenzen von Objekten in einem Bild hinzu. |
| [BinarizeAndDilate(Rectangle area)](#BinarizeAndDilate-java.awt.Rectangle) | Die Dilatation fügt Pixel zu den Grenzen von Objekten in einem Bildausschnitt hinzu. |
| [ContrastCorrection()](#ContrastCorrection) | Kontrastkorrekturfilter. |
| [ContrastCorrection(Rectangle area)](#ContrastCorrection-java.awt.Rectangle) | Kontrastkorrekturfilter für den Bildausschnitt. |
| [Invert()](#Invert) | Invertiert automatisch die Farben in einem Dokumentenbild. |
| [Invert(Rectangle area)](#Invert-java.awt.Rectangle) | Invertiert automatisch die Farben in einem Bildausschnitt. |
| [Median()](#Median) | Der Medianfilter durchläuft jedes Element des Bildes und ersetzt jedes Pixel durch den Median seiner Nachbarpixel. |
| [Median(Rectangle area)](#Median-java.awt.Rectangle) | Der Medianfilter läuft durch jedes Element des Bildausschnitts und ersetzt jedes Pixel durch den Median seiner Nachbarpixel. |
| [Resize(int width, int height)](#Resize-int-int) | Bild skalieren – Auf- oder Abskalieren der Bildauflösung. |
| [Resize(int width, int height, InterpolationFilterType type)](#Resize-int-int-com.aspose.ocr.InterpolationFilterType) | Bild skalieren – Auf- oder Abskalieren der Bildauflösung. |
| [Rotate(float angle)](#Rotate-float) | Originalbild drehen. |
| [Rotate(float angle, Rectangle area)](#Rotate-float-java.awt.Rectangle) | Den Bildausschnitt drehen. |
| [Scale(float ratio)](#Scale-float) | Bild skalieren – Auf- oder Abskalieren der Bildauflösung. |
| [Scale(float ratio, InterpolationFilterType type)](#Scale-float-com.aspose.ocr.InterpolationFilterType) | Bild skalieren – Auf- oder Abskalieren der Bildauflösung. |
| [Threshold(int value)](#Threshold-int) | Erstelle ein Binärbild, indem ein Schwellenwert für die Pixelintensität des Originalbildes festgelegt wird. |
| [Threshold(int value, Rectangle area)](#Threshold-int-java.awt.Rectangle) | Erstelle einen Binärbildausschnitt, indem ein Schwellenwert für die Pixelintensität des Originalbildausschnitts festgelegt wird. |
| [ToGrayscale()](#ToGrayscale) | Konvertiert ein Bild in ein Graustufenbild. |
| [add(PreprocessingFilter filter)](#add-com.aspose.ocr.PreprocessingFilter) | Füge den neuen Filter zur Sammlung hinzu, um alle Vorgänge weiter auszuführen. |
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


Ermöglicht die Verwendung eines zusätzlichen neuronalen Netzwerks zur Verbesserung des Bildes – Rauschen reduzieren. Nützlich für Bilder mit Scanartefakten, Verzerrungen, Flecken, Blendungen, Gradienten, Fremdelementen.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDenoising(Rectangle area) {#AutoDenoising-java.awt.Rectangle}
```
public static PreprocessingFilter AutoDenoising(Rectangle area)
```


Ermöglicht die Verwendung eines zusätzlichen neuronalen Netzwerks zur Verbesserung des Bildausschnitts – Rauschen reduzieren. Nützlich für Bilder mit Scanartefakten, Verzerrungen, Flecken, Blendungen, Gradienten, Fremdelementen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fläche | java.awt.Rectangle | Rectangle zum Vorverarbeiten. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDewarping() {#AutoDewarping}
```
public static PreprocessingFilter AutoDewarping()
```


Korrigiert automatisch geometrische Verzerrungen im Bild. Äußerst ressourcenintensiv!

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDewarpingFilter object.
### AutoSkew() {#AutoSkew}
```
public static PreprocessingFilter AutoSkew()
```


Ermöglicht die automatische Korrektur der Bildschräglage.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### AutoSkew(Rectangle area) {#AutoSkew-java.awt.Rectangle}
```
public static PreprocessingFilter AutoSkew(Rectangle area)
```


Ermöglicht die automatische Korrektur der Schräglage des Bildausschnitts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fläche | java.awt.Rectangle | Rectangle zum Vorverarbeiten. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### Binarize() {#Binarize}
```
public static PreprocessingFilter Binarize()
```


Konvertiert ein Bild in ein Schwarz‑weiß‑Bild. Binärbilder sind Bilder, deren Pixel nur zwei mögliche Intensitätswerte haben. Sie werden normalerweise in Schwarz und Weiß angezeigt. Numerisch sind die beiden Werte häufig 0 für Schwarz und 255 für Weiß. Binärbilder werden durch automatisches Schwellenwertsetzen eines Bildes erzeugt.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Binarize(Rectangle area) {#Binarize-java.awt.Rectangle}
```
public static PreprocessingFilter Binarize(Rectangle area)
```


Konvertiert einen Bildausschnitt in ein Schwarz‑weiß‑Bild. Binärbilder sind Bilder, deren Pixel nur zwei mögliche Intensitätswerte haben. Sie werden normalerweise in Schwarz und Weiß angezeigt. Numerisch sind die beiden Werte häufig 0 für Schwarz und 255 für Weiß. Binärbilder werden durch automatisches Schwellenwertsetzen eines Bildes erzeugt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fläche | java.awt.Rectangle | Rectangle zum Vorverarbeiten. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### BinarizeAndDilate() {#BinarizeAndDilate}
```
public static PreprocessingFilter BinarizeAndDilate()
```


Die Dilatation fügt Pixel zu den Grenzen von Objekten in einem Bild hinzu.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### BinarizeAndDilate(Rectangle area) {#BinarizeAndDilate-java.awt.Rectangle}
```
public static PreprocessingFilter BinarizeAndDilate(Rectangle area)
```


Die Dilatation fügt Pixel zu den Grenzen von Objekten in einem Bildausschnitt hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fläche | java.awt.Rectangle | Rectangle zum Vorverarbeiten. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### ContrastCorrection() {#ContrastCorrection}
```
public static PreprocessingFilter ContrastCorrection()
```


Kontrastkorrekturfilter.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### ContrastCorrection(Rectangle area) {#ContrastCorrection-java.awt.Rectangle}
```
public static PreprocessingFilter ContrastCorrection(Rectangle area)
```


Kontrastkorrekturfilter für den Bildausschnitt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fläche | java.awt.Rectangle | Rectangle zum Vorverarbeiten. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### Invert() {#Invert}
```
public static PreprocessingFilter Invert()
```


Invertiert automatisch die Farben in einem Dokumentenbild.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Invert(Rectangle area) {#Invert-java.awt.Rectangle}
```
public static PreprocessingFilter Invert(Rectangle area)
```


Invertiert automatisch die Farben in einem Bildausschnitt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fläche | java.awt.Rectangle | Rectangle zum Vorverarbeiten. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Median() {#Median}
```
public static PreprocessingFilter Median()
```


Der Medianfilter durchläuft jedes Element des Bildes und ersetzt jedes Pixel durch den Median seiner Nachbarpixel.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Median(Rectangle area) {#Median-java.awt.Rectangle}
```
public static PreprocessingFilter Median(Rectangle area)
```


Der Medianfilter läuft durch jedes Element des Bildausschnitts und ersetzt jedes Pixel durch den Median seiner Nachbarpixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fläche | java.awt.Rectangle | Rectangle zum Vorverarbeiten. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Resize(int width, int height) {#Resize-int-int}
```
public static PreprocessingFilter Resize(int width, int height)
```


Bild skalieren – Auf- oder Abskalieren der Bildauflösung. InterpolationFilterType = bilinear oder nächster Nachbar @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die neue Breite des Bildes. |
| Höhe | int | Die neue Höhe des Bildes. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Resize(int width, int height, InterpolationFilterType type) {#Resize-int-int-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Resize(int width, int height, InterpolationFilterType type)
```


Bild skalieren – Auf- oder Abskalieren der Bildauflösung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die neue Breite des Bildes. |
| Höhe | int | Die neue Höhe des Bildes. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Rotate(float angle) {#Rotate-float}
```
public static PreprocessingFilter Rotate(float angle)
```


Originalbild drehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Drehwinkel. Wert von -360 bis 360. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Rotate(float angle, Rectangle area) {#Rotate-float-java.awt.Rectangle}
```
public static PreprocessingFilter Rotate(float angle, Rectangle area)
```


Den Bildausschnitt drehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Drehwinkel. Wert von -360 bis 360. |
| Fläche | java.awt.Rectangle | Rectangle zum Vorverarbeiten. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Scale(float ratio) {#Scale-float}
```
public static PreprocessingFilter Scale(float ratio)
```


Bild neu skalieren - Bildauflösung hoch- oder herunterskalieren. InterpolationFilterType Standard bilinear oder nächster Nachbar @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Verhältnis | float | Der Skalierungsfaktor. Empfohlener Wert von 0,1 bis 1 zum Verkleinern. Von 1 bis 10 zum Vergrößern. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Scale(float ratio, InterpolationFilterType type) {#Scale-float-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Scale(float ratio, InterpolationFilterType type)
```


Bild skalieren – Auf- oder Abskalieren der Bildauflösung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Verhältnis | float | Der Skalierungsfaktor. Empfohlener Wert von 0,1 bis 1 zum Verkleinern. Von 1 bis 10 zum Vergrößern. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Threshold(int value) {#Threshold-int}
```
public static PreprocessingFilter Threshold(int value)
```


Erstelle ein Binärbild, indem ein Schwellenwert für die Pixelintensität des Originalbildes festgelegt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der maximale Wert. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Threshold(int value, Rectangle area) {#Threshold-int-java.awt.Rectangle}
```
public static PreprocessingFilter Threshold(int value, Rectangle area)
```


Erstelle einen Binärbildausschnitt, indem ein Schwellenwert für die Pixelintensität des Originalbildausschnitts festgelegt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der maximale Wert. |
| Fläche | java.awt.Rectangle | Rectangle zum Vorverarbeiten. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### ToGrayscale() {#ToGrayscale}
```
public static PreprocessingFilter ToGrayscale()
```


Konvertiert ein Bild in ein Graustufenbild. Graustufenbilder haben 256 Helligkeitsstufen im Bild (0 bis 255).

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - GrayscaleFilter object.
### add(PreprocessingFilter filter) {#add-com.aspose.ocr.PreprocessingFilter}
```
public void add(PreprocessingFilter filter)
```


Fügen Sie den neuen Filter zur Sammlung hinzu, um alle Vorgänge weiter auszuführen. Konsistenz in der Sammlung ist wichtig.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filter | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Neue Operation zum Hinzufügen zur Filterliste. |

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

