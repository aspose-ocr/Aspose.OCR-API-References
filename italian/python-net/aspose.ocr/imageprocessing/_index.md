---
title: "ImageProcessing"
second_title: "Riferimento API di Aspose.OCR per Python via .NET"
description: 
type: docs
weight: 120
url: /it/python-net/aspose.ocr/imageprocessing/
---

## ImageProcessing class

Classe di supporto per la libreria Aspose OCR. Consente di pre-elaborare e salvare le immagini.

Il tipo ImageProcessing espone i seguenti membri:
## Methods
| Nome | Descrizione |
| :- | :- |
| save(images, folder_path) | Utilizza l'elaborazione delle immagini per migliorare l'accuratezza dell'OCR.<br/>            Crea un elenco di filtri che verranno applicati all'immagine di input nell'ordine specificato.<br/>            Esempio per creare filtri:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            Non è necessario usarli tutti. Imposta solo quelli di cui hai bisogno. |
| render(images) | Utilizza l'elaborazione delle immagini per migliorare l'accuratezza dell'OCR.<br/>            Crea un elenco di filtri che verranno applicati all'immagine di input nell'ordine specificato.<br/>            esempio per creare filtri:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            Non è necessario usarli tutti. Imposta solo quelli di cui hai bisogno. |

### Vedi anche

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

