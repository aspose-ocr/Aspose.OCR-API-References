---
title: "OnnxRuntimeSessionOptions"
second_title: "Référence API d'Aspose.OCR pour Java"
description: "Options de configuration pour créer une session d'inférence ONNX"
type: docs
weight: 20
url: /fr/java/com.aspose.ocr.models/onnxruntimesessionoptions/
---

**Inheritance:**
java.lang.Object
```
public class OnnxRuntimeSessionOptions
```

Options de configuration pour créer une session d'inférence ONNX. Nous recommandons de conserver les valeurs par défaut optimisées sauf si vous êtes absolument certain des modifications. Pour les détails techniques, consultez la documentation d'ONNX Runtime.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OnnxRuntimeSessionOptions()](#OnnxRuntimeSessionOptions) |  |
## Champs

| Champ | Description |
| --- | --- |
| [enableCpuMemArena](#enableCpuMemArena) | Active ou désactive l'allocateur d'arène mémoire CPU utilisé par ONNX Runtime. |
| [enableMemoryPattern](#enableMemoryPattern) | Active ou désactive l'optimisation du modèle de mémoire pour les tenseurs d'entrée. |
| [executionMode](#executionMode) | Mode d'exécution pour la session. |
| [graphOptimizationLevel](#graphOptimizationLevel) | Niveau d'optimisation du graphe pour la session. |
| [interOpNumThreads](#interOpNumThreads) | Nombre de threads pour exécuter plusieurs opérations en parallèle. |
| [intraOpNumThreads](#intraOpNumThreads) | Nombre de threads pour une opération unique. |


### OnnxRuntimeSessionOptions() {#OnnxRuntimeSessionOptions}
```
public OnnxRuntimeSessionOptions()
```


### enableCpuMemArena {#enableCpuMemArena}
```
public static boolean enableCpuMemArena
```


Active ou désactive l'allocateur d'arène mémoire CPU utilisé par ONNX Runtime. Lorsqu'il est activé, la mémoire est regroupée et réutilisée pour de meilleures performances, mais cela peut entraîner une consommation de mémoire accrue dans les scénarios multithreads. Désactivez-le pour réduire l'utilisation maximale de la mémoire au détriment des performances.

### enableMemoryPattern {#enableMemoryPattern}
```
public static boolean enableMemoryPattern
```


Active ou désactive l'optimisation du modèle de mémoire pour les tenseurs d'entrée. Lorsqu'elle est activée, ONNX Runtime met en cache les modèles d'allocation de mémoire pour une exécution plus rapide, mais cela peut augmenter l'utilisation de la mémoire pour les formes d'entrée dynamiques. Désactivez-la si les entrées varient considérablement ou pour réduire l'empreinte mémoire.

### executionMode {#executionMode}
```
public static ExecutionModeOnnx executionMode
```


Mode d'exécution pour la session. Par défaut, les opérateurs sont exécutés de manière concurrente, chaque fois que possible.

### graphOptimizationLevel {#graphOptimizationLevel}
```
public static GraphOptimizationLevelOnnx graphOptimizationLevel
```


Niveau d'optimisation du graphe pour la session. Par défaut, toutes les optimisations disponibles sont activées pour des performances maximales.

### interOpNumThreads {#interOpNumThreads}
```
public static int interOpNumThreads
```


Nombre de threads pour exécuter plusieurs opérations en parallèle. Si l'exécution séquentielle est activée, cette valeur est ignorée.

### intraOpNumThreads {#intraOpNumThreads}
```
public static int intraOpNumThreads
```


Nombre de threads pour une opération unique.