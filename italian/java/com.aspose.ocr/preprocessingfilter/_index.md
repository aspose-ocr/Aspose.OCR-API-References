---
title: "PreprocessingFilter"
second_title: "Riferimento API di Aspose.OCR per Java"
description: "Classe base per i comandi di elaborazione delle immagini"
type: docs
weight: 24
url: /it/java/com.aspose.ocr/preprocessingfilter/
---

**Inheritance:**
java.lang.Object
```
public class PreprocessingFilter
```

Classe base per i comandi di elaborazione delle immagini.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PreprocessingFilter()](#PreprocessingFilter) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [Empty](#Empty) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [AutoDenoising()](#AutoDenoising) | Consente l'uso di una rete neurale aggiuntiva per migliorare l'immagine - ridurre il rumore. |
| [AutoDenoising(Rectangle area)](#AutoDenoising-java.awt.Rectangle) | Consente l'uso di una rete neurale aggiuntiva per migliorare la parte dell'immagine - ridurre il rumore. |
| [AutoDewarping()](#AutoDewarping) | Corregge automaticamente le distorsioni geometriche nell'immagine. |
| [AutoSkew()](#AutoSkew) | Abilita la correzione automatica dell'inclinazione dell'immagine. |
| [AutoSkew(Rectangle area)](#AutoSkew-java.awt.Rectangle) | Abilita la correzione automatica dell'inclinazione della parte dell'immagine. |
| [Binarize()](#Binarize) | Converte un'immagine in immagine in bianco e nero. |
| [Binarize(Rectangle area)](#Binarize-java.awt.Rectangle) | Converte una parte dell'immagine in immagine in bianco e nero. |
| [BinarizeAndDilate()](#BinarizeAndDilate) | La dilatazione aggiunge pixel ai bordi degli oggetti in un'immagine. |
| [BinarizeAndDilate(Rectangle area)](#BinarizeAndDilate-java.awt.Rectangle) | La dilatazione aggiunge pixel ai bordi degli oggetti in una parte dell'immagine. |
| [ContrastCorrection()](#ContrastCorrection) | Filtro di correzione del contrasto. |
| [ContrastCorrection(Rectangle area)](#ContrastCorrection-java.awt.Rectangle) | Filtro di correzione del contrasto per la parte dell'immagine. |
| [Invert()](#Invert) | Inverte automaticamente i colori in un'immagine di documento. |
| [Invert(Rectangle area)](#Invert-java.awt.Rectangle) | Inverte automaticamente i colori in una parte dell'immagine. |
| [Median()](#Median) | Il filtro mediano scorre ogni elemento dell'immagine e sostituisce ogni pixel con la mediana dei pixel vicini. |
| [Median(Rectangle area)](#Median-java.awt.Rectangle) | Il filtro mediano attraversa ogni elemento della parte dell'immagine e sostituisce ogni pixel con la mediana dei pixel vicini. |
| [Resize(int width, int height)](#Resize-int-int) | Ridimensiona immagine - Aumenta o diminuisci la risoluzione dell'immagine. |
| [Resize(int width, int height, InterpolationFilterType type)](#Resize-int-int-com.aspose.ocr.InterpolationFilterType) | Ridimensiona immagine - aumenta o diminuisci la risoluzione dell'immagine. |
| [Rotate(float angle)](#Rotate-float) | Ruota l'immagine originale. |
| [Rotate(float angle, Rectangle area)](#Rotate-float-java.awt.Rectangle) | Ruota la parte dell'immagine. |
| [Scale(float ratio)](#Scale-float) | Ridimensiona immagine - Aumenta o diminuisci la risoluzione dell'immagine. |
| [Scale(float ratio, InterpolationFilterType type)](#Scale-float-com.aspose.ocr.InterpolationFilterType) | Ridimensiona immagine - Aumenta o diminuisci la risoluzione dell'immagine. |
| [Threshold(int value)](#Threshold-int) | Crea un'immagine binaria impostando un valore di soglia sull'intensità dei pixel dell'immagine originale. |
| [Threshold(int value, Rectangle area)](#Threshold-int-java.awt.Rectangle) | Crea una parte di immagine binaria impostando un valore di soglia sull'intensità dei pixel della parte dell'immagine originale. |
| [ToGrayscale()](#ToGrayscale) | Converte un'immagine in immagine in scala di grigi. |
| [add(PreprocessingFilter filter)](#add-com.aspose.ocr.PreprocessingFilter) | Aggiungi il nuovo filtro alla collezione per eseguire ulteriormente tutte le operazioni. |
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


Abilita l'uso di una rete neurale aggiuntiva per migliorare l'immagine - ridurre il rumore. Utile per immagini con artefatti di scansione, distorsioni, macchie, bagliori, gradienti, elementi estranei.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDenoising(Rectangle area) {#AutoDenoising-java.awt.Rectangle}
```
public static PreprocessingFilter AutoDenoising(Rectangle area)
```


Abilita l'uso di una rete neurale aggiuntiva per migliorare la parte dell'immagine - ridurre il rumore. Utile per immagini con artefatti di scansione, distorsioni, macchie, bagliori, gradienti, elementi estranei.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| area | java.awt.Rectangle | Rettangolo da pre-elaborare. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDewarping() {#AutoDewarping}
```
public static PreprocessingFilter AutoDewarping()
```


Corregge automaticamente le distorsioni geometriche nell'immagine. Estremamente intensivo di risorse!

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDewarpingFilter object.
### AutoSkew() {#AutoSkew}
```
public static PreprocessingFilter AutoSkew()
```


Abilita la correzione automatica dell'inclinazione dell'immagine.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### AutoSkew(Rectangle area) {#AutoSkew-java.awt.Rectangle}
```
public static PreprocessingFilter AutoSkew(Rectangle area)
```


Abilita la correzione automatica dell'inclinazione della parte dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| area | java.awt.Rectangle | Rettangolo da pre-elaborare. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### Binarize() {#Binarize}
```
public static PreprocessingFilter Binarize()
```


Converte un'immagine in immagine in bianco e nero. Le immagini binarie sono immagini i cui pixel hanno solo due possibili valori di intensità. Sono normalmente visualizzate in bianco e nero. Numericamente, i due valori sono spesso 0 per il nero e 255 per il bianco. Le immagini binarie sono prodotte mediante sogliatura automatica di un'immagine.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Binarize(Rectangle area) {#Binarize-java.awt.Rectangle}
```
public static PreprocessingFilter Binarize(Rectangle area)
```


Converte una parte dell'immagine in immagine in bianco e nero. Le immagini binarie sono immagini i cui pixel hanno solo due possibili valori di intensità. Sono normalmente visualizzate in bianco e nero. Numericamente, i due valori sono spesso 0 per il nero e 255 per il bianco. Le immagini binarie sono prodotte mediante sogliatura automatica di un'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| area | java.awt.Rectangle | Rettangolo da pre-elaborare. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### BinarizeAndDilate() {#BinarizeAndDilate}
```
public static PreprocessingFilter BinarizeAndDilate()
```


La dilatazione aggiunge pixel ai bordi degli oggetti in un'immagine.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### BinarizeAndDilate(Rectangle area) {#BinarizeAndDilate-java.awt.Rectangle}
```
public static PreprocessingFilter BinarizeAndDilate(Rectangle area)
```


La dilatazione aggiunge pixel ai bordi degli oggetti in una parte dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| area | java.awt.Rectangle | Rettangolo da pre-elaborare. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### ContrastCorrection() {#ContrastCorrection}
```
public static PreprocessingFilter ContrastCorrection()
```


Filtro di correzione del contrasto.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### ContrastCorrection(Rectangle area) {#ContrastCorrection-java.awt.Rectangle}
```
public static PreprocessingFilter ContrastCorrection(Rectangle area)
```


Filtro di correzione del contrasto per la parte dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| area | java.awt.Rectangle | Rettangolo da pre-elaborare. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### Invert() {#Invert}
```
public static PreprocessingFilter Invert()
```


Inverte automaticamente i colori in un'immagine di documento.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Invert(Rectangle area) {#Invert-java.awt.Rectangle}
```
public static PreprocessingFilter Invert(Rectangle area)
```


Inverte automaticamente i colori in una parte dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| area | java.awt.Rectangle | Rettangolo da pre-elaborare. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Median() {#Median}
```
public static PreprocessingFilter Median()
```


Il filtro mediano scorre ogni elemento dell'immagine e sostituisce ogni pixel con la mediana dei pixel vicini.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Median(Rectangle area) {#Median-java.awt.Rectangle}
```
public static PreprocessingFilter Median(Rectangle area)
```


Il filtro mediano attraversa ogni elemento della parte dell'immagine e sostituisce ogni pixel con la mediana dei pixel vicini.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| area | java.awt.Rectangle | Rettangolo da pre-elaborare. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Resize(int width, int height) {#Resize-int-int}
```
public static PreprocessingFilter Resize(int width, int height)
```


Ridimensiona immagine - Aumenta o diminuisci la risoluzione dell'immagine. InterpolationFilterType = bilinear or nearest neighbor @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza | int | La nuova larghezza dell'immagine. |
| altezza | int | La nuova altezza dell'immagine. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Resize(int width, int height, InterpolationFilterType type) {#Resize-int-int-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Resize(int width, int height, InterpolationFilterType type)
```


Ridimensiona immagine - aumenta o diminuisci la risoluzione dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza | int | La nuova larghezza dell'immagine. |
| altezza | int | La nuova altezza dell'immagine. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Rotate(float angle) {#Rotate-float}
```
public static PreprocessingFilter Rotate(float angle)
```


Ruota l'immagine originale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angolo | float | Angolo di rotazione. Valore da -360 a 360. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Rotate(float angle, Rectangle area) {#Rotate-float-java.awt.Rectangle}
```
public static PreprocessingFilter Rotate(float angle, Rectangle area)
```


Ruota la parte dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angolo | float | Angolo di rotazione. Valore da -360 a 360. |
| area | java.awt.Rectangle | Rettangolo da pre-elaborare. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Scale(float ratio) {#Scale-float}
```
public static PreprocessingFilter Scale(float ratio)
```


Ridimensiona immagine - Aumenta o diminuisci la risoluzione dell'immagine. InterpolationFilterType predefinito bilineare o nearest neighbor @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rapporto | float | Il fattore di scala. Valore consigliato da 0,1 a 1 per ridurre. Da 1 a 10 per ingrandire. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Scale(float ratio, InterpolationFilterType type) {#Scale-float-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Scale(float ratio, InterpolationFilterType type)
```


Ridimensiona immagine - Aumenta o diminuisci la risoluzione dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rapporto | float | Il fattore di scala. Valore consigliato da 0,1 a 1 per ridurre. Da 1 a 10 per ingrandire. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Threshold(int value) {#Threshold-int}
```
public static PreprocessingFilter Threshold(int value)
```


Crea un'immagine binaria impostando un valore di soglia sull'intensità dei pixel dell'immagine originale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il valore massimo. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Threshold(int value, Rectangle area) {#Threshold-int-java.awt.Rectangle}
```
public static PreprocessingFilter Threshold(int value, Rectangle area)
```


Crea una parte di immagine binaria impostando un valore di soglia sull'intensità dei pixel della parte dell'immagine originale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il valore massimo. |
| area | java.awt.Rectangle | Rettangolo da pre-elaborare. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### ToGrayscale() {#ToGrayscale}
```
public static PreprocessingFilter ToGrayscale()
```


Converte un'immagine in immagine in scala di grigi. L'immagine in scala di grigi ha 256 livelli di luminosità nell'immagine (0 a 255).

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - GrayscaleFilter object.
### add(PreprocessingFilter filter) {#add-com.aspose.ocr.PreprocessingFilter}
```
public void add(PreprocessingFilter filter)
```


Aggiungi il nuovo filtro alla collezione per eseguire ulteriormente tutte le operazioni. La coerenza nella collezione è importante.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filter | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Nuova operazione da aggiungere all'elenco dei filtri. |

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

