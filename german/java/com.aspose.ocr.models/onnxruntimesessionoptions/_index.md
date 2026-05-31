---
title: "OnnxRuntimeSessionOptions"
second_title: "Aspose.OCR für Java API-Referenz"
description: "Konfigurationsoptionen für die Erstellung einer ONNX InferenceSession"
type: docs
weight: 20
url: /de/java/com.aspose.ocr.models/onnxruntimesessionoptions/
---

**Inheritance:**
java.lang.Object
```
public class OnnxRuntimeSessionOptions
```

Konfigurationsoptionen für die Erstellung einer ONNX InferenceSession. Wir empfehlen, die optimierten Vorgaben beizubehalten, es sei denn, Sie sind sich absolut sicher über die Änderungen. Für technische Details siehe die ONNX Runtime Dokumentation.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OnnxRuntimeSessionOptions()](#OnnxRuntimeSessionOptions) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [enableCpuMemArena](#enableCpuMemArena) | Aktiviert oder deaktiviert den von ONNX Runtime verwendeten CPU‑Speicher‑Arena‑Allocator. |
| [enableMemoryPattern](#enableMemoryPattern) | Aktiviert oder deaktiviert die Speicher‑Muster‑Optimierung für Eingabetensoren. |
| [executionMode](#executionMode) | Ausführungsmodus für die Sitzung. |
| [graphOptimizationLevel](#graphOptimizationLevel) | Graph‑Optimierungsstufe für die Sitzung. |
| [interOpNumThreads](#interOpNumThreads) | Anzahl der Threads für die parallele Ausführung mehrerer Operationen. |
| [intraOpNumThreads](#intraOpNumThreads) | Anzahl der Threads für eine einzelne Operation. |


### OnnxRuntimeSessionOptions() {#OnnxRuntimeSessionOptions}
```
public OnnxRuntimeSessionOptions()
```


### enableCpuMemArena {#enableCpuMemArena}
```
public static boolean enableCpuMemArena
```


Aktiviert oder deaktiviert den von ONNX Runtime verwendeten CPU‑Speicher‑Arena‑Allocator. Wenn aktiviert, wird der Speicher gebündelt und wiederverwendet, um die Leistung zu verbessern, kann jedoch in multithreaded Szenarien zu erhöhtem Speicherverbrauch führen. Deaktivieren Sie diese Option, um den Spitzen‑Speicherverbrauch auf Kosten der Leistung zu reduzieren.

### enableMemoryPattern {#enableMemoryPattern}
```
public static boolean enableMemoryPattern
```


Aktiviert oder deaktiviert die Optimierung von Speichermustern für Eingabetensoren. Wenn aktiviert, cached ONNX Runtime Speicherzuweisungsmuster für schnellere Ausführung, kann jedoch den Speicherverbrauch bei dynamischen Eingabeformen erhöhen. Deaktivieren Sie dies, wenn Eingaben stark variieren oder um den Speicherverbrauch zu reduzieren.

### executionMode {#executionMode}
```
public static ExecutionModeOnnx executionMode
```


Ausführungsmodus für die Sitzung. Standardmäßig werden Operatoren, wann immer möglich, gleichzeitig ausgeführt.

### graphOptimizationLevel {#graphOptimizationLevel}
```
public static GraphOptimizationLevelOnnx graphOptimizationLevel
```


Graphoptimierungsstufe für die Sitzung. Standardmäßig sind alle verfügbaren Optimierungen für maximale Leistung aktiviert.

### interOpNumThreads {#interOpNumThreads}
```
public static int interOpNumThreads
```


Anzahl der Threads für die parallele Ausführung mehrerer Operationen. Wenn sequentielle Ausführung aktiviert ist, wird dieser Wert ignoriert.

### intraOpNumThreads {#intraOpNumThreads}
```
public static int intraOpNumThreads
```


Anzahl der Threads für eine einzelne Operation.