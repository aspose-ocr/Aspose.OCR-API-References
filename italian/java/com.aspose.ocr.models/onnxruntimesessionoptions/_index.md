---
title: "OnnxRuntimeSessionOptions"
second_title: "Riferimento API di Aspose.OCR per Java"
description: "Opzioni di configurazione per la creazione di ONNX InferenceSession"
type: docs
weight: 20
url: /it/java/com.aspose.ocr.models/onnxruntimesessionoptions/
---

**Inheritance:**
java.lang.Object
```
public class OnnxRuntimeSessionOptions
```

Opzioni di configurazione per la creazione di ONNX InferenceSession. Si consiglia di mantenere le impostazioni predefinite ottimizzate a meno che non si sia assolutamente certi delle modifiche. Per dettagli tecnici, consultare la documentazione di ONNX Runtime.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OnnxRuntimeSessionOptions()](#OnnxRuntimeSessionOptions) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [enableCpuMemArena](#enableCpuMemArena) | Abilita o disabilita l'allocatore di arena di memoria CPU utilizzato da ONNX Runtime. |
| [enableMemoryPattern](#enableMemoryPattern) | Abilita o disabilita l'ottimizzazione del pattern di memoria per i tensori di input. |
| [executionMode](#executionMode) | Modalità di esecuzione per la sessione. |
| [graphOptimizationLevel](#graphOptimizationLevel) | Livello di ottimizzazione del grafo per la sessione. |
| [interOpNumThreads](#interOpNumThreads) | Numero di thread per eseguire più operazioni in parallelo. |
| [intraOpNumThreads](#intraOpNumThreads) | Numero di thread per un'operazione singola. |


### OnnxRuntimeSessionOptions() {#OnnxRuntimeSessionOptions}
```
public OnnxRuntimeSessionOptions()
```


### enableCpuMemArena {#enableCpuMemArena}
```
public static boolean enableCpuMemArena
```


Abilita o disabilita l'allocatore di arena di memoria CPU utilizzato da ONNX Runtime. Quando abilitato, la memoria è raggruppata e riutilizzata per migliori prestazioni, ma può comportare un aumento del consumo di memoria in scenari multithread. Disabilita per ridurre l'utilizzo di memoria di picco a scapito delle prestazioni.

### enableMemoryPattern {#enableMemoryPattern}
```
public static boolean enableMemoryPattern
```


Abilita o disabilita l'ottimizzazione del modello di memoria per i tensori di input. Quando abilitato, ONNX Runtime memorizza nella cache i modelli di allocazione della memoria per un'esecuzione più rapida, ma può aumentare l'uso della memoria per forme di input dinamiche. Disabilita se gli input variano significativamente o per ridurre l'impronta di memoria.

### executionMode {#executionMode}
```
public static ExecutionModeOnnx executionMode
```


Modalità di esecuzione per la sessione. Per impostazione predefinita, gli operatori vengono eseguiti in modo concorrente, quando possibile.

### graphOptimizationLevel {#graphOptimizationLevel}
```
public static GraphOptimizationLevelOnnx graphOptimizationLevel
```


Livello di ottimizzazione del grafo per la sessione. Per impostazione predefinita, tutte le ottimizzazioni disponibili sono abilitate per massime prestazioni.

### interOpNumThreads {#interOpNumThreads}
```
public static int interOpNumThreads
```


Numero di thread per eseguire più operazioni in parallelo. Se l'esecuzione sequenziale è abilitata, questo valore viene ignorato.

### intraOpNumThreads {#intraOpNumThreads}
```
public static int intraOpNumThreads
```


Numero di thread per un'operazione singola.