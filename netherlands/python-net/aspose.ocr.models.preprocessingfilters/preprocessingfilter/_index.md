---
title: "PreprocessingFilter"
second_title: "Aspose.OCR voor Python via .NET API-referentie"
description: 
type: docs
weight: 10
url: /nl/python-net/aspose.ocr.models.preprocessingfilters/preprocessingfilter/
---

## PreprocessingFilter class

Basisklasse voor beeldverwerkingsopdrachten.

Het type PreprocessingFilter bevat de volgende leden:
## Constructors
| Naam | Beschrijving |
| :- | :- |
| PreprocessingFilter() | Initialiseert een nieuw exemplaar van de PreprocessingFilter-klasse |
## Eigenschappen
| Naam | Beschrijving |
| :- | :- |
| standaard | Standaardfiltercollectie bevat AutoSkew-filter |
| empty | Lege filtercollectie |
## Methods
| Naam | Beschrijving |
| :- | :- |
| binarize() | Converteert een afbeelding naar een zwart-wit afbeelding.<br/>            Binaire afbeeldingen zijn afbeeldingen waarvan de pixels slechts twee mogelijke intensiteitswaarden hebben. <br/>            Ze worden normaal weergegeven als zwart en wit. Numeriek zijn de twee waarden vaak 0 voor zwart en 255 voor wit.<br/>            Binaire afbeeldingen worden geproduceerd door automatische drempelbepaling van een afbeelding. |
| binarize(area) | Converteert een deel van de afbeelding naar een zwart-wit afbeelding.<br/>            Binaire afbeeldingen zijn afbeeldingen waarvan de pixels slechts twee mogelijke intensiteitswaarden hebben. <br/>            Ze worden normaal weergegeven als zwart en wit. Numeriek zijn de twee waarden vaak 0 voor zwart en 255 voor wit.<br/>            Binaire afbeeldingen worden geproduceerd door automatische drempelbepaling van een afbeelding. |
| resize(width, height, type) | Schaal afbeelding opnieuw - Verhoog of verlaag de resolutie van de afbeelding. |
| resize(width, height) | Schaal afbeelding opnieuw - Verhoog of verlaag de resolutie van de afbeelding. |
| dilate() | Dilatie voegt pixels toe aan de randen van objecten in een afbeelding. |
| dilate(area) | Dilatie voegt pixels toe aan de randen van objecten in een deel van de afbeelding. |
| invert() | Keert automatisch de kleuren om in een documentafbeelding. |
| invert(area) | Keert automatisch de kleuren om in een deel van de afbeelding. |
| rotate(angle) | Roteer de originele afbeelding. |
| rotate(angle, area) | Roteer een deel van de afbeelding. |
| scale(ratio) | Afbeelding herschalen - Verhoog of verlaag de resolutie van de afbeelding.<br/>            InterpolationFilterType = Lanczos8 |
| scale(ratio, type) | Schaal afbeelding opnieuw - Verhoog of verlaag de resolutie van de afbeelding. |
| threshold(value) | Maak een binaire afbeelding op basis van het instellen van een drempelwaarde op de pixelintensiteit van de originele afbeelding. |
| threshold(value, area) | Maak een binaire afbeeldingdeel op basis van het instellen van een drempelwaarde op de pixelintensiteit van het originele afbeeldingdeel. |
| median() | Het medianfilter doorloopt elk element van de afbeelding en vervangt elke pixel door de mediaan van de aangrenzende pixels. |
| median(area) | Het medianfilter doorloopt elk element van het afbeeldingdeel en vervangt elke pixel door de mediaan van de aangrenzende pixels. |
| auto_denoising() | Stelt het gebruik van een extra neuraal netwerk in om de afbeelding te verbeteren - ruis te verminderen.<br/>            Handig voor afbeeldingen met scanartefacten, vervormingen, vlekken, schitteringen, verlopen, vreemde elementen. |
| auto_denoising(area) | Stelt het gebruik van een extra neuraal netwerk in om het afbeeldingdeel te verbeteren - ruis te verminderen.<br/>            Handig voor afbeeldingen met scanartefacten, vervormingen, vlekken, schitteringen, verlopen, vreemde elementen. |
| auto_skew() | Stelt de automatische scheefcorrectie van de afbeelding in. |
| auto_skew(area) | Stelt de automatische scheefcorrectie van het afbeeldingdeel in. |
| contrast_correction_filter() | Contrastcorrectiefilter. |
| contrast_correction_filter(area) | Contrastcorrectiefilter voor het afbeeldingdeel. |
| to_grayscale() | Converteert een afbeelding naar een grijswaardenafbeelding.<br/>            Een grijswaardenafbeelding heeft 256 lichtniveaus (0 tot 255). |
| auto_dewarping() | Corrigeert automatisch geometrische vervormingen in de afbeelding.<br/>            Zeer resource-intensief! |
| add(filter) | Voeg het nieuwe filter toe aan de collectie om alle bewerkingen verder uit te voeren.<br/>            Consistentie in de collectie is belangrijk. |

### Zie ook

* namespace [aspose.ocr.models.preprocessingfilters](/ocr/python-net/aspose.ocr.models.preprocessingfilters/)
* assembly [Aspose.ocr](/ocr/python-net/)

