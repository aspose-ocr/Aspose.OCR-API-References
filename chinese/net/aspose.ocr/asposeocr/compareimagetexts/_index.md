---
title: "CompareImageTexts"
second_title: "Aspose.OCR 适用于 .NET 的 API 参考"
description: "检查两幅图像是否包含相同的文本。"
type: docs
weight: 40
url: /zh/net/aspose.ocr/asposeocr/compareimagetexts/
---
## AsposeOcr.CompareImageTexts method

检查两幅图像是否包含相同的文本。

```csharp
public bool CompareImageTexts(string fullPath1, string fullPath2, 
    RecognitionSettings settings = null, bool ignoreCase = true)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullPath1 | String | 第一张图像的路径。 |
| fullPath2 | String | 第二张图像的路径。 |
| settings | RecognitionSettings | 识别设置。 |
| ignoreCase | Boolean | True - 表示不区分大小写的搜索。 |

### 返回值

如果图像的文本相同（相似度 90%），则为 True。

### 另见

* class [RecognitionSettings](../../recognitionsettings)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OCR.dll 生成 -->
