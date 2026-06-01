---
title: "ImageProcessing"
second_title: "Riferimento API di Aspose.OCR per Java"
description: "Classe di supporto per la libreria Aspose OCR"
type: docs
weight: 19
url: /it/java/com.aspose.ocr/imageprocessing/
---

**Inheritance:**
java.lang.Object
```
public class ImageProcessing
```

Classe di supporto per la libreria Aspose OCR. Consente di pre-elaborare e salvare le immagini.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageProcessing()](#ImageProcessing) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Render(OcrInput images)](#Render-com.aspose.ocr.OcrInput) | Utilizza l'elaborazione delle immagini per migliorare l'accuratezza dell'OCR. |
| [Save(OcrInput images, String folderPath)](#Save-com.aspose.ocr.OcrInput-java.lang.String) | Utilizza l'elaborazione delle immagini per migliorare l'accuratezza dell'OCR. |

### ImageProcessing() {#ImageProcessing}
```
public ImageProcessing()
```


### Render(OcrInput images) {#Render-com.aspose.ocr.OcrInput}
```
public static OcrInput Render(OcrInput images)
```


Utilizza l'elaborazione delle immagini per migliorare l'accuratezza dell'OCR. Crea un elenco di filtri che verranno applicati all'immagine di input nell'ordine specificato. Esempio per creare i filtri: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); Non è necessario usarli tutti. Imposta solo quelli di cui hai bisogno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Oggetto OcrInput contenente diverse immagini @see \#OcrInput. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput in Image field.
### Save(OcrInput images, String folderPath) {#Save-com.aspose.ocr.OcrInput-java.lang.String}
```
public static OcrInput Save(OcrInput images, String folderPath)
```


Utilizza l'elaborazione delle immagini per migliorare l'accuratezza dell'OCR. Crea un elenco di filtri che verranno applicati all'immagine di input nell'ordine specificato. Esempio per creare i filtri: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); Non è necessario usarli tutti. Imposta solo quelli di cui hai bisogno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Oggetto OcrInput contenente diverse immagini @see \#OcrInput. |
| folderPath | java.lang.String | Percorso senza i nomi delle immagini per salvare le immagini elaborate. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput.
