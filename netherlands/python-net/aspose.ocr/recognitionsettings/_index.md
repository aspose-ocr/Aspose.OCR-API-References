---
title: "RecognitionSettings"
second_title: "Aspose.OCR voor Python via .NET API-referentie"
description: 
type: docs
weight: 330
url: /nl/python-net/aspose.ocr/recognitionsettings/
---

## RecognitionSettings class

Instellingen voor de beeldherkenning.<br/>            Bevat elementen die het aanpassen van het herkenningsproces mogelijk maken.

Het type RecognitionSettings exposeert de volgende leden:
## Constructors
| Naam | Beschrijving |
| :- | :- |
| RecognitionSettings() | Initialiseert een nieuw exemplaar van de |
| RecognitionSettings(language, recognition_areas, recognize_single_line) | Initialiseert een nieuw exemplaar van de klasse RecognitionSettings |
## Eigenschappen
| Naam | Beschrijving |
| :- | :- |
| recognize_vertical_lines |  |
| threads_count | Haalt het aantal threads op of stelt het in voor verwerking. |
| language | Haalt de taal op die voor OCR wordt gebruikt, of stelt deze in. |
| ignored_symbols | Stelt een zwarte lijst in voor herkenningssymbolen. |
| allowed_symbols | Stel de toegestane tekens in met de eigenschap alphabet. |
| allowed_characters | Set van toegestane tekens. Bepaalt het type tekens dat is toegestaan voor het herkenningsresultaat. |
| automatic_color_inversion | Detecteert afbeeldingen met witte tekst op een donkere/zwart achtergrond en kiest automatisch een speciaal OCR-algoritme voor hen. |
| recognition_areas | Haalt de lijst met tekstgebieden op of stelt deze in voor verwerking. |
| recognize_single_line | Stelt herkenning van éénregelige afbeeldingen in. <br/>            Standaard uitgeschakeld (false). <br/>            Schakel alle verwerkingsstappen uit die verband houden met het splitsen in regels. <br/>            Stel deze parameter in op true als uw afbeelding slechts één regel bevat. Schakelt de instellingen voor RecognitionAreas uit, zodat alle gebiedsinstellingen worden genegeerd. |
| language_detection_level |  |
| lines_filtration | Staat toe tekst te herkennen in de tabellen (gebieden omgeven door lijnen). |
| detect_areas_mode | Staat toe de optimale modus te selecteren voor gebieden van het documenttype: document, foto, platte tekst, kolom, afbeelding. |
| upscale_small_font | Staat u toe extra algoritmen te gebruiken die specifiek zijn voor herkenning van kleine letters.<br/>            Handig voor afbeeldingen met kleine tekens. |

### Zie ook

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

