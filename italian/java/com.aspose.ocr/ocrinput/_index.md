---
title: "OcrInput"
second_title: "Riferimento API di Aspose.OCR per Java"
description: "Classe principale per riconoscere il testo dalle immagini"
type: docs
weight: 20
url: /it/java/com.aspose.ocr/ocrinput/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class OcrInput implements Iterable<ImageData>
```

Classe principale per riconoscere il testo dalle immagini.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OcrInput(InputType type, PreprocessingFilter filters)](#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter) | Costruttore per creare il contenitore e impostare il tipo di immagini / documenti e filtri per l'ulteriore elaborazione / riconoscimento. |
| [OcrInput(InputType type)](#OcrInput-com.aspose.ocr.InputType) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(int[] pixels, int width, int height, int bitsPerPixel)](#add-int---int-int-int) | Aggiungi l'immagine decodificata all'elenco per il riconoscimento / elaborazione. |
| [add(BufferedImage image)](#add-java.awt.image.BufferedImage) | Aggiungi il BufferedImage contenente l'immagine per il riconoscimento / elaborazione. |
| [add(BufferedImage image, int startPage, int pagesCount)](#add-java.awt.image.BufferedImage-int-int) | Aggiungi il BufferedImage contenente l'immagine multipagina per il riconoscimento / elaborazione. |
| [add(InputStream stream)](#add-java.io.InputStream) | Aggiungi l'InputStream contenente l'immagine per il riconoscimento / elaborazione. |
| [add(InputStream stream, int startPage, int pagesCount)](#add-java.io.InputStream-int-int) | Aggiungi l'InputStream contenente l'immagine multipagina per il riconoscimento / elaborazione. |
| [add(String fullPath)](#add-java.lang.String) | Aggiungi il percorso o l'URI contenente l'immagine per il riconoscimento / elaborazione. |
| [add(String fullPath, int startPage, int pagesCount)](#add-java.lang.String-int-int) | Aggiungi le immagini / documenti multipagina per il riconoscimento / elaborazione. |
| [addBase64(String base64)](#addBase64-java.lang.String) | Aggiungi la stringa base64 contenente l'immagine per il riconoscimento / elaborazione. |
| [clear()](#clear) | Imposta la quantità di elementi per l'elaborazione / riconoscimento a 0. |
| [clearFilters()](#clearFilters) | Rimuovi tutti i filtri. |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [get(int index)](#get-int) | Restituisce informazioni sull'immagine elaborata / riconosciuta. |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [iterator()](#iterator) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [replaceFilters(PreprocessingFilter filters)](#replaceFilters-com.aspose.ocr.PreprocessingFilter) | Rimuovi i filtri vecchi e impostane di nuovi. |
| [size()](#size) | Numero di elementi per l'elaborazione / riconoscimento. |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OcrInput(InputType type, PreprocessingFilter filters) {#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter}
```
public OcrInput(InputType type, PreprocessingFilter filters)
```


Costruttore per creare il contenitore e impostare il tipo di immagini / documenti e filtri per l'ulteriore elaborazione / riconoscimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) | Imposta il tipo di immagini/documenti che verrà aggiunto al contenitore. |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Imposta i filtri di elaborazione che verranno applicati per ulteriori elaborazioni o riconoscimenti. |

### OcrInput(InputType type) {#OcrInput-com.aspose.ocr.InputType}
```
public OcrInput(InputType type)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) |  |

### add(int[] pixels, int width, int height, int bitsPerPixel) {#add-int---int-int-int}
```
public void add(int[] pixels, int width, int height, int bitsPerPixel)
```


Aggiungi l'immagine decodificata all'elenco per il riconoscimento / l'elaborazione. Il tipo dell'immagine deve corrispondere al tipo specificato nel costruttore (SingleImage).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | int[] | I pixel sono rappresentati come valori interi a 32 bit (rgb). |
| larghezza | int | Larghezza immagine. |
| altezza | int | Altezza immagine. |
| bitsPerPixel | int | Supporta da 1 a 32 bit. |

### add(BufferedImage image) {#add-java.awt.image.BufferedImage}
```
public void add(BufferedImage image)
```


Aggiungi il BufferedImage contenente l'immagine per il riconoscimento / l'elaborazione. Il tipo dell'immagine deve corrispondere al tipo specificato nel costruttore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| immagine | java.awt.image.BufferedImage | BufferedImage contenente l'immagine o il documento. |

### add(BufferedImage image, int startPage, int pagesCount) {#add-java.awt.image.BufferedImage-int-int}
```
public void add(BufferedImage image, int startPage, int pagesCount)
```


Aggiungi il BufferedImage contenente l'immagine multipagina per il riconoscimento / l'elaborazione. Il tipo dell'immagine deve corrispondere al tipo specificato nel costruttore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| immagine | java.awt.image.BufferedImage | BufferedImage contenente il documento multipagina. |
| startPage | int | La prima pagina/immagine per l'elaborazione / riconoscimento. Da usare per i documenti. |
| pagesCount | int | Il numero totale di pagine/immagini per l'elaborazione / riconoscimento. Da usare per i documenti. Predefinito = tutte. |

### add(InputStream stream) {#add-java.io.InputStream}
```
public void add(InputStream stream)
```


Aggiungi l'InputStream contenente l'immagine per il riconoscimento / l'elaborazione. Il tipo dell'immagine deve corrispondere al tipo specificato nel costruttore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream contenente l'immagine o il documento. |

### add(InputStream stream, int startPage, int pagesCount) {#add-java.io.InputStream-int-int}
```
public void add(InputStream stream, int startPage, int pagesCount)
```


Aggiungi l'InputStream contenente l'immagine multipagina per il riconoscimento / l'elaborazione. Il tipo dell'immagine deve corrispondere al tipo specificato nel costruttore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream contenente il documento multipagina. |
| startPage | int | La prima pagina/immagine per l'elaborazione / riconoscimento. Da usare per i documenti. |
| pagesCount | int | Il numero totale di pagine/immagini per l'elaborazione / riconoscimento. Da usare per i documenti. Predefinito = tutte. |

### add(String fullPath) {#add-java.lang.String}
```
public void add(String fullPath)
```


Aggiungi il percorso o l'URI contenente l'immagine per il riconoscimento / l'elaborazione. Il tipo dell'immagine deve corrispondere al tipo specificato nel costruttore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullPath | java.lang.String | Percorso verso l'immagine/ documento / cartella / archivio. |

### add(String fullPath, int startPage, int pagesCount) {#add-java.lang.String-int-int}
```
public void add(String fullPath, int startPage, int pagesCount)
```


Aggiungi le immagini / i documenti multipagina per il riconoscimento / l'elaborazione. Il tipo dell'immagine deve corrispondere al tipo specificato nel costruttore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullPath | java.lang.String | Percorso verso l'immagine/ documento / cartella / archivio. |
| startPage | int | La prima pagina/immagine per l'elaborazione / il riconoscimento. Da usare per documenti, zip, cartelle. |
| pagesCount | int | Il numero totale di pagine/immagini per l'elaborazione / il riconoscimento. Da usare per documenti, zip, cartelle. Predefinito = tutti. |

### addBase64(String base64) {#addBase64-java.lang.String}
```
public void addBase64(String base64)
```


Aggiungi la stringa base64 contenente l'immagine per il riconoscimento / l'elaborazione. Il tipo dell'immagine deve corrispondere al tipo specificato nel costruttore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| base64 | java.lang.String | Stringa Base64 con immagine singola. |

### clear() {#clear}
```
public void clear()
```


Imposta il numero di elementi per l'elaborazione / il riconoscimento a 0. Svuota la collezione.

### clearFilters() {#clearFilters}
```
public void clearFilters()
```


Rimuovi tutti i filtri.

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
### get(int index) {#get-int}
```
public ImageData get(int index)
```


Restituisce informazioni sull'immagine elaborata / riconosciuta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione dell'immagine nella Lista. |

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


Rimuovi i filtri vecchi e impostane di nuovi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | I filtri di elaborazione saranno applicati per ulteriori elaborazioni o riconoscimenti. |

### size() {#size}
```
public int size()
```


Numero di elementi per l'elaborazione / riconoscimento.

**Returns:**
int - Numero di elementi.
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

