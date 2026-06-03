---
title: "ImageProcessing"
second_title: "Aspose.OCR para Python a través de .NET Referencia de API"
description: 
type: docs
weight: 120
url: /es/python-net/aspose.ocr/imageprocessing/
---

## ImageProcessing class

Clase auxiliar de la biblioteca Aspose OCR. Permite preprocesar y guardar imágenes.

El tipo ImageProcessing expone los siguientes miembros:
## Methods
| Nombre | Descripción |
| :- | :- |
| save(images, folder_path) | Utilice el procesamiento de imágenes para mejorar la precisión del OCR.<br/>            Cree una lista de filtros que se aplicarán a la imagen de entrada en el orden que especifique.<br/>            Ejemplo para crear filtros:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            No necesita todos ellos. Establezca solo lo que necesite. |
| render(images) | Utilice el procesamiento de imágenes para mejorar la precisión del OCR.<br/>            Cree una lista de filtros que se aplicarán a la imagen de entrada en el orden que especifique.<br/>            ejemplo para crear filtros:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            No necesita todos ellos. Establezca solo lo que necesite. |

### Ver también

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

