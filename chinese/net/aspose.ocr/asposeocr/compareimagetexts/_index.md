---
title: CompareImageTexts
second_title: Aspose.OCR 适用于 .NET 的 API 参考
description: 检查两幅图像是否包含相同的文本。
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
| fullPath1 | String | Path to the first image. |
| fullPath2 | String | Path to the second image. |
| settings | RecognitionSettings | Recognition settings. |
| ignoreCase | Boolean | True - means a case-insensitive search. |

### 返回值

True if images have the same text (90% similarity).

### 另请参阅

* class [RecognitionSettings](../../recognitionsettings)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 Aspose.OCR.dll 生成 -->
