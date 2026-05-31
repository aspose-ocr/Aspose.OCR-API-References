---
title: "OcrInput"
second_title: "Aspose.OCR für Java API-Referenz"
description: "Hauptklasse zum Erkennen von Text aus Bildern"
type: docs
weight: 20
url: /de/java/com.aspose.ocr/ocrinput/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class OcrInput implements Iterable<ImageData>
```

Hauptklasse zum Erkennen von Text aus Bildern.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OcrInput(InputType type, PreprocessingFilter filters)](#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter) | Konstruktor zum Erstellen eines Containers und zum Festlegen des Typs von Bildern/Dokumenten sowie Filtern für die weitere Verarbeitung/Erkennung. |
| [OcrInput(InputType type)](#OcrInput-com.aspose.ocr.InputType) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add(int[] pixels, int width, int height, int bitsPerPixel)](#add-int---int-int-int) | Fügt das dekodierte Bild der Liste zur Erkennung/Verarbeitung hinzu. |
| [add(BufferedImage image)](#add-java.awt.image.BufferedImage) | Fügt das BufferedImage, das das Bild zur Erkennung/Verarbeitung enthält, hinzu. |
| [add(BufferedImage image, int startPage, int pagesCount)](#add-java.awt.image.BufferedImage-int-int) | Fügt das BufferedImage, das das mehrseitige Bild zur Erkennung/Verarbeitung enthält, hinzu. |
| [add(InputStream stream)](#add-java.io.InputStream) | Fügt den InputStream, der das Bild zur Erkennung/Verarbeitung enthält, hinzu. |
| [add(InputStream stream, int startPage, int pagesCount)](#add-java.io.InputStream-int-int) | Fügt den InputStream, der das mehrseitige Bild zur Erkennung/Verarbeitung enthält, hinzu. |
| [add(String fullPath)](#add-java.lang.String) | Fügt den Pfad oder die URI hinzu, die das Bild zur Erkennung/Verarbeitung enthält. |
| [add(String fullPath, int startPage, int pagesCount)](#add-java.lang.String-int-int) | Fügt die mehrseitigen Bilder/Dokumente zur Erkennung/Verarbeitung hinzu. |
| [addBase64(String base64)](#addBase64-java.lang.String) | Fügt die Base64-Zeichenkette hinzu, die das Bild zur Erkennung/Verarbeitung enthält. |
| [clear()](#clear) | Setzt die Anzahl der Elemente für Verarbeitung/Erkennung auf 0. |
| [clearFilters()](#clearFilters) | Alle Filter entfernen. |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [get(int index)](#get-int) | Gibt Informationen über das verarbeitete / erkannte Bild zurück. |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [iterator()](#iterator) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [replaceFilters(PreprocessingFilter filters)](#replaceFilters-com.aspose.ocr.PreprocessingFilter) | Alte Filter entfernen und neue festlegen. |
| [size()](#size) | Anzahl der Elemente für Verarbeitung / Erkennung. |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OcrInput(InputType type, PreprocessingFilter filters) {#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter}
```
public OcrInput(InputType type, PreprocessingFilter filters)
```


Konstruktor zum Erstellen eines Containers und zum Festlegen des Typs von Bildern/Dokumenten sowie Filtern für die weitere Verarbeitung/Erkennung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) | Legen Sie den Typ der Bilder/Dokumente fest, der dem Container hinzugefügt wird. |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Verarbeitungsfilter festlegen, die für die weitere Verarbeitung oder Erkennung angewendet werden. |

### OcrInput(InputType type) {#OcrInput-com.aspose.ocr.InputType}
```
public OcrInput(InputType type)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) |  |

### add(int[] pixels, int width, int height, int bitsPerPixel) {#add-int---int-int-int}
```
public void add(int[] pixels, int width, int height, int bitsPerPixel)
```


Fügen Sie das dekodierte Bild der Liste für Erkennung / Verarbeitung hinzu. Der Bildtyp muss dem im Konstruktor angegebenen Typ entsprechen (SingleImage).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pixel | int[] | Die Pixel werden als 32‑Bit‑Ganzzahlwerte (rgb) dargestellt. |
| Breite | int | Bildbreite. |
| Höhe | int | Bildhöhe. |
| bitsPerPixel | int | Unterstützt 1‑32 Bit. |

### add(BufferedImage image) {#add-java.awt.image.BufferedImage}
```
public void add(BufferedImage image)
```


Fügen Sie das BufferedImage, das das Bild für Erkennung / Verarbeitung enthält, hinzu. Der Bildtyp muss dem im Konstruktor angegebenen Typ entsprechen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bild | java.awt.image.BufferedImage | BufferedImage, das das Bild oder Dokument enthält. |

### add(BufferedImage image, int startPage, int pagesCount) {#add-java.awt.image.BufferedImage-int-int}
```
public void add(BufferedImage image, int startPage, int pagesCount)
```


Fügen Sie das BufferedImage, das das mehrseitige Bild für Erkennung / Verarbeitung enthält, hinzu. Der Bildtyp muss dem im Konstruktor angegebenen Typ entsprechen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bild | java.awt.image.BufferedImage | BufferedImage, das das mehrseitige Dokument enthält. |
| startPage | int | Die erste Seite/das erste Bild für Verarbeitung / Erkennung. Für Dokumente verwenden. |
| pagesCount | int | Die Gesamtanzahl der Seiten/Bilder für Verarbeitung / Erkennung. Für Dokumente verwenden. Standard = alle. |

### add(InputStream stream) {#add-java.io.InputStream}
```
public void add(InputStream stream)
```


Fügen Sie den InputStream, der das Bild für Erkennung / Verarbeitung enthält, hinzu. Der Bildtyp muss dem im Konstruktor angegebenen Typ entsprechen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | InputStream, der das Bild oder Dokument enthält. |

### add(InputStream stream, int startPage, int pagesCount) {#add-java.io.InputStream-int-int}
```
public void add(InputStream stream, int startPage, int pagesCount)
```


Fügen Sie den InputStream hinzu, der das mehrseitige Bild für die Erkennung / Verarbeitung enthält. Der Bildtyp muss dem im Konstruktor angegebenen Typ entsprechen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | InputStream, der das mehrseitige Dokument enthält. |
| startPage | int | Die erste Seite/das erste Bild für Verarbeitung / Erkennung. Für Dokumente verwenden. |
| pagesCount | int | Die Gesamtanzahl der Seiten/Bilder für Verarbeitung / Erkennung. Für Dokumente verwenden. Standard = alle. |

### add(String fullPath) {#add-java.lang.String}
```
public void add(String fullPath)
```


Fügen Sie den Pfad oder die URI hinzu, die das Bild für die Erkennung / Verarbeitung enthält. Der Bildtyp muss dem im Konstruktor angegebenen Typ entsprechen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullPath | java.lang.String | Pfad zum Bild/Dokument/Ordner/Archiv. |

### add(String fullPath, int startPage, int pagesCount) {#add-java.lang.String-int-int}
```
public void add(String fullPath, int startPage, int pagesCount)
```


Fügen Sie die mehrseitigen Bilder/Dokumente für die Erkennung / Verarbeitung hinzu. Der Bildtyp muss dem im Konstruktor angegebenen Typ entsprechen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullPath | java.lang.String | Pfad zum Bild/Dokument/Ordner/Archiv. |
| startPage | int | Die erste Seite/das erste Bild für die Verarbeitung / Erkennung. Verwenden Sie es für Dokumente, ZIP-Dateien, Ordner. |
| pagesCount | int | Die Gesamtanzahl der Seiten/Bilder für die Verarbeitung / Erkennung. Verwenden Sie es für Dokumente, ZIP-Dateien, Ordner. Standard = alle. |

### addBase64(String base64) {#addBase64-java.lang.String}
```
public void addBase64(String base64)
```


Fügen Sie die Base64-Zeichenkette hinzu, die das Bild für die Erkennung / Verarbeitung enthält. Der Bildtyp muss dem im Konstruktor angegebenen Typ entsprechen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| base64 | java.lang.String | Base64-Zeichenkette mit einem einzelnen Bild. |

### clear() {#clear}
```
public void clear()
```


Setzen Sie die Anzahl der Elemente für die Verarbeitung / Erkennung auf 0. Leeren Sie die Sammlung.

### clearFilters() {#clearFilters}
```
public void clearFilters()
```


Alle Filter entfernen.

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
### get(int index) {#get-int}
```
public ImageData get(int index)
```


Gibt Informationen über das verarbeitete / erkannte Bild zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int | Position des Bildes in der Liste. |

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


Alte Filter entfernen und neue festlegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Verarbeitungsfilter werden für die weitere Verarbeitung oder Erkennung angewendet. |

### size() {#size}
```
public int size()
```


Anzahl der Elemente für Verarbeitung / Erkennung.

**Returns:**
int – Anzahl der Elemente.
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

