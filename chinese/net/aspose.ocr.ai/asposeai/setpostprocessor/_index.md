---
title: "SetPostProcessor"
second_title: "Aspose.OCR 适用于 .NET 的 API 参考"
description: "添加一个将在 OCR 结果上应用的 AI 后处理器。如果提供了 customSettings，则将在应用后处理器之前自动加载并配置指定的或默认的 AI 模型。"
type: docs
weight: 80
url: /zh/net/aspose.ocr.ai/asposeai/setpostprocessor/
---
## AsposeAI.SetPostProcessor method

添加一个将在 OCR 结果上应用的 AI 后处理器。如果提供了 *customSettings*，将在应用后处理器之前自动加载并配置指定的或默认的 AI 模型。

```csharp
public void SetPostProcessor(IOcrAIPostProcessor processor, 
    AsposeAIModelConfig customSettings = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| processor | IOcrAIPostProcessor | [`IOcrAIPostProcessor`](../../iocraipostprocessor) 的实现，定义了基于 AI 的后处理逻辑（例如拼写检查、表格提取或布局校正）。 |
| customSettings | AsposeAIModelConfig | 要使用的自定义 AI 模型配置。如果提供，将自动加载并应用在 [`AsposeAIModelConfig`](../../asposeaimodelconfig) 中指定的模型。 |

### 另见

* interface [IOcrAIPostProcessor](../../iocraipostprocessor)
* class [AsposeAIModelConfig](../../asposeaimodelconfig)
* class [AsposeAI](../../asposeai)
* namespace [Aspose.OCR.AI](../../asposeai)
* assembly [Aspose.OCR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OCR.dll 生成 -->
