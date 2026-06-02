---
title: "OnnxRuntimeSessionOptions"
second_title: "Aspose.OCR för Java API-referens"
description: "Konfigurationsalternativ för att skapa ONNX InferenceSession"
type: docs
weight: 20
url: /sv/java/com.aspose.ocr.models/onnxruntimesessionoptions/
---

**Inheritance:**
java.lang.Object
```
public class OnnxRuntimeSessionOptions
```

Konfigurationsalternativ för att skapa ONNX InferenceSession. Vi rekommenderar att behålla de optimerade standardinställningarna såvida du inte är helt säker på ändringarna. För tekniska detaljer, se ONNX Runtime-dokumentationen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [OnnxRuntimeSessionOptions()](#OnnxRuntimeSessionOptions) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [enableCpuMemArena](#enableCpuMemArena) | Aktiverar eller inaktiverar CPU‑minnesarenans allokerare som används av ONNX Runtime. |
| [enableMemoryPattern](#enableMemoryPattern) | Aktiverar eller inaktiverar minnesmönsteroptimering för inmatningstensorer. |
| [executionMode](#executionMode) | Exekveringsläge för sessionen. |
| [graphOptimizationLevel](#graphOptimizationLevel) | Grafoptimeringsnivå för sessionen. |
| [interOpNumThreads](#interOpNumThreads) | Antal trådar för att köra flera operationer parallellt. |
| [intraOpNumThreads](#intraOpNumThreads) | Antal trådar för en enskild operation. |


### OnnxRuntimeSessionOptions() {#OnnxRuntimeSessionOptions}
```
public OnnxRuntimeSessionOptions()
```


### enableCpuMemArena {#enableCpuMemArena}
```
public static boolean enableCpuMemArena
```


Aktiverar eller inaktiverar CPU‑minnesarenans allokerare som används av ONNX Runtime. När den är aktiverad poolas minnet och återanvänds för bättre prestanda, men kan leda till ökad minnesförbrukning i flertrådade scenarier. Inaktivera för att minska toppminnesanvändningen på bekostnad av prestanda.

### enableMemoryPattern {#enableMemoryPattern}
```
public static boolean enableMemoryPattern
```


Aktiverar eller inaktiverar minnesmönsteroptimering för inmatningstensorer. När den är aktiverad cachar ONNX Runtime minnesallokeringsmönster för snabbare körning, men kan öka minnesanvändningen för dynamiska inmatningsformer. Inaktivera om indata varierar kraftigt eller för att minska minnesfotavtrycket.

### executionMode {#executionMode}
```
public static ExecutionModeOnnx executionMode
```


Exekveringsläge för sessionen. Som standard körs operatorer samtidigt, när det är möjligt.

### graphOptimizationLevel {#graphOptimizationLevel}
```
public static GraphOptimizationLevelOnnx graphOptimizationLevel
```


Grafoptimeringsnivå för sessionen. Som standard är alla tillgängliga optimeringar aktiverade för maximal prestanda.

### interOpNumThreads {#interOpNumThreads}
```
public static int interOpNumThreads
```


Antal trådar för att köra flera operationer parallellt. Om sekventiell exekvering är aktiverad ignoreras detta värde.

### intraOpNumThreads {#intraOpNumThreads}
```
public static int intraOpNumThreads
```


Antal trådar för en enskild operation.