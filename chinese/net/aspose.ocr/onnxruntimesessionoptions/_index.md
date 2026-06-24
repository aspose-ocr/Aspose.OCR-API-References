---
title: "OnnxRuntimeSessionOptions"
second_title: "Aspose.OCR 适用于 .NET 的 API 参考"
description: "用于创建 ONNX InferenceSession 的配置选项。我们建议保留优化后的默认值，除非您对修改绝对确定。有关技术细节，请参阅 ONNX Runtime 文档。"
type: docs
weight: 230
url: /zh/net/aspose.ocr/onnxruntimesessionoptions/
---
## OnnxRuntimeSessionOptions class

创建 ONNX InferenceSession 的配置选项。除非您对修改绝对确定，否则建议保留优化的默认设置。有关技术细节，请参阅 ONNX Runtime 文档。

```csharp
public static class OnnxRuntimeSessionOptions
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [EnableCpuMemArena](../../aspose.ocr/onnxruntimesessionoptions/enablecpumemarena) { get; set; } | 启用或禁用 ONNX Runtime 使用的 CPU 内存 arena 分配器。启用后，内存会被池化并复用以获得更好性能，但在多线程场景下可能导致内存消耗增加。禁用可在牺牲性能的情况下降低峰值内存使用。 |
| static [EnableMemoryPattern](../../aspose.ocr/onnxruntimesessionoptions/enablememorypattern) { get; set; } | 启用或禁用输入张量的内存模式优化。启用后，ONNX Runtime 会缓存内存分配模式以加快执行，但可能会增加动态输入形状的内存使用量。如果输入差异显著或需要减少内存占用，请禁用。 |
| static [ExecutionMode](../../aspose.ocr/onnxruntimesessionoptions/executionmode) { get; set; } | 会话的执行模式。默认情况下，运算符会在可能的情况下并发执行。 |
| static [GraphOptimizationLevel](../../aspose.ocr/onnxruntimesessionoptions/graphoptimizationlevel) { get; set; } | 会话的图优化级别。默认情况下，已启用所有可用的优化以获得最大性能。 |
| static [InterOpNumThreads](../../aspose.ocr/onnxruntimesessionoptions/interopnumthreads) { get; set; } | 并行运行多个操作的线程数。如果在 ExecutionMode 属性中启用了顺序执行 (ExecutionModeOnnx.ORT_SEQUENTIAL)，此值将被忽略。 |
| static [IntraOpNumThreads](../../aspose.ocr/onnxruntimesessionoptions/intraopnumthreads) { get; set; } | 单个操作的线程数。 |

### 另见

* namespace [Aspose.OCR](../../aspose.ocr)
* assembly [Aspose.OCR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OCR.dll 生成 -->
