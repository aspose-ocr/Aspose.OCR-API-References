---
title: SetPostProcessor
second_title: Aspose.OCR 适用于 .NET 的 API 参考
description: Adds an AI postprocessor to be applied to OCR results. If customSettings is provided the specified or default AI model will be loaded and configured automatically before applying the postprocessor.
type: docs
weight: 80
url: /zh/net/aspose.ocr.ai/asposeai/setpostprocessor/
---
## AsposeAI.SetPostProcessor method

向 OCR 结果添加一个 AI 后处理器。如果提供了 *customSettings*，将在应用后处理器之前自动加载并配置指定的或默认的 AI 模型。

```csharp
public void SetPostProcessor(IOcrAIPostProcessor processor, 
    AsposeAIModelConfig customSettings = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| processor | IOcrAIPostProcessor | An implementation of [`IOcrAIPostProcessor`](../../iocraipostprocessor) that defines the logic for AI-based post-processing (e.g., spell-checking, table extraction, or layout correction). |
| customSettings | AsposeAIModelConfig | The custom AI model configuration to use. If provided, the model specified in [`AsposeAIModelConfig`](../../asposeaimodelconfig) will be automatically loaded and applied. |

### 另请参阅

* interface [IOcrAIPostProcessor](../../iocraipostprocessor)
* class [AsposeAIModelConfig](../../asposeaimodelconfig)
* class [AsposeAI](../../asposeai)
* namespace [Aspose.OCR.AI](../../asposeai)
* assembly [Aspose.OCR](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 Aspose.OCR.dll 生成 -->
