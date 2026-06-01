---
title: "OnnxRuntimeSessionOptions"
second_title: "Aspose.OCR जावा के लिए API संदर्भ"
description: "ONNX InferenceSession बनाने के लिए कॉन्फ़िगरेशन विकल्प।"
type: docs
weight: 20
url: /hi/java/com.aspose.ocr.models/onnxruntimesessionoptions/
---

**Inheritance:**
java.lang.Object
```
public class OnnxRuntimeSessionOptions
```

ONNX InferenceSession बनाने के लिए कॉन्फ़िगरेशन विकल्प। हम अनुशंसा करते हैं कि आप अनुकूलित डिफ़ॉल्ट को रखें जब तक कि आप संशोधनों के बारे में पूरी तरह निश्चित न हों। तकनीकी विवरणों के लिए, ONNX Runtime दस्तावेज़ देखें।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [OnnxRuntimeSessionOptions()](#OnnxRuntimeSessionOptions) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [enableCpuMemArena](#enableCpuMemArena) | ONNX Runtime द्वारा उपयोग किए जाने वाले CPU मेमोरी एरीना अलोकेटर को सक्षम या अक्षम करता है। |
| [enableMemoryPattern](#enableMemoryPattern) | इनपुट टेन्सर्स के लिए मेमोरी पैटर्न अनुकूलन को सक्षम या अक्षम करता है। |
| [executionMode](#executionMode) | सेशन के लिए निष्पादन मोड। |
| [graphOptimizationLevel](#graphOptimizationLevel) | सेशन के लिए ग्राफ़ अनुकूलन स्तर। |
| [interOpNumThreads](#interOpNumThreads) | समांतर रूप से कई ऑपरेशनों को चलाने के लिए थ्रेड्स की संख्या। |
| [intraOpNumThreads](#intraOpNumThreads) | एकल ऑपरेशन के लिए थ्रेड्स की संख्या। |


### OnnxRuntimeSessionOptions() {#OnnxRuntimeSessionOptions}
```
public OnnxRuntimeSessionOptions()
```


### enableCpuMemArena {#enableCpuMemArena}
```
public static boolean enableCpuMemArena
```


ONNX Runtime द्वारा उपयोग किए जाने वाले CPU मेमोरी एरीना अलोकेटर को सक्षम या अक्षम करता है। सक्षम होने पर, मेमोरी को पूल किया जाता है और बेहतर प्रदर्शन के लिए पुन: उपयोग किया जाता है, लेकिन मल्टी-थ्रेडेड परिदृश्यों में मेमोरी खपत बढ़ सकती है। प्रदर्शन की कीमत पर पीक मेमोरी उपयोग को कम करने के लिए अक्षम करें।

### enableMemoryPattern {#enableMemoryPattern}
```
public static boolean enableMemoryPattern
```


इनपुट टेन्सर्स के लिए मेमोरी पैटर्न अनुकूलन को सक्षम या अक्षम करता है। सक्षम होने पर, ONNX Runtime तेज़ निष्पादन के लिए मेमोरी आवंटन पैटर्न को कैश करता है, लेकिन गतिशील इनपुट आकारों के लिए मेमोरी उपयोग बढ़ा सकता है। यदि इनपुट में काफी अंतर है या मेमोरी फुटप्रिंट कम करना चाहते हैं तो इसे अक्षम करें।

### executionMode {#executionMode}
```
public static ExecutionModeOnnx executionMode
```


सेशन के लिए निष्पादन मोड। डिफ़ॉल्ट रूप से, ऑपरेटरों को संभव होने पर समानांतर रूप से निष्पादित किया जाता है।

### graphOptimizationLevel {#graphOptimizationLevel}
```
public static GraphOptimizationLevelOnnx graphOptimizationLevel
```


सेशन के लिए ग्राफ़ अनुकूलन स्तर। डिफ़ॉल्ट रूप से, अधिकतम प्रदर्शन के लिए सभी उपलब्ध अनुकूलन सक्षम होते हैं।

### interOpNumThreads {#interOpNumThreads}
```
public static int interOpNumThreads
```


समांतर रूप से कई ऑपरेशनों को चलाने के लिए थ्रेड्स की संख्या। यदि क्रमिक निष्पादन सक्षम है, तो यह मान अनदेखा किया जाता है।

### intraOpNumThreads {#intraOpNumThreads}
```
public static int intraOpNumThreads
```


एकल ऑपरेशन के लिए थ्रेड्स की संख्या।