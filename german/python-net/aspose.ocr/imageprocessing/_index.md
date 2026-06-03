---
title: "ImageProcessing"
second_title: "Aspose.OCR für Python via .NET API-Referenz"
description: 
type: docs
weight: 120
url: /de/python-net/aspose.ocr/imageprocessing/
---

## ImageProcessing class

Hilfsklasse für die Aspose OCR-Bibliothek. Ermöglicht das Vorverarbeiten und Speichern von Bildern.

Der Typ ImageProcessing stellt die folgenden Mitglieder bereit:
## Methoden
| Name | Beschreibung |
| :- | :- |
| save(images, folder_path) | Verwenden Sie die Bildverarbeitung, um die Genauigkeit der OCR zu verbessern.<br/>            Erstellen Sie eine Liste von Filtern, die in der von Ihnen angegebenen Reihenfolge auf das Eingabebild angewendet werden.<br/>            Beispiel zum Erstellen von Filtern:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            Sie benötigen nicht alle. Setzen Sie nur das, was Sie benötigen. |
| render(images) | Verwenden Sie die Bildverarbeitung, um die Genauigkeit der OCR zu verbessern.<br/>            Erstellen Sie eine Liste von Filtern, die in der von Ihnen angegebenen Reihenfolge auf das Eingabebild angewendet werden.<br/>            Beispiel zum Erstellen von Filtern:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            Sie benötigen nicht alle. Setzen Sie nur das, was Sie benötigen. |

### Siehe auch

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

