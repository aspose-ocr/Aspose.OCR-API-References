---
title: "ImageTextDiff"
second_title: "Aspose.OCR 适用于 .NET 的 API 参考"
description: "比较两幅图像上的文本，并返回一个表示相似度的数值，范围为 0 到 1。"
type: docs
weight: 130
url: /zh/net/aspose.ocr/asposeocr/imagetextdiff/
---
## AsposeOcr.ImageTextDiff method

比较两幅图像上的文本并返回一个表示相似度的数字（0 到 1）。

```csharp
public float ImageTextDiff(string fullPath1, string fullPath2, RecognitionSettings settings = null, 
    bool ignoreCase = true, bool autoSkew = true)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullPath1 | String | 第一张图像的路径。 |
| fullPath2 | String | 第二张图像的路径。 |
| settings | RecognitionSettings | 识别设置。 |
| ignoreCase | Boolean | True - 表示不区分大小写的搜索。 |
| autoSkew | Boolean | 启用自动图像倾斜校正。 |

### 返回值

0 表示文本完全不同；1 表示文本完全相同。

### 另见

* class [RecognitionSettings](../../recognitionsettings)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OCR.dll 生成 -->
