---
title: "RecognizeFormula"
second_title: "Aspose.OCR 适用于 .NET 的 API 参考"
description: "从提供的输入图像中识别数学公式。"
type: docs
weight: 180
url: /zh/net/aspose.ocr/asposeocr/recognizeformula/
---
## AsposeOcr.RecognizeFormula method

从提供的输入图像中识别数学公式。

```csharp
public OcrOutput RecognizeFormula(OcrInput images, bool detectAreas = true)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图像 | OcrInput | 输入图像包含一个或多个待识别的数学表达式。支持多页或多帧 OCR 输入。 |
| detectAreas | Boolean | 如果设置为 `true`，将在执行识别前自动检测并分离公式区域。如果设置为 `false`，则将整幅图像作为公式处理。 |

### 返回值

一个包含已识别公式文本、检测置信度分数和位置信息的 [`OcrOutput`](../../ocroutput) 对象。

### 另见

* class [OcrOutput](../../ocroutput)
* class [OcrInput](../../ocrinput)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OCR.dll 生成 -->
