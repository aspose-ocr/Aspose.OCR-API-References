---
title: "PreprocessingFilter"
second_title: "Référence de l'API Aspose.OCR pour Python via .NET"
description: 
type: docs
weight: 10
url: /fr/python-net/aspose.ocr.models.preprocessingfilters/preprocessingfilter/
---

## PreprocessingFilter class

Classe de base pour les commandes de traitement d'image.

Le type PreprocessingFilter expose les membres suivants :
## Constructors
| Name | Description |
| :- | :- |
| PreprocessingFilter() | Initialise une nouvelle instance de la classe PreprocessingFilter |
## Properties
| Name | Description |
| :- | :- |
| par défaut | La collection de filtres par défaut contient le filtre AutoSkew |
| empty | Collection de filtres vide |
## Methods
| Name | Description |
| :- | :- |
| binarize() | Convertit une image en image noir et blanc.<br/>            Les images binaires sont des images dont les pixels n'ont que deux valeurs d'intensité possibles. <br/>            Elles sont généralement affichées en noir et blanc. Numériquement, les deux valeurs sont souvent 0 pour le noir et 255 pour le blanc.<br/>            Les images binaires sont produites par seuillage automatique d'une image. |
| binarize(area) | Convertit une partie de l'image en image noir et blanc.<br/>            Les images binaires sont des images dont les pixels n'ont que deux valeurs d'intensité possibles. <br/>            Elles sont généralement affichées en noir et blanc. Numériquement, les deux valeurs sont souvent 0 pour le noir et 255 pour le blanc.<br/>            Les images binaires sont produites par seuillage automatique d'une image. |
| resize(width, height, type) | Redimensionne l'image - Augmente ou réduit la résolution de l'image. |
| resize(width, height) | Redimensionne l'image - Augmente ou réduit la résolution de l'image. |
| dilate() | La dilatation ajoute des pixels aux frontières des objets dans une image. |
| dilate(area) | La dilatation ajoute des pixels aux frontières des objets dans une partie de l'image. |
| invert() | Inverse automatiquement les couleurs dans une image de document. |
| invert(area) | Inverse automatiquement les couleurs dans une partie de l'image. |
| rotate(angle) | Faire pivoter l'image originale. |
| rotate(angle, area) | Faire pivoter une partie de l'image. |
| scale(ratio) | Redimensionner l'image - Augmenter ou diminuer la résolution de l'image.<br/>            InterpolationFilterType = Lanczos8 |
| scale(ratio, type) | Redimensionne l'image - Augmente ou réduit la résolution de l'image. |
| threshold(value) | Créer une image binaire en définissant une valeur de seuil sur l'intensité des pixels de l'image originale. |
| threshold(value, area) | Créer une partie binaire de l'image en définissant une valeur de seuil sur l'intensité des pixels de la partie originale de l'image. |
| median() | Le filtre médian parcourt chaque élément de l'image et remplace chaque pixel par la médiane de ses pixels voisins. |
| median(area) | Le filtre médian parcourt chaque élément de la partie de l'image et remplace chaque pixel par la médiane de ses pixels voisins. |
| auto_denoising() | Permet l'utilisation d'un réseau neuronal supplémentaire pour améliorer l'image - réduire le bruit.<br/>            Utile pour les images présentant des artefacts de numérisation, des distorsions, des taches, des éclats, des dégradés, des éléments étrangers. |
| auto_denoising(area) | Permet l'utilisation d'un réseau neuronal supplémentaire pour améliorer la partie de l'image - réduire le bruit.<br/>            Utile pour les images présentant des artefacts de numérisation, des distorsions, des taches, des éclats, des dégradés, des éléments étrangers. |
| auto_skew() | Active la correction automatique de l'inclinaison de l'image. |
| auto_skew(area) | Active la correction automatique de l'inclinaison de la partie de l'image. |
| contrast_correction_filter() | Filtre de correction de contraste. |
| contrast_correction_filter(area) | Filtre de correction de contraste pour la partie de l'image. |
| to_grayscale() | Convertit une image en image en niveaux de gris.<br/>            L'image en niveaux de gris possède 256 niveaux de luminosité (de 0 à 255). |
| auto_dewarping() | Corrige automatiquement les distorsions géométriques de l'image.<br/>            Extrêmement gourmand en ressources! |
| add(filter) | Ajoutez le nouveau filtre à la collection pour exécuter toutes les opérations ultérieures.<br/>            La cohérence de la collection est importante. |

### See Also

* namespace [aspose.ocr.models.preprocessingfilters](/ocr/python-net/aspose.ocr.models.preprocessingfilters/)
* assembly [Aspose.ocr](/ocr/python-net/)

