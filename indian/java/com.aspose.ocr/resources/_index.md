---
title: "Resources"
second_title: "Aspose.OCR जावा के लिए API संदर्भ"
description: "Aspose.OCR पहचान क्षमताओं को बढ़ाने वाले डाउनलोडेबल संसाधनों का प्रबंधन करें"
type: docs
weight: 32
url: /hi/java/com.aspose.ocr/resources/
---

**Inheritance:**
java.lang.Object
```
public class Resources
```

ऐसे डाउनलोड करने योग्य संसाधनों का प्रबंधन करें जो Aspose.OCR पहचान क्षमताओं को बढ़ाते हैं।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Resources()](#Resources) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [AllowAutomaticDownloads(Boolean allow)](#AllowAutomaticDownloads-java.lang.Boolean) | ऑनलाइन रिपॉज़िटरी से आवश्यक संसाधनों की स्वचालित डाउनलोडिंग को अनुमति दें (true) या ब्लॉक करें (false)। |
| [FetchAll()](#FetchAll) | ऑनलाइन रिपॉज़िटरी से सभी संगत संसाधनों को डाउनलोड करें। |
| [FetchResource(String name)](#FetchResource-java.lang.String) | ऑनलाइन रिपॉजिटरी से नाम पैरामीटर में निर्दिष्ट संसाधन डाउनलोड करें। |
| [FetchResources(String[] names)](#FetchResources-java.lang.String) | ऑनलाइन रिपॉजिटरी से नामों पैरामीटर में निर्दिष्ट संसाधनों को डाउनलोड करें। |
| [GetLocalPath()](#GetLocalPath) | उस डायरेक्टरी का पूर्ण पथ लौटाएँ जहाँ संसाधन डाउनलोड किए जाएंगे। |
| [GetRepository()](#GetRepository) | ऑनलाइन रिपॉजिटरी का URL लौटाएँ जिससे Aspose.OCR संसाधन डाउनलोड होते हैं। |
| [ListLocal()](#ListLocal) | स्थानीय डायरेक्टरी में संग्रहीत सभी Aspose.OCR संसाधनों की सूची बनाएँ। |
| [ListRemote()](#ListRemote) | ऑनलाइन रिपॉजिटरी से सभी संगत संसाधनों की सूची बनाएँ। |
| [ReleaseMemory()](#ReleaseMemory) | मेमोरी मुक्त करने के लिए OCR मॉड्यूल अनलोड करें। |
| [RemoveLocal(String name)](#RemoveLocal-java.lang.String) | स्थानीय रूप से संग्रहीत Aspose.OCR संसाधन को हटाता है। |
| [SetLocalPath(String path)](#SetLocalPath-java.lang.String) | उस डायरेक्टरी का पूर्ण या सापेक्ष पथ निर्दिष्ट करें जहाँ संसाधन डाउनलोड किए जाएंगे। |
| [SetLocalPath(String path, Boolean create)](#SetLocalPath-java.lang.String-java.lang.Boolean) | उस डायरेक्टरी का पूर्ण या सापेक्ष पथ निर्दिष्ट करें जहाँ संसाधन डाउनलोड किए जाएंगे। |
| [SetRepository(String url)](#SetRepository-java.lang.String) | ऑनलाइन रिपॉजिटरी का URL निर्दिष्ट करें जिससे Aspose.OCR संसाधन डाउनलोड किए जाएंगे। |

### Resources() {#Resources}
```
public Resources()
```


### AllowAutomaticDownloads(Boolean allow) {#AllowAutomaticDownloads-java.lang.Boolean}
```
public static void AllowAutomaticDownloads(Boolean allow)
```


ऑनलाइन रिपॉजिटरी से आवश्यक संसाधनों के स्वचालित डाउनलोड को अनुमति (true) या रोक (false) दें। डिफ़ॉल्ट रूप से, जब कोई मेथड जो उस पर निर्भर करता है, कॉल किया जाता है, तो संसाधन स्वचालित रूप से डाउनलोड हो जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| अनुमति | java.lang.Boolean | आवश्यक संसाधनों के स्वचालित डाउनलोड को अनुमति या रोकने के लिए बूलियन मान। |

### FetchAll() {#FetchAll}
```
public static void FetchAll()
```


ऑनलाइन रिपॉजिटरी से सभी संगत संसाधनों को डाउनलोड करें। मौजूदा संसाधन फ़ाइलें अधिलेखित हो जाएँगी।

### FetchResource(String name) {#FetchResource-java.lang.String}
```
public static void FetchResource(String name)
```


ऑनलाइन रिपॉजिटरी से नाम पैरामीटर में निर्दिष्ट संसाधन डाउनलोड करें। यदि संसाधन पहले से डाउनलोड किया गया है, तो वह अधिलेखित हो जाएगा। आप .OCR एक्सटेंशन को छोड़कर केवल फ़ाइल नाम का उपयोग कर सकते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | संसाधन नाम वाला स्ट्रिंग। ListRemote मेथड देखें। |

### FetchResources(String[] names) {#FetchResources-java.lang.String}
```
public static void FetchResources(String[] names)
```


ऑनलाइन रिपॉजिटरी से नामों पैरामीटर में निर्दिष्ट संसाधनों को डाउनलोड करें। यदि एक या अधिक संसाधन पहले से डाउनलोड किए गए हैं, तो वे अधिलेखित हो जाएंगे। आप .OCR एक्सटेंशन को छोड़कर केवल फ़ाइल नामों का उपयोग कर सकते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String[] | संसाधन नामों वाला एरे। ListRemote मेथड देखें। |

### GetLocalPath() {#GetLocalPath}
```
public static String GetLocalPath()
```


उस डायरेक्टरी का पूर्ण पथ लौटाएँ जहाँ संसाधन डाउनलोड किए जाएंगे।

**Returns:**
java.lang.String - संसाधन डायरेक्टरी के पथ वाला स्ट्रिंग।
### GetRepository() {#GetRepository}
```
public static String GetRepository()
```


ऑनलाइन रिपॉजिटरी का URL लौटाएँ जिससे Aspose.OCR संसाधन डाउनलोड होते हैं।

**Returns:**
java.lang.String - ऑनलाइन रिपॉजिटरी का URL।
### ListLocal() {#ListLocal}
```
public static List<String> ListLocal()
```


स्थानीय डायरेक्टरी में संग्रहीत सभी Aspose.OCR संसाधनों की सूची बनाएँ।

**Returns:**
java.util.List<java.lang.String> - स्थानीय डायरेक्टरी में संग्रहीत सभी Aspose.OCR संसाधनों की सूची बनाएँ।
### ListRemote() {#ListRemote}
```
public static List<String> ListRemote()
```


ऑनलाइन रिपॉजिटरी से सभी संगत संसाधनों की सूची बनाएँ।

**Returns:**
java.util.List<java.lang.String> - संसाधनों के नामों की सूची।
### ReleaseMemory() {#ReleaseMemory}
```
public static void ReleaseMemory()
```


OCR मॉड्यूल को अनलोड करें ताकि मेमोरी मुक्त हो सके। डाउनलोड किए गए मॉड्यूल फ़ाइलें अपरिवर्तित रहेंगी।

### RemoveLocal(String name) {#RemoveLocal-java.lang.String}
```
public static void RemoveLocal(String name)
```


स्थानीय रूप से संग्रहीत Aspose.OCR संसाधन को हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

### SetLocalPath(String path) {#SetLocalPath-java.lang.String}
```
public static void SetLocalPath(String path)
```


संसाधनों के डाउनलोड होने वाले डायरेक्टरी का पूर्ण या सापेक्ष पथ निर्दिष्ट करें। यदि डायरेक्टरी मौजूद नहीं है, तो इसे स्वचालित रूप से बनाया जाएगा। डिफ़ॉल्ट रूप से, संसाधन एप्लिकेशन की कार्यशील डायरेक्टरी में aspose\_data डायरेक्टरी में डाउनलोड किए जाते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पथ | java.lang.String | डायरेक्टरी का पूर्ण या सापेक्ष पथ। |

### SetLocalPath(String path, Boolean create) {#SetLocalPath-java.lang.String-java.lang.Boolean}
```
public static void SetLocalPath(String path, Boolean create)
```


संसाधनों के डाउनलोड होने वाले डायरेक्टरी का पूर्ण या सापेक्ष पथ निर्दिष्ट करें। डायरेक्टरी को स्वचालित रूप से बनाने से रोकने के लिए create पैरामीटर को false पास करें। यदि प्रदान की गई डायरेक्टरी मौजूद नहीं है और निर्माण की अनुमति नहीं है, तो संसाधन एप्लिकेशन की कार्यशील डायरेक्टरी में aspose\_data डायरेक्टरी में लोड किए जाएंगे।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पथ | java.lang.String | डायरेक्टरी का पूर्ण या सापेक्ष पथ। |
| create | java.lang.Boolean | डायरेक्टरी को स्वचालित रूप से बनाने से रोकने का पैरामीटर। |

### SetRepository(String url) {#SetRepository-java.lang.String}
```
public static void SetRepository(String url)
```


ऑनलाइन रिपॉज़िटरी का URL निर्दिष्ट करें जिससे Aspose.OCR संसाधन डाउनलोड किए जाएंगे। डिफ़ॉल्ट रूप से, संसाधन https://github.com/aspose-ocr/resources/ से डाउनलोड होते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | java.lang.String | ऑनलाइन रिपॉज़िटरी का URL। |


