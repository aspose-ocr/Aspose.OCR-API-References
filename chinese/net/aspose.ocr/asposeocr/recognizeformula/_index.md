---
title: RecognizeFormula
second_title: Aspose.OCR 适用于 .NET API 参考
description: 识别提供的输入图像中的数学公式。
type: docs
weight: 170
url: /zh/net/aspose.ocr/asposeocr/recognizeformula/
---
## AsposeOcr.RecognizeFormula method

识别提供的输入图像中的数学公式。

```csharp
public OcrOutput RecognizeFormula(OcrInput images, bool detectAreas = true)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图像 | OcrInput | 输入图像包含一个或多个待识别的数学表达式。支持多页或多帧 OCR 输入。 |
| detectAreas | Boolean | 如果设置为 `true`，将在执行识别前自动检测并隔离公式区域。如果设置为 `false`，则将整幅图像视为公式进行处理。 |

### Return Value

一个 [`OcrOutput`](../../ocroutput) 对象，包含已识别的公式文本、检测置信度分数和位置信息。

### 另请参阅

* class [OcrOutput](../../ocroutput)
* class [OcrInput](../../ocrinput)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OCR.dll 生成 -->
