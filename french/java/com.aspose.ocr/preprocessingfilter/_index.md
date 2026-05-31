---
title: "PreprocessingFilter"
second_title: "Référence API d'Aspose.OCR pour Java"
description: "Classe de base pour les commandes de traitement d'image"
type: docs
weight: 24
url: /fr/java/com.aspose.ocr/preprocessingfilter/
---

**Inheritance:**
java.lang.Object
```
public class PreprocessingFilter
```

Classe de base pour les commandes de traitement d'image.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PreprocessingFilter()](#PreprocessingFilter) |  |
## Champs

| Champ | Description |
| --- | --- |
| [Empty](#Empty) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [AutoDenoising()](#AutoDenoising) | Permet l'utilisation d'un réseau neuronal supplémentaire pour améliorer l'image - réduire le bruit. |
| [AutoDenoising(Rectangle area)](#AutoDenoising-java.awt.Rectangle) | Permet l'utilisation d'un réseau neuronal supplémentaire pour améliorer la partie de l'image - réduire le bruit. |
| [AutoDewarping()](#AutoDewarping) | Corrige automatiquement les distorsions géométriques de l'image. |
| [AutoSkew()](#AutoSkew) | Active la correction automatique de l'inclinaison de l'image. |
| [AutoSkew(Rectangle area)](#AutoSkew-java.awt.Rectangle) | Active la correction automatique de l'inclinaison de la partie de l'image. |
| [Binarize()](#Binarize) | Convertit une image en image noir et blanc. |
| [Binarize(Rectangle area)](#Binarize-java.awt.Rectangle) | Convertit une partie de l'image en image noir et blanc. |
| [BinarizeAndDilate()](#BinarizeAndDilate) | La dilatation ajoute des pixels aux frontières des objets dans une image. |
| [BinarizeAndDilate(Rectangle area)](#BinarizeAndDilate-java.awt.Rectangle) | La dilatation ajoute des pixels aux frontières des objets dans une partie de l'image. |
| [ContrastCorrection()](#ContrastCorrection) | Filtre de correction de contraste. |
| [ContrastCorrection(Rectangle area)](#ContrastCorrection-java.awt.Rectangle) | Filtre de correction de contraste pour la partie de l'image. |
| [Invert()](#Invert) | Inverse automatiquement les couleurs d'une image de document. |
| [Invert(Rectangle area)](#Invert-java.awt.Rectangle) | Inverse automatiquement les couleurs dans une partie de l'image. |
| [Median()](#Median) | Le filtre médian parcourt chaque élément de l'image et remplace chaque pixel par la médiane de ses pixels voisins. |
| [Median(Rectangle area)](#Median-java.awt.Rectangle) | Le filtre médian parcourt chaque élément de la partie de l'image et remplace chaque pixel par la médiane de ses pixels voisins. |
| [Resize(int width, int height)](#Resize-int-int) | Redimensionner l'image - augmenter ou diminuer la résolution de l'image. |
| [Resize(int width, int height, InterpolationFilterType type)](#Resize-int-int-com.aspose.ocr.InterpolationFilterType) | Redimensionner l'image - augmenter ou diminuer la résolution de l'image. |
| [Rotate(float angle)](#Rotate-float) | Faire pivoter l'image originale. |
| [Rotate(float angle, Rectangle area)](#Rotate-float-java.awt.Rectangle) | Faire pivoter la partie de l'image. |
| [Scale(float ratio)](#Scale-float) | Redimensionner l'image - augmenter ou diminuer la résolution de l'image. |
| [Scale(float ratio, InterpolationFilterType type)](#Scale-float-com.aspose.ocr.InterpolationFilterType) | Redimensionner l'image - augmenter ou diminuer la résolution de l'image. |
| [Threshold(int value)](#Threshold-int) | Créer une image binaire en définissant une valeur de seuil sur l'intensité des pixels de l'image originale. |
| [Threshold(int value, Rectangle area)](#Threshold-int-java.awt.Rectangle) | Créer une partie d'image binaire en définissant une valeur de seuil sur l'intensité des pixels de la partie de l'image originale. |
| [ToGrayscale()](#ToGrayscale) | Convertit une image en image en niveaux de gris. |
| [add(PreprocessingFilter filter)](#add-com.aspose.ocr.PreprocessingFilter) | Ajoutez le nouveau filtre à la collection pour exécuter toutes les opérations ultérieurement. |
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


Permet l'utilisation d'un réseau neuronal supplémentaire pour améliorer l'image - réduire le bruit. Utile pour les images présentant des artefacts de numérisation, des distorsions, des taches, des reflets, des gradients, des éléments étrangers.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDenoising(Rectangle area) {#AutoDenoising-java.awt.Rectangle}
```
public static PreprocessingFilter AutoDenoising(Rectangle area)
```


Permet l'utilisation d'un réseau neuronal supplémentaire pour améliorer la partie de l'image - réduire le bruit. Utile pour les images présentant des artefacts de numérisation, des distorsions, des taches, des reflets, des gradients, des éléments étrangers.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| zone | java.awt.Rectangle | Rectangle à prétraiter. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDewarping() {#AutoDewarping}
```
public static PreprocessingFilter AutoDewarping()
```


Corrige automatiquement les distorsions géométriques de l'image. Extrêmement gourmand en ressources !

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDewarpingFilter object.
### AutoSkew() {#AutoSkew}
```
public static PreprocessingFilter AutoSkew()
```


Active la correction automatique de l'inclinaison de l'image.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### AutoSkew(Rectangle area) {#AutoSkew-java.awt.Rectangle}
```
public static PreprocessingFilter AutoSkew(Rectangle area)
```


Active la correction automatique de l'inclinaison de la partie de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| zone | java.awt.Rectangle | Rectangle à prétraiter. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### Binarize() {#Binarize}
```
public static PreprocessingFilter Binarize()
```


Convertit une image en image noir et blanc. Les images binaires sont des images dont les pixels n'ont que deux valeurs d'intensité possibles. Elles sont généralement affichées en noir et blanc. Numériquement, les deux valeurs sont souvent 0 pour le noir et 255 pour le blanc. Les images binaires sont produites par un seuillage automatique d'une image.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Binarize(Rectangle area) {#Binarize-java.awt.Rectangle}
```
public static PreprocessingFilter Binarize(Rectangle area)
```


Convertit une partie de l'image en image noir et blanc. Les images binaires sont des images dont les pixels n'ont que deux valeurs d'intensité possibles. Elles sont généralement affichées en noir et blanc. Numériquement, les deux valeurs sont souvent 0 pour le noir et 255 pour le blanc. Les images binaires sont produites par un seuillage automatique d'une image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| zone | java.awt.Rectangle | Rectangle à prétraiter. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### BinarizeAndDilate() {#BinarizeAndDilate}
```
public static PreprocessingFilter BinarizeAndDilate()
```


La dilatation ajoute des pixels aux frontières des objets dans une image.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### BinarizeAndDilate(Rectangle area) {#BinarizeAndDilate-java.awt.Rectangle}
```
public static PreprocessingFilter BinarizeAndDilate(Rectangle area)
```


La dilatation ajoute des pixels aux frontières des objets dans une partie de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| zone | java.awt.Rectangle | Rectangle à prétraiter. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### ContrastCorrection() {#ContrastCorrection}
```
public static PreprocessingFilter ContrastCorrection()
```


Filtre de correction de contraste.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### ContrastCorrection(Rectangle area) {#ContrastCorrection-java.awt.Rectangle}
```
public static PreprocessingFilter ContrastCorrection(Rectangle area)
```


Filtre de correction de contraste pour la partie de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| zone | java.awt.Rectangle | Rectangle à prétraiter. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### Invert() {#Invert}
```
public static PreprocessingFilter Invert()
```


Inverse automatiquement les couleurs d'une image de document.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Invert(Rectangle area) {#Invert-java.awt.Rectangle}
```
public static PreprocessingFilter Invert(Rectangle area)
```


Inverse automatiquement les couleurs dans une partie de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| zone | java.awt.Rectangle | Rectangle à prétraiter. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Median() {#Median}
```
public static PreprocessingFilter Median()
```


Le filtre médian parcourt chaque élément de l'image et remplace chaque pixel par la médiane de ses pixels voisins.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Median(Rectangle area) {#Median-java.awt.Rectangle}
```
public static PreprocessingFilter Median(Rectangle area)
```


Le filtre médian parcourt chaque élément de la partie de l'image et remplace chaque pixel par la médiane de ses pixels voisins.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| zone | java.awt.Rectangle | Rectangle à prétraiter. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Resize(int width, int height) {#Resize-int-int}
```
public static PreprocessingFilter Resize(int width, int height)
```


Redimensionner l'image - augmenter ou diminuer la résolution de l'image. InterpolationFilterType = bilinéaire ou voisin le plus proche @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur | int | La nouvelle largeur de l'image. |
| hauteur | int | La nouvelle hauteur de l'image. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Resize(int width, int height, InterpolationFilterType type) {#Resize-int-int-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Resize(int width, int height, InterpolationFilterType type)
```


Redimensionner l'image - augmenter ou diminuer la résolution de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur | int | La nouvelle largeur de l'image. |
| hauteur | int | La nouvelle hauteur de l'image. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Rotate(float angle) {#Rotate-float}
```
public static PreprocessingFilter Rotate(float angle)
```


Faire pivoter l'image originale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | Angle de rotation. Valeur de -360 à 360. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Rotate(float angle, Rectangle area) {#Rotate-float-java.awt.Rectangle}
```
public static PreprocessingFilter Rotate(float angle, Rectangle area)
```


Faire pivoter la partie de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | Angle de rotation. Valeur de -360 à 360. |
| zone | java.awt.Rectangle | Rectangle à prétraiter. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Scale(float ratio) {#Scale-float}
```
public static PreprocessingFilter Scale(float ratio)
```


Redimensionner l'image - Agrandir ou réduire la résolution de l'image. InterpolationFilterType par défaut bilinéaire ou voisin le plus proche @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ratio | float | Le facteur d'échelle. Valeur recommandée de 0,1 à 1 pour réduire. De 1 à 10 pour agrandir. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Scale(float ratio, InterpolationFilterType type) {#Scale-float-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Scale(float ratio, InterpolationFilterType type)
```


Redimensionner l'image - augmenter ou diminuer la résolution de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ratio | float | Le facteur d'échelle. Valeur recommandée de 0,1 à 1 pour réduire. De 1 à 10 pour agrandir. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Threshold(int value) {#Threshold-int}
```
public static PreprocessingFilter Threshold(int value)
```


Créer une image binaire en définissant une valeur de seuil sur l'intensité des pixels de l'image originale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La valeur maximale. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Threshold(int value, Rectangle area) {#Threshold-int-java.awt.Rectangle}
```
public static PreprocessingFilter Threshold(int value, Rectangle area)
```


Créer une partie d'image binaire en définissant une valeur de seuil sur l'intensité des pixels de la partie de l'image originale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La valeur maximale. |
| zone | java.awt.Rectangle | Rectangle à prétraiter. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### ToGrayscale() {#ToGrayscale}
```
public static PreprocessingFilter ToGrayscale()
```


Convertit une image en image en niveaux de gris. L'image en niveaux de gris possède 256 niveaux de luminosité (0 à 255).

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - GrayscaleFilter object.
### add(PreprocessingFilter filter) {#add-com.aspose.ocr.PreprocessingFilter}
```
public void add(PreprocessingFilter filter)
```


Ajoutez le nouveau filtre à la collection pour exécuter toutes les opérations ultérieurement. La cohérence dans la collection est importante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filter | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Nouvelle opération à ajouter à la liste des filtres. |

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

