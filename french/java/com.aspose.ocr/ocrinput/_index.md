---
title: "OcrInput"
second_title: "Référence API d'Aspose.OCR pour Java"
description: "Classe principale pour reconnaître le texte à partir d'images."
type: docs
weight: 20
url: /fr/java/com.aspose.ocr/ocrinput/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class OcrInput implements Iterable<ImageData>
```

Classe principale pour reconnaître du texte à partir d'images.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OcrInput(InputType type, PreprocessingFilter filters)](#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter) | Constructeur pour créer le conteneur et définir le type d'images / documents ainsi que les filtres pour le traitement / la reconnaissance ultérieurs. |
| [OcrInput(InputType type)](#OcrInput-com.aspose.ocr.InputType) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(int[] pixels, int width, int height, int bitsPerPixel)](#add-int---int-int-int) | Ajoute l'image décodée à la liste pour la reconnaissance / le traitement. |
| [add(BufferedImage image)](#add-java.awt.image.BufferedImage) | Ajoute le BufferedImage contenant l'image pour la reconnaissance / le traitement. |
| [add(BufferedImage image, int startPage, int pagesCount)](#add-java.awt.image.BufferedImage-int-int) | Ajoute le BufferedImage contenant l'image multipage pour la reconnaissance / le traitement. |
| [add(InputStream stream)](#add-java.io.InputStream) | Ajoute l'InputStream contenant l'image pour la reconnaissance / le traitement. |
| [add(InputStream stream, int startPage, int pagesCount)](#add-java.io.InputStream-int-int) | Ajoute l'InputStream contenant l'image multipage pour la reconnaissance / le traitement. |
| [add(String fullPath)](#add-java.lang.String) | Ajoute le chemin ou l'URI contenant l'image pour la reconnaissance / le traitement. |
| [add(String fullPath, int startPage, int pagesCount)](#add-java.lang.String-int-int) | Ajoute les images / documents multipages pour la reconnaissance / le traitement. |
| [addBase64(String base64)](#addBase64-java.lang.String) | Ajoute la chaîne base64 contenant l'image pour la reconnaissance / le traitement. |
| [clear()](#clear) | Définit le nombre d'éléments à traiter / reconnaître à 0. |
| [clearFilters()](#clearFilters) | Supprimez tous les filtres. |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [get(int index)](#get-int) | Renvoie des informations sur l'image traitée / reconnue. |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [iterator()](#iterator) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [replaceFilters(PreprocessingFilter filters)](#replaceFilters-com.aspose.ocr.PreprocessingFilter) | Supprimez les anciens filtres et définissez‑en de nouveaux. |
| [size()](#size) | Nombre d'éléments pour le traitement / la reconnaissance. |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OcrInput(InputType type, PreprocessingFilter filters) {#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter}
```
public OcrInput(InputType type, PreprocessingFilter filters)
```


Constructeur pour créer le conteneur et définir le type d'images / documents ainsi que les filtres pour le traitement / la reconnaissance ultérieurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) | Définissez le type d'images/documents qui sera ajouté au conteneur. |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Définissez les filtres de traitement qui seront appliqués pour le traitement ou la reconnaissance ultérieurs. |

### OcrInput(InputType type) {#OcrInput-com.aspose.ocr.InputType}
```
public OcrInput(InputType type)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) |  |

### add(int[] pixels, int width, int height, int bitsPerPixel) {#add-int---int-int-int}
```
public void add(int[] pixels, int width, int height, int bitsPerPixel)
```


Ajoutez l'image décodée à la liste pour la reconnaissance / le traitement. Le type de l'image doit correspondre au type spécifié dans le constructeur (SingleImage).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | int[] | Les pixels sont représentés sous forme de valeurs entières 32 bits (rgb). |
| largeur | int | Largeur de l'image. |
| hauteur | int | Hauteur de l'image. |
| bitsPerPixel | int | Prend en charge 1 à 32 bits. |

### add(BufferedImage image) {#add-java.awt.image.BufferedImage}
```
public void add(BufferedImage image)
```


Ajoutez le BufferedImage contenant l'image pour la reconnaissance / le traitement. Le type de l'image doit correspondre au type spécifié dans le constructeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | BufferedImage contenant l'image ou le document. |

### add(BufferedImage image, int startPage, int pagesCount) {#add-java.awt.image.BufferedImage-int-int}
```
public void add(BufferedImage image, int startPage, int pagesCount)
```


Ajoutez le BufferedImage contenant l'image multipage pour la reconnaissance / le traitement. Le type de l'image doit correspondre au type spécifié dans le constructeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | BufferedImage contenant le document multipage. |
| startPage | int | Première page/image pour le traitement / la reconnaissance. À utiliser pour les documents. |
| pagesCount | int | Nombre total de pages/images pour le traitement / la reconnaissance. À utiliser pour les documents. Par défaut = toutes. |

### add(InputStream stream) {#add-java.io.InputStream}
```
public void add(InputStream stream)
```


Ajoutez le InputStream contenant l'image pour la reconnaissance / le traitement. Le type de l'image doit correspondre au type spécifié dans le constructeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream contenant l'image ou le document. |

### add(InputStream stream, int startPage, int pagesCount) {#add-java.io.InputStream-int-int}
```
public void add(InputStream stream, int startPage, int pagesCount)
```


Ajoutez l'InputStream contenant l'image multipage pour la reconnaissance / le traitement. Le type de l'image doit correspondre au type spécifié dans le constructeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream contenant le document multipage. |
| startPage | int | Première page/image pour le traitement / la reconnaissance. À utiliser pour les documents. |
| pagesCount | int | Nombre total de pages/images pour le traitement / la reconnaissance. À utiliser pour les documents. Par défaut = toutes. |

### add(String fullPath) {#add-java.lang.String}
```
public void add(String fullPath)
```


Ajoutez le chemin ou l'URI contenant l'image pour la reconnaissance / le traitement. Le type de l'image doit correspondre au type spécifié dans le constructeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullPath | java.lang.String | Chemin vers l'image / le document / le dossier / l'archive. |

### add(String fullPath, int startPage, int pagesCount) {#add-java.lang.String-int-int}
```
public void add(String fullPath, int startPage, int pagesCount)
```


Ajoutez les images / documents multipages pour la reconnaissance / le traitement. Le type de l'image doit correspondre au type spécifié dans le constructeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullPath | java.lang.String | Chemin vers l'image / le document / le dossier / l'archive. |
| startPage | int | Première page/image pour le traitement / la reconnaissance. À utiliser pour les documents, zip, dossiers. |
| pagesCount | int | Nombre total de pages/images pour le traitement / la reconnaissance. À utiliser pour les documents, zip, dossiers. Par défaut = tous. |

### addBase64(String base64) {#addBase64-java.lang.String}
```
public void addBase64(String base64)
```


Ajoutez la chaîne base64 contenant l'image pour la reconnaissance / le traitement. Le type de l'image doit correspondre au type spécifié dans le constructeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| base64 | java.lang.String | Chaîne Base64 avec une seule image. |

### clear() {#clear}
```
public void clear()
```


Définissez le nombre d'éléments pour le traitement / la reconnaissance à 0. Videz la collection.

### clearFilters() {#clearFilters}
```
public void clearFilters()
```


Supprimez tous les filtres.

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int}
```
public ImageData get(int index)
```


Renvoie des informations sur l'image traitée / reconnue.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Position de l'image dans la List. |

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


Supprimez les anciens filtres et définissez‑en de nouveaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Des filtres de traitement seront appliqués pour le traitement ou la reconnaissance ultérieurs. |

### size() {#size}
```
public int size()
```


Nombre d'éléments pour le traitement / la reconnaissance.

**Returns:**
int - Nombre d'éléments.
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

