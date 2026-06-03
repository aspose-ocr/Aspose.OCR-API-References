---
title: "OcrInput"
second_title: "Aspose.OCR voor Python via .NET API-referentie"
description: 
type: docs
weight: 240
url: /nl/python-net/aspose.ocr/ocrinput/
---

## OcrInput class

Container om alle afbeeldingen / documenten te verzamelen voor pre-processing / herkenning.

Het OcrInput-type biedt de volgende leden:
## Constructors
| Naam | Beschrijving |
| :- | :- |
| OcrInput(type, filters) | Initialiseert een nieuwe instantie van de OcrInput-klasse |
| OcrInput(type) | Initialiseert een nieuwe instantie van de OcrInput-klasse |
## Indexer
| Naam | Beschrijving |
| :- | :- |
| [index] | Retourneert informatie over de verwerkte / herkende afbeelding. |
## Methods
| Naam | Beschrijving |
| :- | :- |
| add(full_path) | Voeg het pad of de URI toe die de afbeelding bevat voor herkenning / verwerking.<br/>            Het type van de afbeelding moet overeenkomen met het type dat is opgegeven in de constructor. |
| add(stream) | Voeg de geheugenstroom toe die de afbeelding bevat voor herkenning / verwerking.<br/>            Het type van de afbeelding moet overeenkomen met het type dat is opgegeven in de constructor. |
| add(full_path, start_page, pages_count) | Voeg de meerpagina-afbeeldingen / documenten toe voor herkenning / verwerking.<br/>            Het type van de afbeelding moet overeenkomen met het type dat is opgegeven in de constructor. |
| add(stream, start_page, pages_count) | Voeg de geheugenstroom toe die de meerpagina-afbeelding bevat voor herkenning / verwerking.<br/>            Het type van de afbeelding moet overeenkomen met het type dat is opgegeven in de constructor. |
| add(arr, width, height, pixel_format) | Voeg de gedecodeerde afbeelding toe aan de lijst voor herkenning / verwerking.<br/>            Het type van de afbeelding moet overeenkomen met het type dat is opgegeven in de constructor (SingleImage). |
| replace_filters(filters) | Verwijder oude filters en stel nieuwe in. |
| clear_filters() | Verwijder alle filters. |
| add_base64(base64) | Voeg de base64‑string toe die de afbeelding bevat voor herkenning / verwerking.<br/>            Het type van de afbeelding moet overeenkomen met het type dat is opgegeven in de constructor. |
| clear() | Verwijder alle filters. |
| count() | Aantal items voor verwerking / herkenning. |
| get_input_type() | Type van toegestane afbeeldingen voor herkenning. |

### Zie ook

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

