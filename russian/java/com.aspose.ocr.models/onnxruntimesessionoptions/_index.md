---
title: "OnnxRuntimeSessionOptions"
second_title: "Aspose.OCR для Java API Reference"
description: "Параметры конфигурации для создания ONNX InferenceSession"
type: docs
weight: 20
url: /ru/java/com.aspose.ocr.models/onnxruntimesessionoptions/
---

**Inheritance:**
java.lang.Object
```
public class OnnxRuntimeSessionOptions
```

Параметры конфигурации для создания ONNX InferenceSession. Мы рекомендуем оставлять оптимизированные значения по умолчанию, если вы не полностью уверены в изменениях. Для технических деталей см. документацию ONNX Runtime.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OnnxRuntimeSessionOptions()](#OnnxRuntimeSessionOptions) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [enableCpuMemArena](#enableCpuMemArena) | Включает или отключает аллокатор арены памяти CPU, используемый ONNX Runtime. |
| [enableMemoryPattern](#enableMemoryPattern) | Включает или отключает оптимизацию шаблона памяти для входных тензоров. |
| [executionMode](#executionMode) | Режим выполнения для сессии. |
| [graphOptimizationLevel](#graphOptimizationLevel) | Уровень оптимизации графа для сессии. |
| [interOpNumThreads](#interOpNumThreads) | Количество потоков для выполнения нескольких операций параллельно. |
| [intraOpNumThreads](#intraOpNumThreads) | Количество потоков для одной операции. |


### OnnxRuntimeSessionOptions() {#OnnxRuntimeSessionOptions}
```
public OnnxRuntimeSessionOptions()
```


### enableCpuMemArena {#enableCpuMemArena}
```
public static boolean enableCpuMemArena
```


Включает или отключает аллокатор арены памяти CPU, используемый ONNX Runtime. При включении память собирается в пул и переиспользуется для повышения производительности, но может привести к увеличенному потреблению памяти в многопоточных сценариях. Отключите, чтобы снизить пиковое использование памяти за счёт производительности.

### enableMemoryPattern {#enableMemoryPattern}
```
public static boolean enableMemoryPattern
```


Включает или отключает оптимизацию шаблонов памяти для входных тензоров. При включении ONNX Runtime кэширует шаблоны выделения памяти для более быстрой работы, но может увеличить использование памяти при динамических формах входных данных. Отключите, если входы сильно различаются или чтобы уменьшить объём памяти.

### executionMode {#executionMode}
```
public static ExecutionModeOnnx executionMode
```


Режим выполнения для сеанса. По умолчанию операторы выполняются параллельно, когда это возможно.

### graphOptimizationLevel {#graphOptimizationLevel}
```
public static GraphOptimizationLevelOnnx graphOptimizationLevel
```


Уровень оптимизации графа для сеанса. По умолчанию все доступные оптимизации включены для максимальной производительности.

### interOpNumThreads {#interOpNumThreads}
```
public static int interOpNumThreads
```


Количество потоков для параллельного выполнения нескольких операций. Если включено последовательное выполнение, это значение игнорируется.

### intraOpNumThreads {#intraOpNumThreads}
```
public static int intraOpNumThreads
```


Количество потоков для одной операции.