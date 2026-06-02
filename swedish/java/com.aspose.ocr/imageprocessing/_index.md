---
title: "Bildbehandling"
second_title: "Aspose.OCR för Java API-referens"
description: "Hjälparklass för Aspose OCR-biblioteket"
type: docs
weight: 19
url: /sv/java/com.aspose.ocr/imageprocessing/
---

**Inheritance:**
java.lang.Object
```
public class ImageProcessing
```

Hjälparklass för Aspose OCR-biblioteket. Tillåter förbehandling och sparande av bilder.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ImageProcessing()](#ImageProcessing) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Render(OcrInput images)](#Render-com.aspose.ocr.OcrInput) | Använd bildbehandling för att förbättra noggrannheten i OCR. |
| [Save(OcrInput images, String folderPath)](#Save-com.aspose.ocr.OcrInput-java.lang.String) | Använd bildbehandling för att förbättra noggrannheten i OCR. |

### ImageProcessing() {#ImageProcessing}
```
public ImageProcessing()
```


### Render(OcrInput images) {#Render-com.aspose.ocr.OcrInput}
```
public static OcrInput Render(OcrInput images)
```


Använd bildbehandling för att förbättra noggrannheten i OCR. Skapa en lista med filter som kommer att tillämpas på inmatningsbilden i den ordning du anger. Exempel för att skapa filter: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); Du behöver inte alla. Ställ in endast det du behöver.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | OcrInput-objekt som innehåller olika bilder @see \#OcrInput. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput in Image field.
### Save(OcrInput images, String folderPath) {#Save-com.aspose.ocr.OcrInput-java.lang.String}
```
public static OcrInput Save(OcrInput images, String folderPath)
```


Använd bildbehandling för att förbättra noggrannheten i OCR. Skapa en lista med filter som kommer att tillämpas på inmatningsbilden i den ordning du anger. Exempel för att skapa filter: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); Du behöver inte alla. Ställ in endast det du behöver.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | OcrInput-objekt som innehåller olika bilder @see \#OcrInput. |
| folderPath | java.lang.String | Sökväg utan bildnamn för att spara bearbetade bilder. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput.
