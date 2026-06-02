---
title: "PreprocessImage"
second_title: "Aspose.OCR 适用于 .NET 的 API 参考"
description: "使用图像预处理来提高 OCR 的准确性。创建一个过滤器列表，这些过滤器将按照您指定的顺序应用于输入图像。例如创建过滤器：PreprocessingFilter filters  new PreprocessingFilter  PreprocessingFilter.Invert PreprocessingFilter.Threshold150 PreprocessingFilter.Binarize PreprocessingFilter.Rotate180 PreprocessingFilter.Resize30003000 Aspose.OCR.Filters.InterpolationFilterType.Box PreprocessingFilter.Scale6f PreprocessingFilter.Dilate  您不需要全部过滤器，只设置您需要的即可。"
type: docs
weight: 100
url: /zh/net/aspose.ocr/asposeocr/preprocessimage/
---
## PreprocessImage(string, PreprocessingFilter) {#preprocessimage_1}

使用图像预处理来提高 OCR 的准确性。创建一个过滤器列表，这些过滤器将按照您指定的顺序应用于输入图像。例如创建过滤器：PreprocessingFilter filters = new PreprocessingFilter { PreprocessingFilter.Invert(), PreprocessingFilter.Threshold(150), PreprocessingFilter.Binarize(), PreprocessingFilter.Rotate(180), PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box), PreprocessingFilter.Scale(6f), PreprocessingFilter.Dilate() }; 您不需要全部过滤器，只设置您需要的即可。

```csharp
public MemoryStream PreprocessImage(string fullPath, PreprocessingFilter filters)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullPath | String | 图像的完整路径。 |
| filters | PreprocessingFilter | 图像优化过滤器[`PreprocessingFilter`](../../../aspose.ocr.models.preprocessingfilters/preprocessingfilter)。 |

### 返回值

包含已修改图像的流，以便您可以保存或识别它。

### 另见

* class [PreprocessingFilter](../../../aspose.ocr.models.preprocessingfilters/preprocessingfilter)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

---

## PreprocessImage(MemoryStream, PreprocessingFilter) {#preprocessimage}

使用图像预处理来提高 OCR 的准确性。创建一个过滤器列表，这些过滤器将按照您指定的顺序应用于输入图像。例如创建过滤器：PreprocessingFilter filters = new PreprocessingFilter { PreprocessingFilter.Invert(), PreprocessingFilter.Threshold(150), PreprocessingFilter.Binarize(), PreprocessingFilter.Rotate(180), PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box), PreprocessingFilter.Scale(6f), PreprocessingFilter.Dilate() }; 您不需要全部过滤器，只设置您需要的即可。

```csharp
public MemoryStream PreprocessImage(MemoryStream stream, PreprocessingFilter filters)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | MemoryStream | 包含图像的内存流。 |
| filters | PreprocessingFilter | 图像优化过滤器[`PreprocessingFilter`](../../../aspose.ocr.models.preprocessingfilters/preprocessingfilter)。 |

### 返回值

包含已修改图像的流，以便您可以保存或识别它。

### 另见

* class [PreprocessingFilter](../../../aspose.ocr.models.preprocessingfilters/preprocessingfilter)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OCR.dll 生成 -->
