---
title: "图像处理"
second_title: "Aspose.OCR for Java API 参考"
description: "Aspose OCR 库的帮助类"
type: docs
weight: 19
url: /zh/java/com.aspose.ocr/imageprocessing/
---

**Inheritance:**
java.lang.Object
```
public class ImageProcessing
```

Aspose OCR 库的帮助类。允许对图像进行预处理并保存。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImageProcessing()](#ImageProcessing) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [Render(OcrInput images)](#Render-com.aspose.ocr.OcrInput) | 使用图像处理来提高 OCR 的准确性。 |
| [Save(OcrInput images, String folderPath)](#Save-com.aspose.ocr.OcrInput-java.lang.String) | 使用图像处理来提高 OCR 的准确性。 |

### ImageProcessing() {#ImageProcessing}
```
public ImageProcessing()
```


### Render(OcrInput images) {#Render-com.aspose.ocr.OcrInput}
```
public static OcrInput Render(OcrInput images)
```


使用图像处理来提高 OCR 的准确性。创建一个过滤器列表，这些过滤器将按照您指定的顺序应用于输入图像。创建过滤器的示例：PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); 您不需要全部过滤器。仅设置您需要的即可。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | 包含不同图像的 OcrInput 对象 @see \#OcrInput。 |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput in Image field.
### Save(OcrInput images, String folderPath) {#Save-com.aspose.ocr.OcrInput-java.lang.String}
```
public static OcrInput Save(OcrInput images, String folderPath)
```


使用图像处理来提高 OCR 的准确性。创建一个过滤器列表，这些过滤器将按照您指定的顺序应用于输入图像。创建过滤器的示例：PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); 您不需要全部过滤器。仅设置您需要的即可。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | 包含不同图像的 OcrInput 对象 @see \#OcrInput。 |
| folderPath | java.lang.String | 用于保存处理后图像的路径（不包含图像名称）。 |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput.
