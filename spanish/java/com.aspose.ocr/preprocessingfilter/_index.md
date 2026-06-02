---
title: "PreprocessingFilter"
second_title: "Referencia de API de Aspose.OCR para Java"
description: "Clase base para comandos de procesamiento de imágenes"
type: docs
weight: 24
url: /es/java/com.aspose.ocr/preprocessingfilter/
---

**Inheritance:**
java.lang.Object
```
public class PreprocessingFilter
```

Clase base para comandos de procesamiento de imágenes.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PreprocessingFilter()](#PreprocessingFilter) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [Empty](#Empty) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [AutoDenoising()](#AutoDenoising) | Permite el uso de una red neuronal adicional para mejorar la imagen - reducir el ruido. |
| [AutoDenoising(Rectangle area)](#AutoDenoising-java.awt.Rectangle) | Permite el uso de una red neuronal adicional para mejorar la parte de la imagen - reducir el ruido. |
| [AutoDewarping()](#AutoDewarping) | Corrige automáticamente las distorsiones geométricas en la imagen. |
| [AutoSkew()](#AutoSkew) | Permite la corrección automática de la inclinación de la imagen. |
| [AutoSkew(Rectangle area)](#AutoSkew-java.awt.Rectangle) | Permite la corrección automática de la inclinación de la parte de la imagen. |
| [Binarize()](#Binarize) | Convierte una imagen a una imagen en blanco y negro. |
| [Binarize(Rectangle area)](#Binarize-java.awt.Rectangle) | Convierte una parte de la imagen a una imagen en blanco y negro. |
| [BinarizeAndDilate()](#BinarizeAndDilate) | La dilatación agrega píxeles a los bordes de los objetos en una imagen. |
| [BinarizeAndDilate(Rectangle area)](#BinarizeAndDilate-java.awt.Rectangle) | La dilatación agrega píxeles a los bordes de los objetos en una parte de la imagen. |
| [ContrastCorrection()](#ContrastCorrection) | Filtro de corrección de contraste. |
| [ContrastCorrection(Rectangle area)](#ContrastCorrection-java.awt.Rectangle) | Filtro de corrección de contraste para la parte de la imagen. |
| [Invert()](#Invert) | Invierte automáticamente los colores en una imagen de documento. |
| [Invert(Rectangle area)](#Invert-java.awt.Rectangle) | Invierte automáticamente los colores en una parte de la imagen. |
| [Median()](#Median) | El filtro mediano recorre cada elemento de la imagen y reemplaza cada píxel con la mediana de sus píxeles vecinos. |
| [Median(Rectangle area)](#Median-java.awt.Rectangle) | El filtro mediano recorre cada elemento de la parte de la imagen y reemplaza cada píxel con la mediana de sus píxeles vecinos. |
| [Resize(int width, int height)](#Resize-int-int) | Reescalar imagen - Aumentar o reducir la resolución de la imagen. |
| [Resize(int width, int height, InterpolationFilterType type)](#Resize-int-int-com.aspose.ocr.InterpolationFilterType) | Reescalar imagen - aumentar o reducir la resolución de la imagen. |
| [Rotate(float angle)](#Rotate-float) | Rotar la imagen original. |
| [Rotate(float angle, Rectangle area)](#Rotate-float-java.awt.Rectangle) | Rotar la parte de la imagen. |
| [Scale(float ratio)](#Scale-float) | Reescalar imagen - Aumentar o reducir la resolución de la imagen. |
| [Scale(float ratio, InterpolationFilterType type)](#Scale-float-com.aspose.ocr.InterpolationFilterType) | Reescalar imagen - Aumentar o reducir la resolución de la imagen. |
| [Threshold(int value)](#Threshold-int) | Crear una imagen binaria basándose en establecer un valor de umbral en la intensidad de píxeles de la imagen original. |
| [Threshold(int value, Rectangle area)](#Threshold-int-java.awt.Rectangle) | Crear una parte de imagen binaria basándose en establecer un valor de umbral en la intensidad de píxeles de la parte de la imagen original. |
| [ToGrayscale()](#ToGrayscale) | Convierte una imagen a escala de grises. |
| [add(PreprocessingFilter filter)](#add-com.aspose.ocr.PreprocessingFilter) | Añade el nuevo filtro a la colección para ejecutar todas las operaciones. |
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


Permite el uso de una red neuronal adicional para mejorar la imagen - reducir el ruido. Útil para imágenes con artefactos de escaneo, distorsión, manchas, destellos, gradientes, elementos extraños.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDenoising(Rectangle area) {#AutoDenoising-java.awt.Rectangle}
```
public static PreprocessingFilter AutoDenoising(Rectangle area)
```


Permite el uso de una red neuronal adicional para mejorar la parte de la imagen - reducir el ruido. Útil para imágenes con artefactos de escaneo, distorsión, manchas, destellos, gradientes, elementos extraños.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| área | java.awt.Rectangle | Rectangle para preprocesar. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDewarping() {#AutoDewarping}
```
public static PreprocessingFilter AutoDewarping()
```


Corrige automáticamente las distorsiones geométricas en la imagen. ¡Extremadamente intensivo en recursos!

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDewarpingFilter object.
### AutoSkew() {#AutoSkew}
```
public static PreprocessingFilter AutoSkew()
```


Permite la corrección automática de la inclinación de la imagen.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### AutoSkew(Rectangle area) {#AutoSkew-java.awt.Rectangle}
```
public static PreprocessingFilter AutoSkew(Rectangle area)
```


Permite la corrección automática de la inclinación de la parte de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| área | java.awt.Rectangle | Rectangle para preprocesar. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### Binarize() {#Binarize}
```
public static PreprocessingFilter Binarize()
```


Convierte una imagen a blanco y negro. Las imágenes binarias son imágenes cuyos píxeles solo tienen dos valores de intensidad posibles. Normalmente se muestran en blanco y negro. Numéricamente, los dos valores suelen ser 0 para negro y 255 para blanco. Las imágenes binarias se generan mediante umbralado automático de una imagen.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Binarize(Rectangle area) {#Binarize-java.awt.Rectangle}
```
public static PreprocessingFilter Binarize(Rectangle area)
```


Convierte una parte de la imagen a blanco y negro. Las imágenes binarias son imágenes cuyos píxeles solo tienen dos valores de intensidad posibles. Normalmente se muestran en blanco y negro. Numéricamente, los dos valores suelen ser 0 para negro y 255 para blanco. Las imágenes binarias se generan mediante umbralado automático de una imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| área | java.awt.Rectangle | Rectangle para preprocesar. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### BinarizeAndDilate() {#BinarizeAndDilate}
```
public static PreprocessingFilter BinarizeAndDilate()
```


La dilatación agrega píxeles a los bordes de los objetos en una imagen.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### BinarizeAndDilate(Rectangle area) {#BinarizeAndDilate-java.awt.Rectangle}
```
public static PreprocessingFilter BinarizeAndDilate(Rectangle area)
```


La dilatación agrega píxeles a los bordes de los objetos en una parte de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| área | java.awt.Rectangle | Rectangle para preprocesar. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### ContrastCorrection() {#ContrastCorrection}
```
public static PreprocessingFilter ContrastCorrection()
```


Filtro de corrección de contraste.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### ContrastCorrection(Rectangle area) {#ContrastCorrection-java.awt.Rectangle}
```
public static PreprocessingFilter ContrastCorrection(Rectangle area)
```


Filtro de corrección de contraste para la parte de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| área | java.awt.Rectangle | Rectangle para preprocesar. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### Invert() {#Invert}
```
public static PreprocessingFilter Invert()
```


Invierte automáticamente los colores en una imagen de documento.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Invert(Rectangle area) {#Invert-java.awt.Rectangle}
```
public static PreprocessingFilter Invert(Rectangle area)
```


Invierte automáticamente los colores en una parte de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| área | java.awt.Rectangle | Rectangle para preprocesar. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Median() {#Median}
```
public static PreprocessingFilter Median()
```


El filtro mediano recorre cada elemento de la imagen y reemplaza cada píxel con la mediana de sus píxeles vecinos.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Median(Rectangle area) {#Median-java.awt.Rectangle}
```
public static PreprocessingFilter Median(Rectangle area)
```


El filtro mediano recorre cada elemento de la parte de la imagen y reemplaza cada píxel con la mediana de sus píxeles vecinos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| área | java.awt.Rectangle | Rectangle para preprocesar. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Resize(int width, int height) {#Resize-int-int}
```
public static PreprocessingFilter Resize(int width, int height)
```


Reescalar imagen - Aumentar o reducir la resolución de la imagen. InterpolationFilterType = bilinear o vecino más cercano @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El nuevo ancho de la imagen. |
| height | int | El nuevo alto de la imagen. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Resize(int width, int height, InterpolationFilterType type) {#Resize-int-int-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Resize(int width, int height, InterpolationFilterType type)
```


Reescalar imagen - aumentar o reducir la resolución de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El nuevo ancho de la imagen. |
| height | int | El nuevo alto de la imagen. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Rotate(float angle) {#Rotate-float}
```
public static PreprocessingFilter Rotate(float angle)
```


Rotar la imagen original.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ángulo | float | Ángulo de rotación. Valor de -360 a 360. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Rotate(float angle, Rectangle area) {#Rotate-float-java.awt.Rectangle}
```
public static PreprocessingFilter Rotate(float angle, Rectangle area)
```


Rotar la parte de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ángulo | float | Ángulo de rotación. Valor de -360 a 360. |
| área | java.awt.Rectangle | Rectangle para preprocesar. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Scale(float ratio) {#Scale-float}
```
public static PreprocessingFilter Scale(float ratio)
```


Reescalar imagen - Aumentar o reducir la resolución de la imagen. InterpolationFilterType predeterminado bilineal o vecino más cercano @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| relación | float | El factor de escala. Valor recomendado de 0.1 a 1 para reducir. De 1 a 10 para ampliar. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Scale(float ratio, InterpolationFilterType type) {#Scale-float-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Scale(float ratio, InterpolationFilterType type)
```


Reescalar imagen - Aumentar o reducir la resolución de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| relación | float | El factor de escala. Valor recomendado de 0.1 a 1 para reducir. De 1 a 10 para ampliar. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Threshold(int value) {#Threshold-int}
```
public static PreprocessingFilter Threshold(int value)
```


Crear una imagen binaria basándose en establecer un valor de umbral en la intensidad de píxeles de la imagen original.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El valor máximo. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Threshold(int value, Rectangle area) {#Threshold-int-java.awt.Rectangle}
```
public static PreprocessingFilter Threshold(int value, Rectangle area)
```


Crear una parte de imagen binaria basándose en establecer un valor de umbral en la intensidad de píxeles de la parte de la imagen original.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El valor máximo. |
| área | java.awt.Rectangle | Rectangle para preprocesar. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### ToGrayscale() {#ToGrayscale}
```
public static PreprocessingFilter ToGrayscale()
```


Convierte una imagen a una imagen en escala de grises. La imagen en escala de grises tiene 256 niveles de luz en la imagen (0 a 255).

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - GrayscaleFilter object.
### add(PreprocessingFilter filter) {#add-com.aspose.ocr.PreprocessingFilter}
```
public void add(PreprocessingFilter filter)
```


Agrega el nuevo filtro a la colección para ejecutar todas las operaciones posteriormente. La consistencia en la colección es importante.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filter | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Nueva operación para agregar a la lista de filtros. |

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

