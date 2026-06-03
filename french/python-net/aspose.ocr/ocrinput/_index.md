---
title: "OcrInput"
second_title: "Référence de l'API Aspose.OCR pour Python via .NET"
description: 
type: docs
weight: 240
url: /fr/python-net/aspose.ocr/ocrinput/
---

## OcrInput class

Conteneur pour rassembler toutes les images / documents en vue du prétraitement / de la reconnaissance.

Le type OcrInput expose les membres suivants :
## Constructors
| Name | Description |
| :- | :- |
| OcrInput(type, filters) | Initialise une nouvelle instance de la classe OcrInput |
| OcrInput(type) | Initialise une nouvelle instance de la classe OcrInput |
## Indexer
| Name | Description |
| :- | :- |
| [index] | Renvoie des informations sur l'image traitée / reconnue. |
## Methods
| Name | Description |
| :- | :- |
| add(full_path) | Ajoute le chemin ou l'URI contenant l'image pour la reconnaissance / le traitement.<br/>            Le type de l'image doit correspondre au type spécifié dans le constructeur. |
| add(stream) | Ajoute le flux mémoire contenant l'image pour la reconnaissance / le traitement.<br/>            Le type de l'image doit correspondre au type spécifié dans le constructeur. |
| add(full_path, start_page, pages_count) | Ajoute les images / documents multipages pour la reconnaissance / le traitement.<br/>            Le type de l'image doit correspondre au type spécifié dans le constructeur. |
| add(stream, start_page, pages_count) | Ajoute le flux mémoire contenant l'image multipage pour la reconnaissance / le traitement.<br/>            Le type de l'image doit correspondre au type spécifié dans le constructeur. |
| add(arr, width, height, pixel_format) | Ajoutez l'image décodée à la liste pour la reconnaissance / le traitement.<br/>            Le type de l'image doit correspondre au type spécifié dans le constructeur (SingleImage). |
| replace_filters(filters) | Supprimez les anciens filtres et définissez‑en de nouveaux. |
| clear_filters() | Supprimez tous les filtres. |
| add_base64(base64) | Ajoutez la chaîne base64 contenant l'image pour la reconnaissance / le traitement.<br/>            Le type de l'image doit correspondre au type spécifié dans le constructeur. |
| clear() | Supprimez tous les filtres. |
| count() | Nombre d'éléments pour le traitement / la reconnaissance. |
| get_input_type() | Type d'images autorisées pour la reconnaissance. |

### See Also

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

