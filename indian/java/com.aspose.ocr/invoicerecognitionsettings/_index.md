---
title: "InvoiceRecognitionSettings"
second_title: "Aspose.OCR जावा के लिए API संदर्भ"
description: "इनवॉइस पहचान के लिए सेटिंग्स में ऐसे तत्व शामिल हैं जो पहचान प्रक्रिया को अनुकूलित करने की अनुमति देते हैं।"
type: docs
weight: 17
url: /hi/java/com.aspose.ocr/invoicerecognitionsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.ocr.ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/)
```
public class InvoiceRecognitionSettings extends ReceiptRecognitionSettings
```

इनवॉइस पहचान के लिए सेटिंग्स में ऐसे तत्व शामिल हैं जो पहचान प्रक्रिया को अनुकूलित करने की अनुमति देते हैं।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [InvoiceRecognitionSettings()](#InvoiceRecognitionSettings) | डिफ़ॉल्ट कंस्ट्रक्टर: autoSkew को true सेट करें। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | अनुमत अक्षरों का सेट। |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | अनुमत अक्षरों का सेट। |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | गहरे/काले पृष्ठभूमि पर सफ़ेद टेक्स्ट वाली छवियों का पता लगाएँ और उनके लिए स्वचालित रूप से एक विशेष OCR एल्गोरिद्म चुनें। |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | पहचान प्रतीकों के लिए ब्लैकलिस्ट सेट करता है। |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | टेक्स्ट रिकग्निशन के लिए भाषा पहचान के स्तर को निर्दिष्ट करता है। |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | प्रोसेसिंग के लिए थ्रेड्स की संख्या प्राप्त करता है या सेट करता है। |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | छोटे फ़ॉन्ट की पहचान के लिए विशेष रूप से अतिरिक्त एल्गोरिदम का उपयोग करने की अनुमति देता है। |
### InvoiceRecognitionSettings() {#InvoiceRecognitionSettings}
```
public InvoiceRecognitionSettings()
```


डिफ़ॉल्ट कंस्ट्रक्टर: autoSkew को true सेट करें।



### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


अनुमत अक्षरों का सेट। पहचान परिणाम के लिए अनुमत अक्षरों के प्रकार को निर्धारित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) | enum शामिल करता है @see [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) मान। |

### setAllowedCharacters(String allowedCharacters) {#setAllowedCharacters-java.lang.String}
```
public void setAllowedCharacters(String allowedCharacters)
```


अनुमत अक्षरों का सेट। पहचान परिणाम के लिए अनुमत अक्षरों की सरणी को निर्धारित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| allowedCharacters | java.lang.String | अक्षरों की सरणी शामिल करता है। |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


गहरे/काले पृष्ठभूमि पर सफ़ेद टेक्स्ट वाली छवियों का पता लगाएँ और उनके लिए स्वचालित रूप से एक विशेष OCR एल्गोरिद्म चुनें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| automaticColorInversion | boolean | बूलियन मान शामिल करता है - एक automaticColorInversion सेट किया गया है। |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


पहचान प्रतीकों के लिए ब्लैकलिस्ट सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| characters | java.lang.String | पहचान से बाहर किए गए अक्षर। |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.models.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr.models/language/) | OCR के लिए उपयोग की जाने वाली भाषा सेट करता है। डिफ़ॉल्ट रूप से मल्टी-लैंग्वेज (कोई नहीं)। |

### setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel) {#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel}
```
public void setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)
```


टेक्स्ट रिकग्निशन के लिए भाषा पहचान के स्तर को निर्दिष्ट करता है। यह केवल तब काम करता है जब चयनित भाषा Language.MULTILANGUAGE, Language.AUTO, या Language.UNIVERSAL हो। यह प्रक्रिया समय-साध्य है और समग्र पहचान को काफी धीमा कर देती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) | स्तर सेट करने के लिए enum मान (Paragraph, Word, Page)। |

### setThreadsCount(int threadsCount) {#setThreadsCount-int}
```
public void setThreadsCount(int threadsCount)
```


प्रोसेसिंग के लिए थ्रेड्स की संख्या प्राप्त करता है या सेट करता है। डिफ़ॉल्ट रूप से, 0 का अर्थ है कि छवि को आपके प्रोसेसर की संख्या के बराबर थ्रेड्स के साथ प्रोसेस किया जाएगा। ThreadsCount = 1 का अर्थ है कि छवि मुख्य थ्रेड में प्रोसेस होगी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| threadsCount | int | छवि के फ्रैगमेंट्स की समानांतर पहचान के लिए बनाए जाने वाले थ्रेड्स की संख्या। |

### setUpscaleSmallFont(boolean upscaleSmallFont) {#setUpscaleSmallFont-boolean}
```
public void setUpscaleSmallFont(boolean upscaleSmallFont)
```


छोटे फ़ॉन्ट की पहचान के लिए विशेष रूप से अतिरिक्त एल्गोरिदम का उपयोग करने की अनुमति देता है। छोटे आकार के अक्षरों वाली छवियों के लिए उपयोगी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| upscaleSmallFont | boolean | बूलियन मान शामिल करता है - एक upscaleSmallFont सेट किया गया है। |
