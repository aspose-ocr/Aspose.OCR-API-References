---
title: "RecognitionResult"
second_title: "Aspose.OCR जावा के लिए API संदर्भ"
description: "छवि पहचान के परिणाम"
type: docs
weight: 26
url: /hi/java/com.aspose.ocr/recognitionresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult
```

छवि पहचान के परिणाम। इसमें पहचान जानकारी वाले तत्व और परिणाम निर्यात के लिए विधियाँ शामिल हैं।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [RecognitionResult()](#RecognitionResult) | एक नया उदाहरण प्रारंभ करता है |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [language](#language) | छवि में पहचाने गए पाठ की भाषा। |
| [recognitionCharactersList](#recognitionCharactersList) | पहचान एल्गोरिद्म द्वारा पाए गए अक्षरों का सेट, संभाव्यता के घटते क्रम में व्यवस्थित। |
| [recognitionLinesResult](#recognitionLinesResult) | पंक्तियों (आयतों) की सूची के साथ पहचान परिणामों की सूची प्राप्त करता है। |
| [recognitionRegionsResult](#recognitionRegionsResult) | क्षेत्रों (आयतों) की सूची के साथ पहचान परिणामों की सूची प्राप्त करता है। |
| [recognitionText](#recognitionText) | सभी पृष्ठों या एक क्षेत्र का पहचान परिणाम। |
| [warnings](#warnings) | जनरेशन के दौरान उत्पन्न गैर-आलोचनात्मक त्रुटियों का वर्णन करने वाले चेतावनी संदेशों की सूची प्राप्त करता है या सेट करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [GetJson()](#GetJson) | पहचान परिणामों के साथ JSON स्ट्रिंग बनाएं। |
| [GetKeywords()](#GetKeywords) | पासपोर्ट से कुंजीशब्द प्राप्त करें (परीक्षण मोड। |
| [GetXml()](#GetXml) | पहचान परिणामों के साथ JSON स्ट्रिंग बनाएं। |
| [SetKeyword(String key, RecognitionResult.LinesResult result)](#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult) |  |
| [getSpellCheckCorrectedText()](#getSpellCheckCorrectedText) | पाठ को सुधारता है (गलत लिखे शब्दों को बदलता है)। |
| [getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)](#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | पाठ को सुधारता है (गलत लिखे शब्दों को बदलता है)। |
| [getSpellCheckErrorList()](#getSpellCheckErrorList) | दिए गए इनपुट टेक्स्ट के लिए सुझाए गए वर्तनी के साथ गलत शब्दों को खोजें। |
| [getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)](#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | दिए गए इनपुट टेक्स्ट के लिए सुझाए गए वर्तनी के साथ गलत शब्दों को खोजें। |
| [save(String fullFileName)](#save-java.lang.String) | दस्तावेज़ को साधारण टेक्स्ट में सहेजता है |
| [save(String fullFileName, Format format)](#save-java.lang.String-com.aspose.ocr.models.Format) | दस्तावेज़ को साधारण टेक्स्ट या अन्य दस्तावेज़ फ़ॉर्मेट में सहेजता है। |
| [save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode) | दस्तावेज़ को साधारण टेक्स्ट या अन्य दस्तावेज़ फ़ॉर्मेट में सहेजता है। |
| [saveSpellCheckCorrectedText(String fullFileName, Format format)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format) | दस्तावेज़ में अंग्रेज़ी शब्दकोश के साथ सुधारा गया टेक्स्ट को साधारण टेक्स्ट या माइक्रोसॉफ्ट वर्ड टेक्स्ट डॉक्यूमेंट फ़ॉर्मेट में सहेजता है। |
| [saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | दस्तावेज़ में सुधारा गया टेक्स्ट को साधारण टेक्स्ट या अन्य फ़ॉर्मेट में सहेजता है। |
| [toString()](#toString) |  |
| [useUserDictionary(String dictionaryPath)](#useUserDictionary-java.lang.String) | वर्तनी जाँच सुधार के लिए अपना शब्दकोश उपयोग करने की अनुमति देता है। |
### RecognitionResult() {#RecognitionResult}
```
public RecognitionResult()
```


एक नया उदाहरण प्रारंभ करता है

### language {#language}
```
public Language language
```


छवि में पहचाने गए टेक्स्ट की भाषा। यदि  Language.AUTO ,  Language.MULTILANGUAGE , या  Language.UNIVERSAL  चुना गया हो तो यह मान स्वचालित रूप से निर्धारित होता है।

### recognitionCharactersList {#recognitionCharactersList}
```
public ArrayList<char[]> recognitionCharactersList
```


पहचान एल्गोरिद्म द्वारा पाए गए अक्षरों का सेट, संभाव्यता के घटते क्रम में व्यवस्थित।

### recognitionLinesResult {#recognitionLinesResult}
```
public ArrayList<RecognitionResult.LinesResult> recognitionLinesResult
```


पंक्तियों (आयतों) की सूची के साथ पहचान परिणामों की सूची प्राप्त करता है।

### recognitionRegionsResult {#recognitionRegionsResult}
```
public ArrayList<RecognitionResult.RegionResult> recognitionRegionsResult
```


क्षेत्रों (आयतों) की सूची के साथ पहचान परिणामों की सूची प्राप्त करता है।

### recognitionText {#recognitionText}
```
public String recognitionText
```


सभी पृष्ठों या एक क्षेत्र का पहचान परिणाम।

### warnings {#warnings}
```
public ArrayList<String> warnings
```


जनरेशन के दौरान उत्पन्न गैर-आलोचनात्मक त्रुटियों का वर्णन करने वाले चेतावनी संदेशों की सूची प्राप्त करता है या सेट करता है।

### GetJson() {#GetJson}
```
public String GetJson()
```


पहचान परिणामों के साथ JSON स्ट्रिंग बनाएं।

**Returns:**
java.lang.String - पहचान परिणाम JSON स्ट्रिंग के रूप में।
### GetKeywords() {#GetKeywords}
```
public HashMap<String,RecognitionResult.LinesResult> GetKeywords()
```


पासपोर्ट से कीवर्ड प्राप्त करें (टेस्ट मोड। केवल USA और MADAGASCAR पासपोर्ट के लिए काम करता है)।

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.ocr.RecognitionResult.LinesResult> - शब्दकोश जिसमें कीवर्ड कुंजी के रूप में और LinesResult मान के रूप में होता है।
### GetXml() {#GetXml}
```
public String GetXml()
```


पहचान परिणामों के साथ JSON स्ट्रिंग बनाएं।

**Returns:**
java.lang.String - पहचान परिणाम XML स्ट्रिंग के रूप में।
### SetKeyword(String key, RecognitionResult.LinesResult result) {#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult}
```
public void SetKeyword(String key, RecognitionResult.LinesResult result)
```



### getSpellCheckCorrectedText() {#getSpellCheckCorrectedText}
```
public String getSpellCheckCorrectedText()
```


पाठ को सुधारता है (गलत लिखे शब्दों को बदलता है)।

**Returns:**
java.lang.String - सुधारा गया पहचान परिणाम स्ट्रिंग। डिफ़ॉल्ट अंग्रेज़ी शब्दकोश।
### getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language) {#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)
```


पाठ को सुधारता है (गलत लिखे शब्दों को बदलता है)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | उपयोग करने के लिए शब्दकोश। |

**Returns:**
java.lang.String - सुधारा गया पहचान परिणाम स्ट्रिंग।
### getSpellCheckErrorList() {#getSpellCheckErrorList}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList()
```


दिए गए इनपुट टेक्स्ट के लिए सुझाए गए वर्तनी के साथ गलत शब्दों को खोजें। डिफ़ॉल्ट अंग्रेज़ी शब्दकोश।

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - SpellCheckError ऑब्जेक्ट की ArrayList जो प्रत्येक गलत शब्द के लिए सुझाए गए सही वर्तनी की सूची और संपादन दूरी के साथ गलत शब्दों को दर्शाती है।
### getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language) {#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)
```


दिए गए इनपुट टेक्स्ट के लिए सुझाए गए वर्तनी के साथ गलत शब्दों को खोजें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | उपयोग करने के लिए शब्दकोश। |

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - SpellCheckError ऑब्जेक्ट की ArrayList जो प्रत्येक गलत शब्द के लिए सुझाए गए सही वर्तनी की सूची और संपादन दूरी के साथ गलत शब्दों को दर्शाती है।




### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


दस्तावेज़ को साधारण टेक्स्ट में सहेजता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullFileName | java.lang.String | पहचान परिणाम सहेजने के लिए पथ के साथ फ़ाइलनाम |

### save(String fullFileName, Format format) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format format)
```


दस्तावेज़ को साधारण टेक्स्ट या अन्य दस्तावेज़ फ़ॉर्मेट में सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullFileName | java.lang.String | पहचान परिणाम सहेजने के लिए पथ के साथ फ़ाइलनाम। |
| format | [Format](../../com.aspose.ocr.models/format/) | फ़ॉर्मेट का दस्तावेज़ फ़ॉर्मेट enum प्रकार। |

### save(String fullFileName, Format format, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)
```


दस्तावेज़ को साधारण टेक्स्ट या अन्य दस्तावेज़ फ़ॉर्मेट में सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullFileName | java.lang.String | पहचान परिणाम सहेजने के लिए पथ के साथ फ़ाइलनाम। |
| format | [Format](../../com.aspose.ocr.models/format/) | फ़ॉर्मेट का दस्तावेज़ फ़ॉर्मेट enum प्रकार। |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | पृष्ठभूमि छवियों की गुणवत्ता कम करके PDF फ़ाइल का आकार घटाएँ। डिफ़ॉल्ट रूप में, मूल छवि गुणवत्ता बरकरार रहती है। |

### saveSpellCheckCorrectedText(String fullFileName, Format format) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format)
```


दस्तावेज़ में अंग्रेज़ी शब्दकोश के साथ सुधारा गया टेक्स्ट को साधारण टेक्स्ट या माइक्रोसॉफ्ट वर्ड टेक्स्ट डॉक्यूमेंट फ़ॉर्मेट में सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullFileName | java.lang.String | पहचान परिणाम सहेजने के लिए पथ के साथ फ़ाइलनाम। |
| format | [Format](../../com.aspose.ocr.models/format/) | फ़ॉर्मेट का दस्तावेज़ फ़ॉर्मेट enum प्रकार। |

### saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)
```


दस्तावेज़ में सुधारा गया टेक्स्ट को साधारण टेक्स्ट या अन्य फ़ॉर्मेट में सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullFileName | java.lang.String | पहचान परिणाम सहेजने के लिए पथ के साथ फ़ाइलनाम। |
| format | [Format](../../com.aspose.ocr.models/format/) | फ़ॉर्मेट का दस्तावेज़ फ़ॉर्मेट enum प्रकार। |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | वर्तनी जाँच के लिए शब्दकोश। |
### useUserDictionary(String dictionaryPath) {#useUserDictionary-java.lang.String}
```
public void useUserDictionary(String dictionaryPath)
```


वर्तनी जाँच सुधार के लिए अपना शब्दकोश उपयोग करने की अनुमति देता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dictionaryPath | java.lang.String | उपयोगकर्ता शब्दकोश (फ़्रीक्वेंसी शब्दकोश) का पूर्ण पाथ। शब्दकोश फ़ाइल फ़ॉर्मेट: UTF-8 एन्कोडिंग में साधारण टेक्स्ट फ़ाइल। शब्द और शब्द फ़्रीक्वेंसी कोमा द्वारा अलग किए जाते हैं, शब्द पहली कॉलम में और फ़्रीक्वेंसी दूसरी कॉलम में अपेक्षित है। प्रत्येक शब्द‑फ़्रीक्वेंसी जोड़े को अलग पंक्ति में रखा जाता है। एक पंक्ति को वर्णों की श्रृंखला के बाद लाइन फ़ीड ("\n"), कैरिज रिटर्न ("\r"), या कैरिज रिटर्न के तुरंत बाद लाइन फ़ीड ("\r\n") द्वारा परिभाषित किया जाता है। प्रत्येक शब्द को लोअर केस में होना चाहिए। |
