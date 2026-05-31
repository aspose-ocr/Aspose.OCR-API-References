---
title: "ImageProcessing"
second_title: "Référence API d'Aspose.OCR pour Java"
description: "Classe d'assistance pour la bibliothèque Aspose OCR"
type: docs
weight: 19
url: /fr/java/com.aspose.ocr/imageprocessing/
---

**Inheritance:**
java.lang.Object
```
public class ImageProcessing
```

Classe d'assistance pour la bibliothèque Aspose OCR. Permet de prétraiter et d'enregistrer les images.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImageProcessing()](#ImageProcessing) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [Render(OcrInput images)](#Render-com.aspose.ocr.OcrInput) | Utilisez le traitement d'image pour améliorer la précision de l'OCR. |
| [Save(OcrInput images, String folderPath)](#Save-com.aspose.ocr.OcrInput-java.lang.String) | Utilisez le traitement d'image pour améliorer la précision de l'OCR. |

### ImageProcessing() {#ImageProcessing}
```
public ImageProcessing()
```


### Render(OcrInput images) {#Render-com.aspose.ocr.OcrInput}
```
public static OcrInput Render(OcrInput images)
```


Utilisez le traitement d'image pour améliorer la précision de l'OCR. Créez une liste de filtres qui seront appliqués à l'image d'entrée dans l'ordre que vous spécifiez. Exemple pour créer des filtres : PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); Vous n'avez pas besoin de tous. Définissez uniquement ce dont vous avez besoin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Objet OcrInput contenant différentes images @see \#OcrInput. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput in Image field.
### Save(OcrInput images, String folderPath) {#Save-com.aspose.ocr.OcrInput-java.lang.String}
```
public static OcrInput Save(OcrInput images, String folderPath)
```


Utilisez le traitement d'image pour améliorer la précision de l'OCR. Créez une liste de filtres qui seront appliqués à l'image d'entrée dans l'ordre que vous spécifiez. Exemple pour créer des filtres : PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); Vous n'avez pas besoin de tous. Définissez uniquement ce dont vous avez besoin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Objet OcrInput contenant différentes images @see \#OcrInput. |
| folderPath | java.lang.String | Chemin sans les noms d'images pour enregistrer les images traitées. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput.
