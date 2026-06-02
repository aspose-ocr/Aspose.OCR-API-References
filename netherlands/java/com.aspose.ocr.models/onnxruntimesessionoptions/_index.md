---
title: "OnnxRuntimeSessionOptions"
second_title: "Aspose.OCR for Java API-referentie"
description: "Configuratie‑opties voor het maken van een ONNX InferenceSession"
type: docs
weight: 20
url: /nl/java/com.aspose.ocr.models/onnxruntimesessionoptions/
---

**Inheritance:**
java.lang.Object
```
public class OnnxRuntimeSessionOptions
```

Configuratie‑opties voor het maken van een ONNX InferenceSession. We raden aan de geoptimaliseerde standaardinstellingen te behouden, tenzij u absoluut zeker bent van de wijzigingen. Voor technische details, raadpleeg de ONNX Runtime‑documentatie.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [OnnxRuntimeSessionOptions()](#OnnxRuntimeSessionOptions) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [enableCpuMemArena](#enableCpuMemArena) | Schakelt de CPU‑geheugenarena‑allocator die door ONNX Runtime wordt gebruikt in of uit. |
| [enableMemoryPattern](#enableMemoryPattern) | Schakelt geheugenpatroonoptimalisatie voor invoertensors in of uit. |
| [executionMode](#executionMode) | Uitvoermodus voor de sessie. |
| [graphOptimizationLevel](#graphOptimizationLevel) | Grafiekoptimalisatieniveau voor de sessie. |
| [interOpNumThreads](#interOpNumThreads) | Aantal threads voor het parallel uitvoeren van meerdere bewerkingen. |
| [intraOpNumThreads](#intraOpNumThreads) | Aantal threads voor een enkele bewerking. |


### OnnxRuntimeSessionOptions() {#OnnxRuntimeSessionOptions}
```
public OnnxRuntimeSessionOptions()
```


### enableCpuMemArena {#enableCpuMemArena}
```
public static boolean enableCpuMemArena
```


Schakelt de CPU‑geheugenarena‑allocator die door ONNX Runtime wordt gebruikt in of uit. Wanneer ingeschakeld, wordt geheugen gebundeld en hergebruikt voor betere prestaties, maar dit kan leiden tot een hoger geheugenverbruik in multi‑threaded scenario’s. Schakel uit om het piekgeheugengebruik te verminderen ten koste van de prestaties.

### enableMemoryPattern {#enableMemoryPattern}
```
public static boolean enableMemoryPattern
```


Schakelt geheugenpatroonoptimalisatie voor invoertensors in of uit. Wanneer ingeschakeld, cachet ONNX Runtime geheugenallocatiepatronen voor snellere uitvoering, maar kan het het geheugenverbruik verhogen voor dynamische invoervormen. Schakel uit als invoer sterk varieert of om de geheugengebruik te verminderen.

### executionMode {#executionMode}
```
public static ExecutionModeOnnx executionMode
```


Uitvoermodus voor de sessie. Standaard worden operatoren gelijktijdig uitgevoerd, wanneer mogelijk.

### graphOptimizationLevel {#graphOptimizationLevel}
```
public static GraphOptimizationLevelOnnx graphOptimizationLevel
```


Grafiekoptimalisatieniveau voor de sessie. Standaard zijn alle beschikbare optimalisaties ingeschakeld voor maximale prestaties.

### interOpNumThreads {#interOpNumThreads}
```
public static int interOpNumThreads
```


Aantal threads voor het parallel uitvoeren van meerdere bewerkingen. Als sequentiële uitvoering is ingeschakeld, wordt deze waarde genegeerd.

### intraOpNumThreads {#intraOpNumThreads}
```
public static int intraOpNumThreads
```


Aantal threads voor een enkele bewerking.