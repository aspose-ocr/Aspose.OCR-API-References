---
title: "OcrInput"
second_title: "Aspose.OCR för Java API-referens"
description: "Huvudklass för att känna igen text från bilder"
type: docs
weight: 20
url: /sv/java/com.aspose.ocr/ocrinput/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class OcrInput implements Iterable<ImageData>
```

Huvudklass för att känna igen text från bilder.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [OcrInput(InputType type, PreprocessingFilter filters)](#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter) | Konstruktör för att skapa en behållare och ange typen av bilder / dokument samt filter för vidare bearbetning / igenkänning. |
| [OcrInput(InputType type)](#OcrInput-com.aspose.ocr.InputType) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add(int[] pixels, int width, int height, int bitsPerPixel)](#add-int---int-int-int) | Lägg till den avkodade bilden i listan för igenkänning / bearbetning. |
| [add(BufferedImage image)](#add-java.awt.image.BufferedImage) | Lägg till BufferedImage som innehåller bilden för igenkänning / bearbetning. |
| [add(BufferedImage image, int startPage, int pagesCount)](#add-java.awt.image.BufferedImage-int-int) | Lägg till BufferedImage som innehåller flersidig bild för igenkänning / bearbetning. |
| [add(InputStream stream)](#add-java.io.InputStream) | Lägg till InputStream som innehåller bilden för igenkänning / bearbetning. |
| [add(InputStream stream, int startPage, int pagesCount)](#add-java.io.InputStream-int-int) | Lägg till InputStream som innehåller flersidig bild för igenkänning / bearbetning. |
| [add(String fullPath)](#add-java.lang.String) | Lägg till sökvägen eller URI som innehåller bilden för igenkänning / bearbetning. |
| [add(String fullPath, int startPage, int pagesCount)](#add-java.lang.String-int-int) | Lägg till de flersidiga bilderna / dokumenten för igenkänning / bearbetning. |
| [addBase64(String base64)](#addBase64-java.lang.String) | Lägg till base64-strängen som innehåller bilden för igenkänning / bearbetning. |
| [clear()](#clear) | Ställ in antalet objekt för bearbetning / igenkänning till 0. |
| [clearFilters()](#clearFilters) | Ta bort alla filter. |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [get(int index)](#get-int) | Returnerar information om bearbetad / igenkänd bild. |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [iterator()](#iterator) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [replaceFilters(PreprocessingFilter filters)](#replaceFilters-com.aspose.ocr.PreprocessingFilter) | Ta bort gamla filter och ställ in nya. |
| [size()](#size) | Antal objekt för bearbetning / igenkänning. |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OcrInput(InputType type, PreprocessingFilter filters) {#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter}
```
public OcrInput(InputType type, PreprocessingFilter filters)
```


Konstruktör för att skapa en behållare och ange typen av bilder / dokument samt filter för vidare bearbetning / igenkänning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) | Ange vilken typ av bilder/dokument som ska läggas till i behållaren. |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Ange bearbetningsfilter som kommer att tillämpas för vidare bearbetning eller igenkänning. |

### OcrInput(InputType type) {#OcrInput-com.aspose.ocr.InputType}
```
public OcrInput(InputType type)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) |  |

### add(int[] pixels, int width, int height, int bitsPerPixel) {#add-int---int-int-int}
```
public void add(int[] pixels, int width, int height, int bitsPerPixel)
```


Lägg till den avkodade bilden i listan för igenkänning / bearbetning. Bildens typ måste motsvara den typ som anges i konstruktorn (SingleImage).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixlar | int[] | Pixlarna representeras som 32-bitars heltalsvärden (rgb). |
| bredd | int | Bildbredd. |
| höjd | int | Bildhöjd. |
| bitsPerPixel | int | Stöder 1-32 bitar. |

### add(BufferedImage image) {#add-java.awt.image.BufferedImage}
```
public void add(BufferedImage image)
```


Lägg till BufferedImage som innehåller bilden för igenkänning / bearbetning. Bildens typ måste motsvara den typ som anges i konstruktorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | java.awt.image.BufferedImage | BufferedImage som innehåller bilden eller dokumentet. |

### add(BufferedImage image, int startPage, int pagesCount) {#add-java.awt.image.BufferedImage-int-int}
```
public void add(BufferedImage image, int startPage, int pagesCount)
```


Lägg till BufferedImage som innehåller flersidig bild för igenkänning / bearbetning. Bildens typ måste motsvara den typ som anges i konstruktorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | java.awt.image.BufferedImage | BufferedImage som innehåller det flersidiga dokumentet. |
| startPage | int | Den första sidan/bilden för bearbetning / igenkänning. Använd för dokument. |
| pagesCount | int | Det totala antalet sidor/bilder för bearbetning / igenkänning. Använd för dokument. Standard = alla. |

### add(InputStream stream) {#add-java.io.InputStream}
```
public void add(InputStream stream)
```


Lägg till InputStream som innehåller bilden för igenkänning / bearbetning. Bildens typ måste motsvara den typ som anges i konstruktorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream som innehåller bilden eller dokumentet. |

### add(InputStream stream, int startPage, int pagesCount) {#add-java.io.InputStream-int-int}
```
public void add(InputStream stream, int startPage, int pagesCount)
```


Lägg till InputStream som innehåller flersidig bild för igenkänning / bearbetning. Bildens typ måste motsvara den typ som anges i konstruktorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream som innehåller flersidigt dokument. |
| startPage | int | Den första sidan/bilden för bearbetning / igenkänning. Använd för dokument. |
| pagesCount | int | Det totala antalet sidor/bilder för bearbetning / igenkänning. Använd för dokument. Standard = alla. |

### add(String fullPath) {#add-java.lang.String}
```
public void add(String fullPath)
```


Lägg till sökvägen eller URI som innehåller bilden för igenkänning / bearbetning. Bildens typ måste motsvara den typ som anges i konstruktorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullPath | java.lang.String | Sökväg till bilden/ dokumentet / mappen / arkivet. |

### add(String fullPath, int startPage, int pagesCount) {#add-java.lang.String-int-int}
```
public void add(String fullPath, int startPage, int pagesCount)
```


Lägg till flersidiga bilder / dokument för igenkänning / bearbetning. Bildens typ måste motsvara den typ som anges i konstruktorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullPath | java.lang.String | Sökväg till bilden/ dokumentet / mappen / arkivet. |
| startPage | int | Den första sidan/bilden för bearbetning / igenkänning. Använd för dokument, zip, mappar. |
| pagesCount | int | Det totala antalet sidor/bilder för bearbetning / igenkänning. Använd för dokument, zip, mappar. Standard = alla. |

### addBase64(String base64) {#addBase64-java.lang.String}
```
public void addBase64(String base64)
```


Lägg till base64-strängen som innehåller bilden för igenkänning / bearbetning. Bildens typ måste motsvara den typ som anges i konstruktorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| base64 | java.lang.String | Base64-sträng med en enda bild. |

### clear() {#clear}
```
public void clear()
```


Ställ in antalet objekt för bearbetning / igenkänning till 0. Rensa samlingen.

### clearFilters() {#clearFilters}
```
public void clearFilters()
```


Ta bort alla filter.

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
### get(int index) {#get-int}
```
public ImageData get(int index)
```


Returnerar information om bearbetad / igenkänd bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Position för bilden i listan. |

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


Ta bort gamla filter och ställ in nya.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Bearbetningsfilter kommer att tillämpas för vidare bearbetning eller igenkänning. |

### size() {#size}
```
public int size()
```


Antal objekt för bearbetning / igenkänning.

**Returns:**
int - Antal objekt.
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

