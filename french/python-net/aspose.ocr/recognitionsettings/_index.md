---
title: "RecognitionSettings"
second_title: "Référence de l'API Aspose.OCR pour Python via .NET"
description: 
type: docs
weight: 330
url: /fr/python-net/aspose.ocr/recognitionsettings/
---

## RecognitionSettings class

Paramètres pour la reconnaissance d'images.<br/>            Contient des éléments qui permettent de personnaliser le processus de reconnaissance.

Le type RecognitionSettings expose les membres suivants :
## Constructors
| Name | Description |
| :- | :- |
| RecognitionSettings() | Initialise une nouvelle instance de |
| RecognitionSettings(language, recognition_areas, recognize_single_line) | Initialise une nouvelle instance de la classe RecognitionSettings |
## Properties
| Name | Description |
| :- | :- |
| recognize_vertical_lines |  |
| threads_count | Obtient ou définit le nombre de threads pour le traitement. |
| language | Obtient ou définit la langue utilisée pour l'OCR. |
| ignored_symbols | Définit la liste noire pour les symboles de reconnaissance. |
| allowed_symbols | Définit les caractères autorisés avec la propriété alphabet. |
| allowed_characters | Ensemble de caractères autorisés. Détermine le type de caractères autorisés pour le résultat de reconnaissance. |
| automatic_color_inversion | Détecte les images avec du texte blanc sur fond sombre/noir et choisit automatiquement un algorithme OCR spécial pour celles-ci. |
| zones_de_reconnaissance | Obtient ou définit la liste des zones de texte à traiter. |
| recognize_single_line | Définit la reconnaissance d'image à une seule ligne. <br/>            Désactivé (false) par défaut. <br/>            Désactive toutes les étapes de traitement associées à la division en lignes. <br/>            Réglez ce paramètre sur true si votre image ne contient qu'une seule ligne. Désactive les paramètres RecognitionAreas, ainsi tous les paramètres de zones seront ignorés. |
| language_detection_level |  |
| lines_filtration | Permet de reconnaître le texte dans les tableaux (régions entourées de lignes). |
| detect_areas_mode | Permet de sélectionner le mode optimal pour les zones de type document : document, photo, texte brut, colonne, image. |
| upscale_small_font | Vous permet d'utiliser des algorithmes supplémentaires spécifiquement pour la reconnaissance de petites polices.<br/>            Utile pour les images contenant des caractères de petite taille. |

### See Also

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

