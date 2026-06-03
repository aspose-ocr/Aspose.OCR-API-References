---
title: "Resources"
second_title: "Aspose.OCR voor Python via .NET API-referentie"
description: 
type: docs
weight: 360
url: /nl/python-net/aspose.ocr/resources/
---

## Resources class

Beheer downloadbare bronnen die de herkenningsmogelijkheden van **Aspose.OCR** verbeteren.

Het type Resources geeft de volgende leden weer:
## Constructors
| Naam | Beschrijving |
| :- | :- |
| Resources() | Initialiseert een nieuw exemplaar van de Resources‑klasse |
## Methods
| Naam | Beschrijving |
| :- | :- |
| set_local_path(path) | Geef een absoluut of relatief pad op naar de map waar de resources worden gedownload.<br/>            Als de map niet bestaat, wordt deze automatisch aangemaakt.<br/>            Standaard worden de resources gedownload naar de map aspose_data in de werkmap van de applicatie. |
| set_local_path(path, create) | Geef een absoluut of relatief pad op naar de map waar de resources worden gedownload.<br/>            Geef `false` door aan de parameter `create` om te voorkomen dat de map automatisch wordt aangemaakt.<br/>            Als de opgegeven map niet bestaat en aanmaken niet is toegestaan, worden de resources geladen in de map aspose_data in de werkmap van de applicatie. |
| set_repository(url) | Specificeer de URL van de online repository waaruit Aspose.OCR-resources worden gedownload.<br/>            Standaard worden de resources gedownload van https://github.com/aspose-ocr/resources/. |
| get_repository() | Retourneer de URL van de online repository waaruit Aspose.OCR-resources worden gedownload. |
| list_remote() | Lijst alle compatibele resources van de online repository. |
| get_local_path() | Retourneer het volledige pad naar de map waar de resources worden gedownload. |
| list_local() | Lijst alle Aspose.OCR-resources die zijn opgeslagen in de lokale map. |
| allow_automatic_downloads(allow) | Sta (true) toe of blokkeer (false) het automatisch downloaden van vereiste resources van de online repository.<br/>             Standaard wordt een resource automatisch gedownload wanneer een methode die ervan afhankelijk is wordt aangeroepen. |
| fetch_resources(names) | Download de resources die zijn opgegeven in de `names`-parameter van de online repository. Als één of meer resources al gedownload zijn, worden ze overschreven.<br/>            Je kunt de .OCR-extensie weglaten en alleen bestandsnamen gebruiken. |
| fetch_resource(name) | Download de resources die zijn opgegeven in de `names`-parameter van de online repository. Als één of meer resources al gedownload zijn, worden ze overschreven.<br/>            Je kunt de .OCR-extensie weglaten en alleen bestandsnamen gebruiken. |
| fetch_all() | Download alle compatibele resources van de online repository. De bestaande resourcebestanden worden overschreven. |
| remove_local(name) | Verwijdert de lokaal opgeslagen Aspose.OCR-resource. |
| release_memory() |  |

### Zie ook

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

