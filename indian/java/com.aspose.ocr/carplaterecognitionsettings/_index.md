---
title: "CarPlateRecognitionSettings"
second_title: "Aspose.OCR जावा के लिए API संदर्भ"
description: "कार नंबर पहचान के लिए सेटिंग्स में ऐसे तत्व शामिल हैं जो पहचान प्रक्रिया को अनुकूलित करने की अनुमति देते हैं।"
type: docs
weight: 12
url: /hi/java/com.aspose.ocr/carplaterecognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class CarPlateRecognitionSettings
```

कार नंबर पहचान के लिए सेटिंग्स में ऐसे तत्व शामिल हैं जो पहचान प्रक्रिया को अनुकूलित करने की अनुमति देते हैं।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [CarPlateRecognitionSettings()](#CarPlateRecognitionSettings) | डिफ़ॉल्ट कंस्ट्रक्टर: autoSkew को true सेट करें। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType) | अनुमत अक्षरों का सेट। |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | गहरे/काले पृष्ठभूमि पर सफ़ेद टेक्स्ट वाली छवियों का पता लगाएँ और उनके लिए स्वचालित रूप से एक विशेष OCR एल्गोरिद्म चुनें। |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | पहचान प्रतीकों के लिए ब्लैकलिस्ट सेट करता है। |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.Language) |  |
### CarPlateRecognitionSettings() {#CarPlateRecognitionSettings}
```
public CarPlateRecognitionSettings()
```


डिफ़ॉल्ट कंस्ट्रक्टर: autoSkew को true सेट करें।





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


अनुमत अक्षरों का सेट। पहचान परिणाम के लिए अनुमत अक्षरों के प्रकार को निर्धारित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) | enum @see [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) मान शामिल करता है। |

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

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr/language/) | OCR के लिए उपयोग की जाने वाली भाषा सेट करता है। डिफ़ॉल्ट रूप से मल्टी-लैंग्वेज (कोई नहीं)। |

