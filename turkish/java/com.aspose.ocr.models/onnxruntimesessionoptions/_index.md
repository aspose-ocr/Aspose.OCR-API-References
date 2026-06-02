---
title: "OnnxRuntimeSessionOptions"
second_title: "Aspose.OCR for Java API Referansı"
description: "ONNX InferenceSession oluşturmak için yapılandırma seçenekleri"
type: docs
weight: 20
url: /tr/java/com.aspose.ocr.models/onnxruntimesessionoptions/
---

**Inheritance:**
java.lang.Object
```
public class OnnxRuntimeSessionOptions
```

ONNX InferenceSession oluşturmak için yapılandırma seçenekleri. Değişikliklerden tamamen emin olmadığınız sürece optimize edilmiş varsayılanları korumanızı öneririz. Teknik detaylar için ONNX Runtime belgelerine bakın.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OnnxRuntimeSessionOptions()](#OnnxRuntimeSessionOptions) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [enableCpuMemArena](#enableCpuMemArena) | ONNX Runtime tarafından kullanılan CPU bellek arena ayırıcıyı etkinleştirir veya devre dışı bırakır. |
| [enableMemoryPattern](#enableMemoryPattern) | Girdi tensörleri için bellek deseni optimizasyonunu etkinleştirir veya devre dışı bırakır. |
| [executionMode](#executionMode) | Oturum için yürütme modu. |
| [graphOptimizationLevel](#graphOptimizationLevel) | Oturum için grafik optimizasyon seviyesi. |
| [interOpNumThreads](#interOpNumThreads) | Paralel olarak birden fazla işlem çalıştırmak için kullanılan iş parçacığı sayısı. |
| [intraOpNumThreads](#intraOpNumThreads) | Tek bir işlem için iş parçacığı sayısı. |


### OnnxRuntimeSessionOptions() {#OnnxRuntimeSessionOptions}
```
public OnnxRuntimeSessionOptions()
```


### enableCpuMemArena {#enableCpuMemArena}
```
public static boolean enableCpuMemArena
```


ONNX Runtime tarafından kullanılan CPU bellek arena ayırıcıyı etkinleştirir veya devre dışı bırakır. Etkinleştirildiğinde, bellek daha iyi performans için havuzlanır ve yeniden kullanılır, ancak çok iş parçacıklı senaryolarda bellek tüketiminin artmasına neden olabilir. Performans pahasına tepe bellek kullanımını azaltmak için devre dışı bırakın.

### enableMemoryPattern {#enableMemoryPattern}
```
public static boolean enableMemoryPattern
```


Giriş tensörleri için bellek deseni optimizasyonunu etkinleştirir veya devre dışı bırakır. Etkinleştirildiğinde, ONNX Runtime daha hızlı yürütme için bellek tahsis desenlerini önbelleğe alır, ancak dinamik giriş şekilleri için bellek kullanımını artırabilir. Girişler önemli ölçüde değişiyorsa veya bellek ayak izini azaltmak istiyorsanız devre dışı bırakın.

### executionMode {#executionMode}
```
public static ExecutionModeOnnx executionMode
```


Oturum için yürütme modu. Varsayılan olarak, operatörler mümkün olduğunda eşzamanlı olarak yürütülür.

### graphOptimizationLevel {#graphOptimizationLevel}
```
public static GraphOptimizationLevelOnnx graphOptimizationLevel
```


Oturum için grafik optimizasyon seviyesi. Varsayılan olarak, maksimum performans için mevcut tüm optimizasyonlar etkinleştirilir.

### interOpNumThreads {#interOpNumThreads}
```
public static int interOpNumThreads
```


Birden fazla işlemi paralel olarak çalıştırmak için kullanılan iş parçacığı sayısı. Sıralı yürütme etkinleştirilmişse, bu değer yok sayılır.

### intraOpNumThreads {#intraOpNumThreads}
```
public static int intraOpNumThreads
```


Tek bir işlem için iş parçacığı sayısı.