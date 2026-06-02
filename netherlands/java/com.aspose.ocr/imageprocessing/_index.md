---
title: "Afbeeldingsverwerking"
second_title: "Aspose.OCR for Java API-referentie"
description: "Helperklasse voor Aspose OCR-bibliotheek"
type: docs
weight: 19
url: /nl/java/com.aspose.ocr/imageprocessing/
---

**Inheritance:**
java.lang.Object
```
public class ImageProcessing
```

Helperklasse voor Aspose OCR-bibliotheek. Stelt toe om afbeeldingen voor te verwerken en op te slaan.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ImageProcessing()](#ImageProcessing) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [Render(OcrInput images)](#Render-com.aspose.ocr.OcrInput) | Gebruik afbeeldingsverwerking om de nauwkeurigheid van OCR te verbeteren. |
| [Save(OcrInput images, String folderPath)](#Save-com.aspose.ocr.OcrInput-java.lang.String) | Gebruik afbeeldingsverwerking om de nauwkeurigheid van OCR te verbeteren. |

### ImageProcessing() {#ImageProcessing}
```
public ImageProcessing()
```


### Render(OcrInput images) {#Render-com.aspose.ocr.OcrInput}
```
public static OcrInput Render(OcrInput images)
```


Gebruik afbeeldingsverwerking om de nauwkeurigheid van OCR te verbeteren. Maak een lijst met filters die op de invoerafbeelding worden toegepast in de volgorde die u opgeeft. Voorbeeld om filters te maken: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); U hoeft niet alle filters te gebruiken. Stel alleen in wat u nodig heeft.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | OcrInput-object dat verschillende afbeeldingen bevat @see \#OcrInput. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput in Image field.
### Save(OcrInput images, String folderPath) {#Save-com.aspose.ocr.OcrInput-java.lang.String}
```
public static OcrInput Save(OcrInput images, String folderPath)
```


Gebruik afbeeldingsverwerking om de nauwkeurigheid van OCR te verbeteren. Maak een lijst met filters die op de invoerafbeelding worden toegepast in de volgorde die u opgeeft. Voorbeeld om filters te maken: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); U hoeft niet alle filters te gebruiken. Stel alleen in wat u nodig heeft.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | OcrInput-object dat verschillende afbeeldingen bevat @see \#OcrInput. |
| folderPath | java.lang.String | Pad zonder afbeeldingsnamen voor het opslaan van verwerkte afbeeldingen. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput.
