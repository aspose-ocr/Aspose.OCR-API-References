---
title: Scale
second_title: Aspose.OCR 适用于 .NET 的 API 参考
description: Rescale image - Upscale or downscale image resolution. InterpolationFilterType  Lanczos8
type: docs
weight: 140
url: /zh/net/aspose.ocr.models.preprocessingfilters/preprocessingfilter/scale/
---
## Scale(float) {#scale}

重新缩放图像——放大或缩小图像分辨率。InterpolationFilterType = Lanczos8

```csharp
public static PreprocessingFilter Scale(float ratio)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ratio | Single | The scaling factor. Recommended from 0.1 to 1 to shrink. From 1 to 10 to enlarge. |

### 返回值

ScaleFilter object.

### 另请参阅

* class [PreprocessingFilter](../../preprocessingfilter)
* namespace [Aspose.OCR.Models.PreprocessingFilters](../../preprocessingfilter)
* assembly [Aspose.OCR](../../../)

---

## Scale(float, InterpolationFilterType) {#scale_1}

重新缩放图像——放大或缩小图像分辨率。

```csharp
public static PreprocessingFilter Scale(float ratio, InterpolationFilterType type)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ratio | Single | The scaling factor. Recommended from 0.1 to 1 to shrink. From 1 to 10 to enlarge. |
| type | InterpolationFilterType | [`InterpolationFilterType`](../../../aspose.ocr.filters/interpolationfiltertype) |

### 返回值

ScaleFilter object.

### 另请参阅

* enum [InterpolationFilterType](../../../aspose.ocr.filters/interpolationfiltertype)
* class [PreprocessingFilter](../../preprocessingfilter)
* namespace [Aspose.OCR.Models.PreprocessingFilters](../../preprocessingfilter)
* assembly [Aspose.OCR](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 Aspose.OCR.dll 生成 -->
