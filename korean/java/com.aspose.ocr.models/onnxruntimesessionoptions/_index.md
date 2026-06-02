---
title: "OnnxRuntimeSessionOptions"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: "ONNX InferenceSession을 생성하기 위한 구성 옵션"
type: docs
weight: 20
url: /ko/java/com.aspose.ocr.models/onnxruntimesessionoptions/
---

**Inheritance:**
java.lang.Object
```
public class OnnxRuntimeSessionOptions
```

ONNX InferenceSession을 생성하기 위한 구성 옵션입니다. 수정에 대해 확신이 없는 한 최적화된 기본값을 유지하는 것을 권장합니다. 기술적인 세부 사항은 ONNX Runtime 문서를 참조하십시오.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OnnxRuntimeSessionOptions()](#OnnxRuntimeSessionOptions) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [enableCpuMemArena](#enableCpuMemArena) | ONNX Runtime에서 사용되는 CPU 메모리 영역 할당자를 활성화하거나 비활성화합니다. |
| [enableMemoryPattern](#enableMemoryPattern) | 입력 텐서에 대한 메모리 패턴 최적화를 활성화하거나 비활성화합니다. |
| [executionMode](#executionMode) | 세션의 실행 모드. |
| [graphOptimizationLevel](#graphOptimizationLevel) | 세션의 그래프 최적화 수준. |
| [interOpNumThreads](#interOpNumThreads) | 여러 작업을 병렬로 실행하기 위한 스레드 수. |
| [intraOpNumThreads](#intraOpNumThreads) | 단일 작업에 대한 스레드 수. |


### OnnxRuntimeSessionOptions() {#OnnxRuntimeSessionOptions}
```
public OnnxRuntimeSessionOptions()
```


### enableCpuMemArena {#enableCpuMemArena}
```
public static boolean enableCpuMemArena
```


ONNX Runtime에서 사용되는 CPU 메모리 영역 할당자를 활성화하거나 비활성화합니다. 활성화하면 메모리가 풀링되어 재사용되어 성능이 향상되지만, 다중 스레드 환경에서는 메모리 사용량이 증가할 수 있습니다. 성능을 희생하더라도 피크 메모리 사용량을 줄이려면 비활성화하십시오.

### enableMemoryPattern {#enableMemoryPattern}
```
public static boolean enableMemoryPattern
```


입력 텐서에 대한 메모리 패턴 최적화를 활성화하거나 비활성화합니다. 활성화된 경우 ONNX Runtime은 더 빠른 실행을 위해 메모리 할당 패턴을 캐시하지만, 동적 입력 형태에 대해 메모리 사용량이 증가할 수 있습니다. 입력이 크게 달라지거나 메모리 사용량을 줄이려면 비활성화하십시오.

### executionMode {#executionMode}
```
public static ExecutionModeOnnx executionMode
```


세션의 실행 모드입니다. 기본적으로 연산자는 가능한 경우 동시에 실행됩니다.

### graphOptimizationLevel {#graphOptimizationLevel}
```
public static GraphOptimizationLevelOnnx graphOptimizationLevel
```


세션의 그래프 최적화 수준입니다. 기본적으로 최대 성능을 위해 사용 가능한 모든 최적화가 활성화됩니다.

### interOpNumThreads {#interOpNumThreads}
```
public static int interOpNumThreads
```


여러 연산을 병렬로 실행하기 위한 스레드 수입니다. 순차 실행이 활성화된 경우 이 값은 무시됩니다.

### intraOpNumThreads {#intraOpNumThreads}
```
public static int intraOpNumThreads
```


단일 작업에 대한 스레드 수.