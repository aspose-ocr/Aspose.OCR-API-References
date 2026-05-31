---
title: "Bildverarbeitung"
second_title: "Aspose.OCR für Java API-Referenz"
description: "Hilfsklasse für die Aspose OCR-Bibliothek"
type: docs
weight: 19
url: /de/java/com.aspose.ocr/imageprocessing/
---

**Inheritance:**
java.lang.Object
```
public class ImageProcessing
```

Hilfsklasse für die Aspose OCR-Bibliothek. Ermöglicht das Vorverarbeiten und Speichern von Bildern.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImageProcessing()](#ImageProcessing) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Render(OcrInput images)](#Render-com.aspose.ocr.OcrInput) | Verwenden Sie Bildverarbeitung, um die Genauigkeit der OCR zu verbessern. |
| [Save(OcrInput images, String folderPath)](#Save-com.aspose.ocr.OcrInput-java.lang.String) | Verwenden Sie Bildverarbeitung, um die Genauigkeit der OCR zu verbessern. |

### ImageProcessing() {#ImageProcessing}
```
public ImageProcessing()
```


### Render(OcrInput images) {#Render-com.aspose.ocr.OcrInput}
```
public static OcrInput Render(OcrInput images)
```


Verwenden Sie Bildverarbeitung, um die Genauigkeit der OCR zu verbessern. Erstellen Sie eine Liste von Filtern, die in der von Ihnen angegebenen Reihenfolge auf das Eingabebild angewendet werden. Beispiel zum Erstellen von Filtern: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); Sie benötigen nicht alle. Setzen Sie nur das, was Sie benötigen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | OcrInput-Objekt, das verschiedene Bilder enthält @see \#OcrInput. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput in Image field.
### Save(OcrInput images, String folderPath) {#Save-com.aspose.ocr.OcrInput-java.lang.String}
```
public static OcrInput Save(OcrInput images, String folderPath)
```


Verwenden Sie Bildverarbeitung, um die Genauigkeit der OCR zu verbessern. Erstellen Sie eine Liste von Filtern, die in der von Ihnen angegebenen Reihenfolge auf das Eingabebild angewendet werden. Beispiel zum Erstellen von Filtern: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); Sie benötigen nicht alle. Setzen Sie nur das, was Sie benötigen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | OcrInput-Objekt, das verschiedene Bilder enthält @see \#OcrInput. |
| folderPath | java.lang.String | Pfad ohne Bildnamen zum Speichern der verarbeiteten Bilder. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput.
