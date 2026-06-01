---
title: "RecognitionSettings"
second_title: "Aspose.OCR जावा के लिए API संदर्भ"
description: "छवि पहचान के लिए सेटिंग्स"
type: docs
weight: 27
url: /hi/java/com.aspose.ocr/recognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionSettings
```

छवि पहचान के लिए सेटिंग्स। ऐसे तत्व शामिल हैं जो पहचान प्रक्रिया को अनुकूलित करने की अनुमति देते हैं।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [RecognitionSettings()](#RecognitionSettings) | डिफ़ॉल्ट कन्स्ट्रक्टर: recognitionAreas को null सेट करें, linesFiltration को false, autoSkew को false, recognizeSingleLine को false। |
| [RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)](#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean) | कन्स्ट्रक्टर सभी विकल्प सेट करने की अनुमति देता है। |
| [RecognitionSettings(boolean recognizeSingleLine)](#RecognitionSettings-boolean) | कन्स्ट्रक्टर recognizeSingleLine सेट करने की अनुमति देता है। |
| [RecognitionSettings(ReceiptRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings) |  |
| [RecognitionSettings(InvoiceRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings) |  |
| [RecognitionSettings(IDCardRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings) |  |
| [RecognitionSettings(PassportRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings) |  |
| [RecognitionSettings(CarPlateRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | अनुमत अक्षरों का सेट। |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | अनुमत अक्षरों का सेट। |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | गहरे/काले पृष्ठभूमि पर सफ़ेद टेक्स्ट वाली छवियों का पता लगाएँ और उनके लिए स्वचालित रूप से एक विशेष OCR एल्गोरिद्म चुनें। |
| [setDetectAreasMode(DetectAreasMode detectAreasMode)](#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode) | क्षेत्रों के पता लगाने के लिए उपयोग किए जाने वाले न्यूरल नेटवर्क का प्रकार निर्धारित करता है। |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | पहचान प्रतीकों के लिए ब्लैकलिस्ट सेट करता है। |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | टेक्स्ट रिकग्निशन के लिए भाषा पहचान के स्तर को निर्दिष्ट करता है। |
| [setLinesFiltration(boolean linesFiltration)](#setLinesFiltration-boolean) | टेबल्स (रेखाओं से घिरे क्षेत्रों) में टेक्स्ट पहचानने की अनुमति देता है। |
| [setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)](#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle) | प्रसंस्करण के लिए टेक्स्ट क्षेत्रों की सूची सेट करता है। |
| [setRecognizeSingleLine(boolean recognizeSingleLine)](#setRecognizeSingleLine-boolean) | एक-लाइन छवि पहचान सेट करता है। |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | प्रोसेसिंग के लिए थ्रेड्स की संख्या प्राप्त करता है या सेट करता है। |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | छोटे फ़ॉन्ट की पहचान के लिए विशेष रूप से अतिरिक्त एल्गोरिदम का उपयोग करने की अनुमति देता है। |
### RecognitionSettings() {#RecognitionSettings}
```
public RecognitionSettings()
```


डिफ़ॉल्ट कन्स्ट्रक्टर: recognitionAreas को null सेट करें, linesFiltration को false, autoSkew को false, recognizeSingleLine को false।

### RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine) {#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean}
```
public RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)
```


कन्स्ट्रक्टर सभी विकल्प सेट करने की अनुमति देता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | पहचान के लिए आयतें। |
| recognizeSingleLine | boolean | सही यदि छवि में केवल एक पंक्ति हो। |

### RecognitionSettings(boolean recognizeSingleLine) {#RecognitionSettings-boolean}
```
public RecognitionSettings(boolean recognizeSingleLine)
```


कन्स्ट्रक्टर आपको recognizeSingleLine सेट करने की अनुमति देता है। इस मामले में डिफ़ॉल्ट मान: detectAreas - false, autoSkew = false, recognitionAreas - null।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| recognizeSingleLine | boolean | सही यदि छवि में केवल एक पंक्ति हो। |

### RecognitionSettings(ReceiptRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings}
```
public RecognitionSettings(ReceiptRecognitionSettings recSettings)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| recSettings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) |  |

### RecognitionSettings(InvoiceRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings}
```
public RecognitionSettings(InvoiceRecognitionSettings recSettings)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| recSettings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) |  |

### RecognitionSettings(IDCardRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings}
```
public RecognitionSettings(IDCardRecognitionSettings recSettings)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| recSettings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) |  |

### RecognitionSettings(PassportRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings}
```
public RecognitionSettings(PassportRecognitionSettings recSettings)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| recSettings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) |  |

### RecognitionSettings(CarPlateRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings}
```
public RecognitionSettings(CarPlateRecognitionSettings recSettings)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| recSettings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) |  |




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
| allowedCharacters | java.lang.String | अक्षरों की स्ट्रिंग शामिल है। |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


गहरे/काले पृष्ठभूमि पर सफ़ेद टेक्स्ट वाली छवियों का पता लगाएँ और उनके लिए स्वचालित रूप से एक विशेष OCR एल्गोरिद्म चुनें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| automaticColorInversion | boolean | बूलियन मान शामिल है - automaticColorInversion सेट है। डिफ़ॉल्ट रूप से true। |

### setDetectAreasMode(DetectAreasMode detectAreasMode) {#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode}
```
public void setDetectAreasMode(DetectAreasMode detectAreasMode)
```


क्षेत्रों के पता लगाने के लिए उपयोग किए जाने वाले न्यूरल नेटवर्क का प्रकार निर्धारित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | enum मान शामिल है @see [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/)। |

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
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) |  |

### setLinesFiltration(boolean linesFiltration) {#setLinesFiltration-boolean}
```
public void setLinesFiltration(boolean linesFiltration)
```


टेबल्स (रेखाओं से घिरे क्षेत्रों) में टेक्स्ट पहचानने की अनुमति देता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| linesFiltration | boolean | false - प्रदर्शन बढ़ाने और तालिकाओं को न पहचानने तथा पंक्तियों को हटाने की अनुमति देता है; अन्यथा - true। डिफ़ॉल्ट रूप से निष्क्रिय (false)। |

### setRecognitionAreas(ArrayList<Rectangle> recognitionAreas) {#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle}
```
public void setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)
```


प्रसंस्करण के लिए टेक्स्ट क्षेत्रों की सूची सेट करता है। अधिक सटीक पहचान के लिए टेक्स्ट वाले क्षेत्रों को मैन्युअल रूप से निर्दिष्ट करने की अनुमति देता है। यदि कस्टम क्षेत्रों को सेट किया गया है [setDetectAreasMode(DetectAreasMode)](../../com.aspose.ocr/recognitionsettings/\#setDetectAreasMode-DetectAreasMode) (DetectAreasMode)\} NONE नहीं या [PreprocessingFilter.AutoSkew()](../../com.aspose.ocr/preprocessingfilter/\#AutoSkew) (boolean)\} प्रॉपर्टी को अनदेखा किया जाएगा। DetectAreas और AutoSkew को निष्क्रिय करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | पहचान के लिए आयतें। |

### setRecognizeSingleLine(boolean recognizeSingleLine) {#setRecognizeSingleLine-boolean}
```
public void setRecognizeSingleLine(boolean recognizeSingleLine)
```


एक-लाइन छवि पहचान सेट करता है। डिफ़ॉल्ट रूप से निष्क्रिय (false)। पंक्तियों में विभाजन से जुड़े सभी प्रसंस्करण चरणों को निष्क्रिय करता है। यदि आपकी छवि में केवल एक पंक्ति है तो इस पैरामीटर को true सेट करें। [setRecognitionAreas(ArrayList)](../../com.aspose.ocr/recognitionsettings/\#setRecognitionAreas-ArrayList) सेटिंग्स को निष्क्रिय करता है, इसलिए सभी क्षेत्र सेटिंग्स को अनदेखा किया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| recognizeSingleLine | boolean | एक-लाइन छवि के लिए true |

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
| upscaleSmallFont | boolean | बूलियन मान शामिल है - upscaleSmallFont सेट है। |

### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String