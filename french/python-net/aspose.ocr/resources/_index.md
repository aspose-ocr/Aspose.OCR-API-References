---
title: "Resources"
second_title: "Référence de l'API Aspose.OCR pour Python via .NET"
description: 
type: docs
weight: 360
url: /fr/python-net/aspose.ocr/resources/
---

## Resources class

Gérez les ressources téléchargeables qui améliorent les capacités de reconnaissance d'Aspose.OCR.

Le type Resources expose les membres suivants :
## Constructors
| Name | Description |
| :- | :- |
| Resources() | Initialise une nouvelle instance de la classe Resources |
## Methods
| Name | Description |
| :- | :- |
| set_local_path(path) | Spécifiez un chemin absolu ou relatif vers le répertoire où les ressources seront téléchargées.<br/>            Si le répertoire n'existe pas, il sera créé automatiquement.<br/>            Par défaut, les ressources sont téléchargées dans le répertoire aspose_data du répertoire de travail de l'application. |
| set_local_path(path, create) | Spécifiez un chemin absolu ou relatif vers le répertoire où les ressources seront téléchargées.<br/>            Passez `false` au paramètre `create` pour empêcher la création automatique du répertoire.<br/>            Si le répertoire fourni n'existe pas et que la création n'est pas autorisée, les ressources seront chargées dans le répertoire aspose_data du répertoire de travail de l'application. |
| set_repository(url) | Spécifiez l'URL du référentiel en ligne à partir duquel les ressources Aspose.OCR seront téléchargées.<br/>            Par défaut, les ressources sont téléchargées depuis https://github.com/aspose-ocr/resources/. |
| get_repository() | Renvoie l'URL du référentiel en ligne à partir duquel les ressources Aspose.OCR sont téléchargées. |
| list_remote() | Liste toutes les ressources compatibles du référentiel en ligne. |
| get_local_path() | Renvoie le chemin complet du répertoire où les ressources seront téléchargées. |
| list_local() | Liste toutes les ressources Aspose.OCR stockées dans le répertoire local. |
| allow_automatic_downloads(allow) | Autorise (true) ou bloque (false) le téléchargement automatique des ressources requises depuis le référentiel en ligne.<br/>             Par défaut, une ressource est téléchargée automatiquement lorsqu'une méthode qui en dépend est appelée. |
| fetch_resources(names) | Télécharge les ressources spécifiées dans le paramètre `names` depuis le référentiel en ligne. Si une ou plusieurs ressources sont déjà téléchargées, elles seront écrasées.<br/>            Vous pouvez omettre l'extension .OCR et n'utiliser que les noms de fichiers. |
| fetch_resource(name) | Télécharge les ressources spécifiées dans le paramètre `names` depuis le référentiel en ligne. Si une ou plusieurs ressources sont déjà téléchargées, elles seront écrasées.<br/>            Vous pouvez omettre l'extension .OCR et n'utiliser que les noms de fichiers. |
| fetch_all() | Télécharge toutes les ressources compatibles depuis le référentiel en ligne. Les fichiers de ressources existants seront écrasés. |
| remove_local(name) | Supprime la ressource Aspose.OCR stockée localement. |
| release_memory() |  |

### See Also

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

