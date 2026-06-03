---
title: "ImageProcessing"
second_title: "Aspose.OCR för Python via .NET API-referens"
description: 
type: docs
weight: 120
url: /sv/python-net/aspose.ocr/imageprocessing/
---

## ImageProcessing class

Hjälpklass för Aspose OCR-biblioteket. Tillåter förbehandling och sparande av bilder.

Typen ImageProcessing visar följande medlemmar:
## Metoder
| Namn | Beskrivning |
| :- | :- |
| save(images, folder_path) | Använd bildbehandling för att förbättra OCR‑noggrannheten.<br/>            Skapa en lista med filter som kommer att tillämpas på inmatningsbilden i den ordning du anger.<br/>            Exempel för att skapa filter:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            Du behöver inte alla. Ställ in bara det du behöver. |
| render(images) | Använd bildbehandling för att förbättra OCR‑noggrannheten.<br/>            Skapa en lista med filter som kommer att tillämpas på inmatningsbilden i den ordning du anger.<br/>            exempel för att skapa filter:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            Du behöver inte alla. Ställ in bara det du behöver. |

### Se även

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

