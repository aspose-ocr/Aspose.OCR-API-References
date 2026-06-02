---
title: "OcrInput"
second_title: "Aspose.OCR for Java API-referentie"
description: "Hoofdklasse voor het herkennen van tekst uit afbeeldingen"
type: docs
weight: 20
url: /nl/java/com.aspose.ocr/ocrinput/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class OcrInput implements Iterable<ImageData>
```

Hoofdklasse voor het herkennen van tekst uit afbeeldingen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [OcrInput(InputType type, PreprocessingFilter filters)](#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter) | Constructor om een container te maken en het type afbeeldingen / documenten en filters in te stellen voor verdere verwerking / herkenning. |
| [OcrInput(InputType type)](#OcrInput-com.aspose.ocr.InputType) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(int[] pixels, int width, int height, int bitsPerPixel)](#add-int---int-int-int) | Voeg de gedecodeerde afbeelding toe aan de lijst voor herkenning / verwerking. |
| [add(BufferedImage image)](#add-java.awt.image.BufferedImage) | Voeg de BufferedImage toe die de afbeelding bevat voor herkenning / verwerking. |
| [add(BufferedImage image, int startPage, int pagesCount)](#add-java.awt.image.BufferedImage-int-int) | Voeg de BufferedImage toe die de meerpagina-afbeelding bevat voor herkenning / verwerking. |
| [add(InputStream stream)](#add-java.io.InputStream) | Voeg de InputStream toe die de afbeelding bevat voor herkenning / verwerking. |
| [add(InputStream stream, int startPage, int pagesCount)](#add-java.io.InputStream-int-int) | Voeg de InputStream toe die de meerpagina-afbeelding bevat voor herkenning / verwerking. |
| [add(String fullPath)](#add-java.lang.String) | Voeg het pad of de URI toe die de afbeelding bevat voor herkenning / verwerking. |
| [add(String fullPath, int startPage, int pagesCount)](#add-java.lang.String-int-int) | Voeg de meerpagina-afbeeldingen / documenten toe voor herkenning / verwerking. |
| [addBase64(String base64)](#addBase64-java.lang.String) | Voeg de base64-string toe die de afbeelding bevat voor herkenning / verwerking. |
| [clear()](#clear) | Stel het aantal items in voor verwerking / herkenning op 0. |
| [clearFilters()](#clearFilters) | Verwijder alle filters. |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [get(int index)](#get-int) | Geeft informatie over de verwerkte / herkende afbeelding. |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [iterator()](#iterator) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [replaceFilters(PreprocessingFilter filters)](#replaceFilters-com.aspose.ocr.PreprocessingFilter) | Verwijder oude filters en stel nieuwe in. |
| [size()](#size) | Aantal items voor verwerking / herkenning. |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OcrInput(InputType type, PreprocessingFilter filters) {#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter}
```
public OcrInput(InputType type, PreprocessingFilter filters)
```


Constructor om een container te maken en het type afbeeldingen / documenten en filters in te stellen voor verdere verwerking / herkenning.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) | Stel het type afbeeldingen/documenten in dat aan de container wordt toegevoegd. |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Stel verwerkingsfilters in die worden toegepast voor verdere verwerking of herkenning. |

### OcrInput(InputType type) {#OcrInput-com.aspose.ocr.InputType}
```
public OcrInput(InputType type)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) |  |

### add(int[] pixels, int width, int height, int bitsPerPixel) {#add-int---int-int-int}
```
public void add(int[] pixels, int width, int height, int bitsPerPixel)
```


Voeg de gedecodeerde afbeelding toe aan de lijst voor herkenning / verwerking. Het type van de afbeelding moet overeenkomen met het type dat is opgegeven in de constructor (SingleImage).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixels | int[] | De pixels worden weergegeven als 32-bit gehele getallen (rgb). |
| breedte | int | Afbeeldingsbreedte. |
| hoogte | int | Afbeeldingshoogte. |
| bitsPerPixel | int | Ondersteunt 1-32 bits. |

### add(BufferedImage image) {#add-java.awt.image.BufferedImage}
```
public void add(BufferedImage image)
```


Voeg de BufferedImage toe die de afbeelding bevat voor herkenning / verwerking. Het type van de afbeelding moet overeenkomen met het type dat is opgegeven in de constructor.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| afbeelding | java.awt.image.BufferedImage | BufferedImage die de afbeelding of het document bevat. |

### add(BufferedImage image, int startPage, int pagesCount) {#add-java.awt.image.BufferedImage-int-int}
```
public void add(BufferedImage image, int startPage, int pagesCount)
```


Voeg de BufferedImage toe die de meerpagina-afbeelding bevat voor herkenning / verwerking. Het type van de afbeelding moet overeenkomen met het type dat is opgegeven in de constructor.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| afbeelding | java.awt.image.BufferedImage | BufferedImage die het meerpagina-document bevat. |
| startPage | int | De eerste pagina/afbeelding voor verwerking / herkenning. Gebruik voor documenten. |
| pagesCount | int | Het totale aantal pagina's/afbeeldingen voor verwerking / herkenning. Gebruik voor documenten. Standaard = allemaal. |

### add(InputStream stream) {#add-java.io.InputStream}
```
public void add(InputStream stream)
```


Voeg de InputStream toe die de afbeelding bevat voor herkenning / verwerking. Het type van de afbeelding moet overeenkomen met het type dat is opgegeven in de constructor.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream die de afbeelding of het document bevat. |

### add(InputStream stream, int startPage, int pagesCount) {#add-java.io.InputStream-int-int}
```
public void add(InputStream stream, int startPage, int pagesCount)
```


Voeg de InputStream toe die de meerpagina-afbeelding bevat voor herkenning / verwerking. Het type van de afbeelding moet overeenkomen met het type dat in de constructor is opgegeven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream die het meerpagina-document bevat. |
| startPage | int | De eerste pagina/afbeelding voor verwerking / herkenning. Gebruik voor documenten. |
| pagesCount | int | Het totale aantal pagina's/afbeeldingen voor verwerking / herkenning. Gebruik voor documenten. Standaard = allemaal. |

### add(String fullPath) {#add-java.lang.String}
```
public void add(String fullPath)
```


Voeg het pad of de URI toe die de afbeelding bevat voor herkenning / verwerking. Het type van de afbeelding moet overeenkomen met het type dat in de constructor is opgegeven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullPath | java.lang.String | Pad naar de afbeelding / het document / de map / het archief. |

### add(String fullPath, int startPage, int pagesCount) {#add-java.lang.String-int-int}
```
public void add(String fullPath, int startPage, int pagesCount)
```


Voeg de meerpagina-afbeeldingen / documenten toe voor herkenning / verwerking. Het type van de afbeelding moet overeenkomen met het type dat in de constructor is opgegeven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullPath | java.lang.String | Pad naar de afbeelding / het document / de map / het archief. |
| startPage | int | De eerste pagina / afbeelding voor verwerking / herkenning. Gebruik voor documenten, zip, mappen. |
| pagesCount | int | Het totale aantal pagina's / afbeeldingen voor verwerking / herkenning. Gebruik voor documenten, zip, mappen. Standaard = allemaal. |

### addBase64(String base64) {#addBase64-java.lang.String}
```
public void addBase64(String base64)
```


Voeg de base64‑string toe die de afbeelding bevat voor herkenning / verwerking. Het type van de afbeelding moet overeenkomen met het type dat in de constructor is opgegeven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| base64 | java.lang.String | Base64‑string met één afbeelding. |

### clear() {#clear}
```
public void clear()
```


Stel het aantal items voor verwerking / herkenning in op 0. Maak de collectie leeg.

### clearFilters() {#clearFilters}
```
public void clearFilters()
```


Verwijder alle filters.

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
### get(int index) {#get-int}
```
public ImageData get(int index)
```


Geeft informatie over de verwerkte / herkende afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Positie van de afbeelding in de lijst. |

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


Verwijder oude filters en stel nieuwe in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Verwerkingsfilters worden toegepast voor verdere verwerking of herkenning. |

### size() {#size}
```
public int size()
```


Aantal items voor verwerking / herkenning.

**Returns:**
int - Aantal items.
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

