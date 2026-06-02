---
title: "OnnxRuntimeSessionOptions"
second_title: "Referencia de API de Aspose.OCR para Java"
description: "Opciones de configuración para crear ONNX InferenceSession"
type: docs
weight: 20
url: /es/java/com.aspose.ocr.models/onnxruntimesessionoptions/
---

**Inheritance:**
java.lang.Object
```
public class OnnxRuntimeSessionOptions
```

Opciones de configuración para crear ONNX InferenceSession. Recomendamos mantener los valores predeterminados optimizados a menos que esté absolutamente seguro de las modificaciones. Para detalles técnicos, consulte la documentación de ONNX Runtime.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OnnxRuntimeSessionOptions()](#OnnxRuntimeSessionOptions) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [enableCpuMemArena](#enableCpuMemArena) | Activa o desactiva el asignador de arena de memoria CPU utilizado por ONNX Runtime. |
| [enableMemoryPattern](#enableMemoryPattern) | Activa o desactiva la optimización de patrones de memoria para tensores de entrada. |
| [executionMode](#executionMode) | Modo de ejecución para la sesión. |
| [graphOptimizationLevel](#graphOptimizationLevel) | Nivel de optimización del grafo para la sesión. |
| [interOpNumThreads](#interOpNumThreads) | Número de hilos para ejecutar múltiples operaciones en paralelo. |
| [intraOpNumThreads](#intraOpNumThreads) | Número de hilos para una sola operación. |


### OnnxRuntimeSessionOptions() {#OnnxRuntimeSessionOptions}
```
public OnnxRuntimeSessionOptions()
```


### enableCpuMemArena {#enableCpuMemArena}
```
public static boolean enableCpuMemArena
```


Activa o desactiva el asignador de arena de memoria CPU utilizado por ONNX Runtime. Cuando está activado, la memoria se agrupa y reutiliza para un mejor rendimiento, pero puede provocar un mayor consumo de memoria en escenarios multihilo. Desactívelo para reducir el uso máximo de memoria a costa del rendimiento.

### enableMemoryPattern {#enableMemoryPattern}
```
public static boolean enableMemoryPattern
```


Habilita o deshabilita la optimización de patrones de memoria para tensores de entrada. Cuando está habilitado, ONNX Runtime almacena en caché los patrones de asignación de memoria para una ejecución más rápida, pero puede aumentar el uso de memoria para formas de entrada dinámicas. Deshabilite si las entradas varían significativamente o para reducir la huella de memoria.

### executionMode {#executionMode}
```
public static ExecutionModeOnnx executionMode
```


Modo de ejecución para la sesión. Por defecto, los operadores se ejecutan de forma concurrente, siempre que sea posible.

### graphOptimizationLevel {#graphOptimizationLevel}
```
public static GraphOptimizationLevelOnnx graphOptimizationLevel
```


Nivel de optimización del grafo para la sesión. Por defecto, todas las optimizaciones disponibles están habilitadas para obtener el máximo rendimiento.

### interOpNumThreads {#interOpNumThreads}
```
public static int interOpNumThreads
```


Número de hilos para ejecutar múltiples operaciones en paralelo. Si la ejecución secuencial está habilitada, este valor se ignora.

### intraOpNumThreads {#intraOpNumThreads}
```
public static int intraOpNumThreads
```


Número de hilos para una sola operación.