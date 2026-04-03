---
title: IOcrAIPostProcessor
second_title: Aspose.OCR 适用于 .NET 的 API 参考
description: 用于对 OCR 识别结果应用基于 AI 的后处理的接口。
type: docs
weight: 580
url: /zh/net/aspose.ocr.ai/iocraipostprocessor/
---
## IOcrAIPostProcessor interface

用于对 OCR 识别结果应用基于 AI 的后处理的接口。

```csharp
public interface IOcrAIPostProcessor
```

## 方法

| Name | 描述 |
| --- | --- |
| [Process](../../aspose.ocr.ai/iocraipostprocessor/process#process_1)(List&lt;string&gt;) | 使用此 AI 后处理器处理文本结果列表。 |
| [Process](../../aspose.ocr.ai/iocraipostprocessor/process#process)(OcrOutput) | 使用此 AI 后处理器处理 OCR 结果，可选地在指定模式或区域内检测表格。 |
| [SetAI](../../aspose.ocr.ai/iocraipostprocessor/setai)(AsposeAI) | 注入一个 AsposeAI 类的实例，以提供 AI 功能访问。这使得处理器可以与特定的 AI 实现解耦。 |
| [SetDefaultModel](../../aspose.ocr.ai/iocraipostprocessor/setdefaultmodel)(AsposeAIModelConfig) | 设置此处理器使用的默认 AI 模型配置。 |

### 另请参阅

* namespace [Aspose.OCR.AI](../../aspose.ocr.ai)
* assembly [Aspose.OCR](../../)

<!-- 请勿编辑：由 xmldoccmd 为 Aspose.OCR.dll 生成 -->
