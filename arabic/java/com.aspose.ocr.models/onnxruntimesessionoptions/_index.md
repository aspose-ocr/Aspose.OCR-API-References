---
title: "OnnxRuntimeSessionOptions"
second_title: "مرجع Aspose.OCR لـ Java API"
description: "خيارات التكوين لإنشاء ONNX InferenceSession"
type: docs
weight: 20
url: /ar/java/com.aspose.ocr.models/onnxruntimesessionoptions/
---

**Inheritance:**
java.lang.Object
```
public class OnnxRuntimeSessionOptions
```

خيارات التكوين لإنشاء ONNX InferenceSession. نوصي بالحفاظ على الإعدادات الافتراضية المحسّنة ما لم تكن متأكدًا تمامًا من التعديلات. للحصول على تفاصيل تقنية، راجع وثائق ONNX Runtime.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [OnnxRuntimeSessionOptions()](#OnnxRuntimeSessionOptions) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [enableCpuMemArena](#enableCpuMemArena) | يفعل أو يعطل مخصص مساحة الذاكرة للمعالج (CPU) المستخدم من قبل ONNX Runtime. |
| [enableMemoryPattern](#enableMemoryPattern) | يفعل أو يعطل تحسين نمط الذاكرة للمتجهات المدخلة. |
| [executionMode](#executionMode) | وضع التنفيذ للجلسة. |
| [graphOptimizationLevel](#graphOptimizationLevel) | مستوى تحسين الرسم البياني للجلسة. |
| [interOpNumThreads](#interOpNumThreads) | عدد الخيوط لتشغيل عمليات متعددة بالتوازي. |
| [intraOpNumThreads](#intraOpNumThreads) | عدد الخيوط لعملية واحدة. |


### OnnxRuntimeSessionOptions() {#OnnxRuntimeSessionOptions}
```
public OnnxRuntimeSessionOptions()
```


### enableCpuMemArena {#enableCpuMemArena}
```
public static boolean enableCpuMemArena
```


يفعل أو يعطل مخصص مساحة الذاكرة للمعالج (CPU) المستخدم من قبل ONNX Runtime. عند التفعيل، يتم تجميع الذاكرة وإعادة استخدامها لأداء أفضل، لكن قد يؤدي ذلك إلى زيادة استهلاك الذاكرة في سيناريوهات متعددة الخيوط. عطل لتقليل أقصى استهلاك للذاكرة على حساب الأداء.

### enableMemoryPattern {#enableMemoryPattern}
```
public static boolean enableMemoryPattern
```


يقوم بتمكين أو تعطيل تحسين نمط الذاكرة للمتجهات المدخلة. عند التمكين، يقوم ONNX Runtime بتخزين أنماط تخصيص الذاكرة للتنفيذ الأسرع، لكن قد يزيد من استهلاك الذاكرة للأشكال المدخلة الديناميكية. عطل إذا كانت المدخلات تختلف بشكل كبير أو لتقليل حجم الذاكرة.

### executionMode {#executionMode}
```
public static ExecutionModeOnnx executionMode
```


وضع التنفيذ للجلسة. بشكل افتراضي، يتم تنفيذ المشغلات بشكل متزامن كلما كان ذلك ممكنًا.

### graphOptimizationLevel {#graphOptimizationLevel}
```
public static GraphOptimizationLevelOnnx graphOptimizationLevel
```


مستوى تحسين الرسم البياني للجلسة. بشكل افتراضي، يتم تمكين جميع التحسينات المتاحة لتحقيق أقصى أداء.

### interOpNumThreads {#interOpNumThreads}
```
public static int interOpNumThreads
```


عدد الخيوط لتشغيل عمليات متعددة بالتوازي. إذا تم تمكين التنفيذ المتسلسل، يتم تجاهل هذه القيمة.

### intraOpNumThreads {#intraOpNumThreads}
```
public static int intraOpNumThreads
```


عدد الخيوط لعملية واحدة.