---
title: "ImageProcessing"
second_title: "Référence de l'API Aspose.OCR pour Python via .NET"
description: 
type: docs
weight: 120
url: /fr/python-net/aspose.ocr/imageprocessing/
---

## ImageProcessing class

Classe d'assistance pour la bibliothèque Aspose OCR. Permet de prétraiter et d'enregistrer les images.

Le type ImageProcessing expose les membres suivants :
## Methods
| Name | Description |
| :- | :- |
| save(images, folder_path) | Utilisez le traitement d'image pour améliorer la précision de l'OCR.<br/>            Créez une liste de filtres qui seront appliqués à l'image d'entrée dans l'ordre que vous spécifiez.<br/>            Exemple de création de filtres :<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            Vous n'avez pas besoin de tous. Définissez uniquement ce dont vous avez besoin. |
| render(images) | Utilisez le traitement d'image pour améliorer la précision de l'OCR.<br/>            Créez une liste de filtres qui seront appliqués à l'image d'entrée dans l'ordre que vous spécifiez.<br/>            exemple de création de filtres :<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            Vous n'avez pas besoin de tous. Définissez uniquement ce dont vous avez besoin. |

### See Also

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

