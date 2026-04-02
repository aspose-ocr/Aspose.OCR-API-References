---
title: 缩放
second_title: Aspose.OCR 适用于 .NET API 参考
description: 重新缩放图像 - 放大或缩小图像分辨率。InterpolationFilterType Lanczos8
type: docs
weight: 140
url: /zh/net/aspose.ocr.models.preprocessingfilters/preprocessingfilter/scale/
---
## Scale(float) {#scale}

重新缩放图像 - 放大或缩小图像分辨率。InterpolationFilterType = Lanczos8

```csharp
public static PreprocessingFilter Scale(float ratio)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 比例 | 单精度 | 缩放因子。建议在 0.1 到 1 之间用于缩小。1 到 10 之间用于放大。 |

### Return Value

ScaleFilter 对象。

### 另请参阅

* class [PreprocessingFilter](../../preprocessingfilter)
* namespace [Aspose.OCR.Models.PreprocessingFilters](../../preprocessingfilter)
* assembly [Aspose.OCR](../../../)

---

## Scale(float, InterpolationFilterType) {#scale_1}

重新缩放图像 - 放大或缩小图像分辨率。

```csharp
public static PreprocessingFilter Scale(float ratio, InterpolationFilterType type)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 比例 | 单精度 | 缩放因子。建议在 0.1 到 1 之间用于缩小。1 到 10 之间用于放大。 |
| type | InterpolationFilterType | [`InterpolationFilterType`](../../../aspose.ocr.filters/interpolationfiltertype) |

### Return Value

ScaleFilter 对象。

### 另请参阅

* enum [InterpolationFilterType](../../../aspose.ocr.filters/interpolationfiltertype)
* class [PreprocessingFilter](../../preprocessingfilter)
* namespace [Aspose.OCR.Models.PreprocessingFilters](../../preprocessingfilter)
* assembly [Aspose.OCR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OCR.dll 生成 -->
