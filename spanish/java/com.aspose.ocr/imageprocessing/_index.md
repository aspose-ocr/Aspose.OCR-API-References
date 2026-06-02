---
title: "ImageProcessing"
second_title: "Referencia de API de Aspose.OCR para Java"
description: "Clase auxiliar para la biblioteca Aspose OCR"
type: docs
weight: 19
url: /es/java/com.aspose.ocr/imageprocessing/
---

**Inheritance:**
java.lang.Object
```
public class ImageProcessing
```

Clase auxiliar para la biblioteca Aspose OCR. Permite preprocesar y guardar imágenes.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ImageProcessing()](#ImageProcessing) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [Render(OcrInput images)](#Render-com.aspose.ocr.OcrInput) | Utiliza el procesamiento de imágenes para mejorar la precisión del OCR. |
| [Save(OcrInput images, String folderPath)](#Save-com.aspose.ocr.OcrInput-java.lang.String) | Utiliza el procesamiento de imágenes para mejorar la precisión del OCR. |

### ImageProcessing() {#ImageProcessing}
```
public ImageProcessing()
```


### Render(OcrInput images) {#Render-com.aspose.ocr.OcrInput}
```
public static OcrInput Render(OcrInput images)
```


Utiliza el procesamiento de imágenes para mejorar la precisión del OCR. Crea una lista de filtros que se aplicarán a la imagen de entrada en el orden que especifiques. Ejemplo para crear filtros: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); No necesitas todos ellos. Configura solo lo que necesites.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Objeto OcrInput que contiene diferentes imágenes @see \#OcrInput. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput in Image field.
### Save(OcrInput images, String folderPath) {#Save-com.aspose.ocr.OcrInput-java.lang.String}
```
public static OcrInput Save(OcrInput images, String folderPath)
```


Utiliza el procesamiento de imágenes para mejorar la precisión del OCR. Crea una lista de filtros que se aplicarán a la imagen de entrada en el orden que especifiques. Ejemplo para crear filtros: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); No necesitas todos ellos. Configura solo lo que necesites.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Objeto OcrInput que contiene diferentes imágenes @see \#OcrInput. |
| folderPath | java.lang.String | Ruta sin nombres de imágenes para guardar las imágenes procesadas. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput.
