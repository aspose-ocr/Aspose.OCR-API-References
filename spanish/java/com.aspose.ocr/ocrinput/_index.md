---
title: "OcrInput"
second_title: "Referencia de API de Aspose.OCR para Java"
description: "Clase principal para reconocer texto de imágenes"
type: docs
weight: 20
url: /es/java/com.aspose.ocr/ocrinput/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class OcrInput implements Iterable<ImageData>
```

Clase principal para reconocer texto de imágenes.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OcrInput(InputType type, PreprocessingFilter filters)](#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter) | Constructor para crear el contenedor y establecer el tipo de imágenes / documentos y filtros para el procesamiento / reconocimiento posterior. |
| [OcrInput(InputType type)](#OcrInput-com.aspose.ocr.InputType) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [add(int[] pixels, int width, int height, int bitsPerPixel)](#add-int---int-int-int) | Agregar la imagen decodificada a la lista para reconocimiento / procesamiento. |
| [add(BufferedImage image)](#add-java.awt.image.BufferedImage) | Agregar el BufferedImage que contiene la imagen para reconocimiento / procesamiento. |
| [add(BufferedImage image, int startPage, int pagesCount)](#add-java.awt.image.BufferedImage-int-int) | Agregar el BufferedImage que contiene la imagen multipágina para reconocimiento / procesamiento. |
| [add(InputStream stream)](#add-java.io.InputStream) | Agregar el InputStream que contiene la imagen para reconocimiento / procesamiento. |
| [add(InputStream stream, int startPage, int pagesCount)](#add-java.io.InputStream-int-int) | Agregar el InputStream que contiene la imagen multipágina para reconocimiento / procesamiento. |
| [add(String fullPath)](#add-java.lang.String) | Agregar la ruta o URI que contiene la imagen para reconocimiento / procesamiento. |
| [add(String fullPath, int startPage, int pagesCount)](#add-java.lang.String-int-int) | Agregar las imágenes / documentos multipágina para reconocimiento / procesamiento. |
| [addBase64(String base64)](#addBase64-java.lang.String) | Agregar la cadena base64 que contiene la imagen para reconocimiento / procesamiento. |
| [clear()](#clear) | Establecer la cantidad de elementos para procesamiento / reconocimiento en 0. |
| [clearFilters()](#clearFilters) | Eliminar todos los filtros. |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [get(int index)](#get-int) | Devuelve información sobre la imagen procesada / reconocida. |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [iterator()](#iterator) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [replaceFilters(PreprocessingFilter filters)](#replaceFilters-com.aspose.ocr.PreprocessingFilter) | Eliminar filtros antiguos y establecer nuevos. |
| [size()](#size) | Cantidad de elementos para procesamiento / reconocimiento. |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OcrInput(InputType type, PreprocessingFilter filters) {#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter}
```
public OcrInput(InputType type, PreprocessingFilter filters)
```


Constructor para crear el contenedor y establecer el tipo de imágenes / documentos y filtros para el procesamiento / reconocimiento posterior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) | Establecer el tipo de imágenes/documentos que se añadirá al contenedor. |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Establecer los filtros de procesamiento que se aplicarán para un procesamiento o reconocimiento adicional. |

### OcrInput(InputType type) {#OcrInput-com.aspose.ocr.InputType}
```
public OcrInput(InputType type)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) |  |

### add(int[] pixels, int width, int height, int bitsPerPixel) {#add-int---int-int-int}
```
public void add(int[] pixels, int width, int height, int bitsPerPixel)
```


Agregar la imagen decodificada a la lista para reconocimiento / procesamiento. El tipo de la imagen debe coincidir con el tipo especificado en el constructor (SingleImage).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| píxeles | int[] | Los píxeles se representan como valores enteros de 32 bits (rgb). |
| width | int | Ancho de la imagen. |
| height | int | Altura de la imagen. |
| bitsPerPixel | int | Admite de 1 a 32 bits. |

### add(BufferedImage image) {#add-java.awt.image.BufferedImage}
```
public void add(BufferedImage image)
```


Agregar el BufferedImage que contiene la imagen para reconocimiento / procesamiento. El tipo de la imagen debe coincidir con el tipo especificado en el constructor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagen | java.awt.image.BufferedImage | BufferedImage que contiene la imagen o el documento. |

### add(BufferedImage image, int startPage, int pagesCount) {#add-java.awt.image.BufferedImage-int-int}
```
public void add(BufferedImage image, int startPage, int pagesCount)
```


Agregar el BufferedImage que contiene la imagen multipágina para reconocimiento / procesamiento. El tipo de la imagen debe coincidir con el tipo especificado en el constructor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagen | java.awt.image.BufferedImage | BufferedImage que contiene el documento multipágina. |
| startPage | int | La primera página/imagen para procesamiento / reconocimiento. Uso para documentos. |
| pagesCount | int | La cantidad total de páginas/imágenes para procesamiento / reconocimiento. Uso para documentos. Predeterminado = todas. |

### add(InputStream stream) {#add-java.io.InputStream}
```
public void add(InputStream stream)
```


Agregar el InputStream que contiene la imagen para reconocimiento / procesamiento. El tipo de la imagen debe coincidir con el tipo especificado en el constructor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream que contiene la imagen o el documento. |

### add(InputStream stream, int startPage, int pagesCount) {#add-java.io.InputStream-int-int}
```
public void add(InputStream stream, int startPage, int pagesCount)
```


Agregue el InputStream que contiene la imagen multipágina para reconocimiento / procesamiento. El tipo de la imagen debe corresponder al tipo especificado en el constructor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream que contiene el documento multipágina. |
| startPage | int | La primera página/imagen para procesamiento / reconocimiento. Uso para documentos. |
| pagesCount | int | La cantidad total de páginas/imágenes para procesamiento / reconocimiento. Uso para documentos. Predeterminado = todas. |

### add(String fullPath) {#add-java.lang.String}
```
public void add(String fullPath)
```


Agregue la ruta o URI que contiene la imagen para reconocimiento / procesamiento. El tipo de la imagen debe corresponder al tipo especificado en el constructor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullPath | java.lang.String | Ruta a la imagen/ documento / carpeta / archivo. |

### add(String fullPath, int startPage, int pagesCount) {#add-java.lang.String-int-int}
```
public void add(String fullPath, int startPage, int pagesCount)
```


Agregue las imágenes / documentos multipágina para reconocimiento / procesamiento. El tipo de la imagen debe corresponder al tipo especificado en el constructor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullPath | java.lang.String | Ruta a la imagen/ documento / carpeta / archivo. |
| startPage | int | La primera página/imagen para procesamiento / reconocimiento. Úselo para documentos, zip, carpetas. |
| pagesCount | int | La cantidad total de páginas/imágenes para procesamiento / reconocimiento. Úselo para documentos, zip, carpetas. Predeterminado = todas. |

### addBase64(String base64) {#addBase64-java.lang.String}
```
public void addBase64(String base64)
```


Agregue la cadena base64 que contiene la imagen para reconocimiento / procesamiento. El tipo de la imagen debe corresponder al tipo especificado en el constructor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| base64 | java.lang.String | Cadena Base64 con una sola imagen. |

### clear() {#clear}
```
public void clear()
```


Establezca la cantidad de elementos para procesamiento / reconocimiento en 0. Vacíe la colección.

### clearFilters() {#clearFilters}
```
public void clearFilters()
```


Eliminar todos los filtros.

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
### get(int index) {#get-int}
```
public ImageData get(int index)
```


Devuelve información sobre la imagen procesada / reconocida.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Posición de la imagen en la Lista. |

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


Eliminar filtros antiguos y establecer nuevos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Se aplicarán filtros de procesamiento para un procesamiento o reconocimiento adicional. |

### size() {#size}
```
public int size()
```


Cantidad de elementos para procesamiento / reconocimiento.

**Returns:**
int - Cantidad de elementos.
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

