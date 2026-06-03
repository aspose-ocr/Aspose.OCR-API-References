---
title: "Metered"
second_title: "Référence de l'API Aspose.OCR pour Python via .NET"
description: 
type: docs
weight: 190
url: /fr/python-net/aspose.ocr/metered/
---

## Metered class

Fournit des méthodes pour définir la clé mesurée.

Le type Metered expose les membres suivants :
## Constructors
| Name | Description |
| :- | :- |
| Metered() | Initialise une nouvelle instance de cette classe. |
## Methods
| Name | Description |
| :- | :- |
| set_metered_key(public_key, private_key) | Définit les clés publiques et privées mesurées.<br/>            Si vous achetez une licence mesurée, au démarrage de l’application, cette API doit être appelée, normalement, cela suffit. <br/>            Cependant, si le téléchargement des données de consommation échoue constamment et dépasse 24 heures, la licence sera mise en statut d’évaluation, <br/>            pour éviter ce cas, vous devez vérifier régulièrement le statut de la licence, si elle est en statut d’évaluation, appeler à nouveau cette API. |
| get_consumption_quantity() | Obtient la taille du fichier de consommation. |
| get_consumption_credit() | Obtient le crédit de consommation. |

### See Also

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

