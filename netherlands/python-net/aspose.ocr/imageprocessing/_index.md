---
title: "ImageProcessing"
second_title: "Aspose.OCR voor Python via .NET API-referentie"
description: 
type: docs
weight: 120
url: /nl/python-net/aspose.ocr/imageprocessing/
---

## ImageProcessing class

Helperklasse voor Aspose OCR-bibliotheek. Stelt in staat om afbeeldingen voor te verwerken en op te slaan.

Het type ImageProcessing biedt de volgende leden:
## Methods
| Naam | Beschrijving |
| :- | :- |
| save(images, folder_path) | Gebruik beeldverwerking om de nauwkeurigheid van OCR te verbeteren.<br/>            Maak een lijst met filters die op de invoerafbeelding worden toegepast in de volgorde die u opgeeft.<br/>            Voorbeeld om filters te maken:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            U heeft niet allemaal nodig. Stel alleen in wat u nodig heeft. |
| render(images) | Gebruik beeldverwerking om de nauwkeurigheid van OCR te verbeteren.<br/>            Maak een lijst met filters die op de invoerafbeelding worden toegepast in de volgorde die u opgeeft.<br/>            voorbeeld om filters te maken:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            U heeft niet allemaal nodig. Stel alleen in wat u nodig heeft. |

### Zie ook

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

