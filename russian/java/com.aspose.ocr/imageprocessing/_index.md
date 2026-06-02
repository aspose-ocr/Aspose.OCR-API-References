---
title: "ImageProcessing"
second_title: "Aspose.OCR для Java API Reference"
description: "Вспомогательный класс для библиотеки Aspose OCR"
type: docs
weight: 19
url: /ru/java/com.aspose.ocr/imageprocessing/
---

**Inheritance:**
java.lang.Object
```
public class ImageProcessing
```

Вспомогательный класс для библиотеки Aspose OCR. Позволяет предварительно обрабатывать и сохранять изображения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImageProcessing()](#ImageProcessing) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [Render(OcrInput images)](#Render-com.aspose.ocr.OcrInput) | Используйте обработку изображений для повышения точности OCR. |
| [Save(OcrInput images, String folderPath)](#Save-com.aspose.ocr.OcrInput-java.lang.String) | Используйте обработку изображений для повышения точности OCR. |

### ImageProcessing() {#ImageProcessing}
```
public ImageProcessing()
```


### Render(OcrInput images) {#Render-com.aspose.ocr.OcrInput}
```
public static OcrInput Render(OcrInput images)
```


Используйте обработку изображений для повышения точности OCR. Создайте список фильтров, которые будут применяться к входному изображению в указанном вами порядке. Пример создания фильтров: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); Вам не нужны все из них. Установите только то, что необходимо.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Объект OcrInput, содержащий разные изображения @see \#OcrInput. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput in Image field.
### Save(OcrInput images, String folderPath) {#Save-com.aspose.ocr.OcrInput-java.lang.String}
```
public static OcrInput Save(OcrInput images, String folderPath)
```


Используйте обработку изображений для повышения точности OCR. Создайте список фильтров, которые будут применяться к входному изображению в указанном вами порядке. Пример создания фильтров: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); Вам не нужны все из них. Установите только то, что необходимо.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Объект OcrInput, содержащий разные изображения @see \#OcrInput. |
| folderPath | java.lang.String | Путь без имён изображений для сохранения обработанных изображений. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput.
