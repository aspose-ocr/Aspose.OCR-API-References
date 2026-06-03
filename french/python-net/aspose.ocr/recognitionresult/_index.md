---
title: "RecognitionResult"
second_title: "Référence de l'API Aspose.OCR pour Python via .NET"
description: 
type: docs
weight: 290
url: /fr/python-net/aspose.ocr/recognitionresult/
---

## RecognitionResult class

Les résultats de la reconnaissance d'image.<br/>            Contient des éléments avec des informations de reconnaissance et des méthodes d'exportation des résultats.

Le type RecognitionResult expose les membres suivants :


## Properties
| Name | Description |
| :- | :- |
| recognition_regions_result | Obtient une liste de résultats de reconnaissance avec une liste de régions (Rectangles). |
| recognition_lines_result | Obtient une liste de résultats de reconnaissance avec une liste de lignes (Rectangles). |
| recognition_characters_list | Ensemble de caractères trouvés par l'algorithme de reconnaissance et classés par ordre décroissant de probabilité. |
| recognition_text | Obtient le résultat de reconnaissance sous forme d'une chaîne unique. |
| file_name | Chemin complet du fichier. |
| warnings | Obtient la liste des messages d'avertissement décrivant les défauts non critiques survenus lors de la génération. |
| serializable_image |  |
## Methods
| Name | Description |
| :- | :- |
| save(full_file_name, save_format, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) | Enregistre le document au format texte brut, PDF ou document Microsoft Word. |
| save(full_file_name, save_format, embedded_font_path, optimize_pdf) | Enregistre le document au format texte brut, PDF ou document Microsoft Word. |
| save(full_file_name, save_format, optimize_pdf) | Enregistre le document au format texte brut, PDF ou document Microsoft Word. |
| save(stream, save_format, optimize_pdf) | Enregistre le document au format texte brut, PDF ou document Microsoft Word. |
| save(stream, save_format, apply_spelling_correction, language, dictionary_path) | Enregistre le document au format texte brut, PDF ou document Microsoft Word. |
| get_spell_check_corrected_text(language, dictionary_path) | Corrige le texte (remplace les mots mal orthographiés). |
| get_spell_check_error_list(language, dictionary_path) | Trouve les mots mal orthographiés avec les suggestions d'orthographe pour un texte d'entrée donné. |
| get_json(is_readable) | Forme une chaîne JSON avec les résultats de reconnaissance. |
| get_xml() | Forme une chaîne XML avec les résultats de reconnaissance. |
| get_keywords() | Obtenir les mots-clés du passeport (Mode test. Fonctionne uniquement pour les passeports des États‑Unis et de MADAGASCAR). |

### See Also

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

