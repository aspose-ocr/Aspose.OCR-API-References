---
title: "लाइसेंस"
second_title: "Aspose.OCR जावा के लिए API संदर्भ"
description: "घटक को लाइसेंस करने के लिए मेथड प्रदान करता है"
type: docs
weight: 21
url: /hi/java/com.aspose.ocr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

घटक को लाइसेंस करने के लिए मेथड प्रदान करता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [License()](#License) | इस क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |

| [setLicense(File licenseFile)](#setLicense-java.io.File) | घटक को लाइसेंस करता है। |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream) | घटक को लाइसेंस करता है। |
| [setLicense(String licenseFilePath)](#setLicense-java.lang.String) | घटक को लाइसेंस करता है। |
| [isValid()](#isValid--) | लाइसेंस जांचें। |
### License() {#License}
```
public License()
```


इस क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


### setLicense(File licenseFile) {#setLicense-java.io.File}
```
public static void setLicense(File licenseFile)
```


घटक को लाइसेंस करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licenseFile | java.io.File | फ़ाइल पाथनेम का प्रतिनिधित्व |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream}
```
public static void setLicense(InputStream stream)
```


घटक को लाइसेंस करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | एक स्ट्रीम जिसमें लाइसेंस शामिल है। |

### setLicense(String licenseFilePath) {#setLicense-java.lang.String}
```
public static void setLicense(String licenseFilePath)
```


घटक को लाइसेंस करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licenseFilePath | java.lang.String | पूरा या छोटा फ़ाइल नाम हो सकता है। मूल्यांकन मोड में स्विच करने के लिए खाली स्ट्रिंग का उपयोग करें। |



### isValid() {#isValid--}
```
public static boolean isValid()
```


लाइसेंस जांचें।

**Returns:**
boolean - बूलियन मान कि लाइसेंस वैध है।
