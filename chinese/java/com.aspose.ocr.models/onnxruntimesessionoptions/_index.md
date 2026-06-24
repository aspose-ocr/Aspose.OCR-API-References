---
title: "OnnxRuntimeSessionOptions"
second_title: "Aspose.OCR for Java API 参考"
description: "创建 ONNX InferenceSession 的配置选项"
type: docs
weight: 20
url: /zh/java/com.aspose.ocr.models/onnxruntimesessionoptions/
---

**Inheritance:**
java.lang.Object
```
public class OnnxRuntimeSessionOptions
```

创建 ONNX InferenceSession 的配置选项。除非您对修改非常确定，否则建议保留优化后的默认设置。有关技术细节，请参阅 ONNX Runtime 文档。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OnnxRuntimeSessionOptions()](#OnnxRuntimeSessionOptions) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [enableCpuMemArena](#enableCpuMemArena) | 启用或禁用 ONNX Runtime 使用的 CPU 内存 arena 分配器。 |
| [enableMemoryPattern](#enableMemoryPattern) | 启用或禁用输入张量的内存模式优化。 |
| [executionMode](#executionMode) | 会话的执行模式。 |
| [graphOptimizationLevel](#graphOptimizationLevel) | 会话的图优化级别。 |
| [interOpNumThreads](#interOpNumThreads) | 并行运行多个操作的线程数。 |
| [intraOpNumThreads](#intraOpNumThreads) | 单个操作的线程数。 |


### OnnxRuntimeSessionOptions() {#OnnxRuntimeSessionOptions}
```
public OnnxRuntimeSessionOptions()
```


### enableCpuMemArena {#enableCpuMemArena}
```
public static boolean enableCpuMemArena
```


启用或禁用 ONNX Runtime 使用的 CPU 内存 arena 分配器。启用后，内存会被池化并重复使用以提升性能，但在多线程场景下可能导致内存消耗增加。禁用可在牺牲性能的情况下降低峰值内存使用。

### enableMemoryPattern {#enableMemoryPattern}
```
public static boolean enableMemoryPattern
```


为输入张量启用或禁用内存模式优化。启用后，ONNX Runtime 会缓存内存分配模式以加快执行，但可能会增加动态输入形状的内存使用量。如果输入差异显著或需要降低内存占用，请禁用。

### executionMode {#executionMode}
```
public static ExecutionModeOnnx executionMode
```


会话的执行模式。默认情况下，运算符会在可能时并发执行。

### graphOptimizationLevel {#graphOptimizationLevel}
```
public static GraphOptimizationLevelOnnx graphOptimizationLevel
```


会话的图优化级别。默认情况下，已启用所有可用优化以获得最大性能。

### interOpNumThreads {#interOpNumThreads}
```
public static int interOpNumThreads
```


并行运行多个操作的线程数。如果已启用顺序执行，则此值将被忽略。

### intraOpNumThreads {#intraOpNumThreads}
```
public static int intraOpNumThreads
```


单个操作的线程数。