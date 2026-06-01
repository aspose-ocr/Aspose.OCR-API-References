---
title: "AsposeOCR"
second_title: "Aspose.OCR जावा के लिए API संदर्भ"
description: "छवियों से पाठ पहचानने के लिए मुख्य क्लास"
type: docs
weight: 10
url: /hi/java/com.aspose.ocr/asposeocr/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public class AsposeOCR implements AutoCloseable
```

छवियों से टेक्स्ट पहचानने के लिए मुख्य क्लास।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [AsposeOCR()](#AsposeOCR) | सार्वजनिक कंस्ट्रक्टर। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [DebugMode](#DebugMode) | डिबग मोड को सक्षम करता है। |
| [DebugModeSaveDirectory](#DebugModeSaveDirectory) | डिबग परिणाम जहाँ सहेजे जाएंगे वह डायरेक्टरी। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [CalculateSkew(OcrInput input)](#CalculateSkew-com.aspose.ocr.OcrInput) | छवियों के विकृति कोणों की गणना करता है। |
| [CompareImageTexts(String fullPath1, String fullPath2)](#CompareImageTexts-java.lang.String-java.lang.String) | जाँचें कि दो छवियों में समान पाठ है या नहीं। |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | जाँचें कि दो छवियों में समान पाठ है या नहीं। |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | जाँचें कि दो छवियों में समान पाठ है या नहीं। |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | पाठ को सुधारता है (गलत लिखे शब्दों को बदलता है)। |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String) | पाठ को सुधारता है (गलत लिखे शब्दों को बदलता है)। |
| [DetectDefects(OcrInput input, DefectType defectType)](#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType) | छवि के उन समस्याग्रस्त क्षेत्रों को स्वचालित रूप से खोजता है जो OCR की सटीकता को महत्वपूर्ण रूप से प्रभावित कर सकते हैं। |
| [DetectDocumentLayout(OcrInput input)](#DetectDocumentLayout-com.aspose.ocr.OcrInput) | छवि का विश्लेषण करता है और उसके भीतर विभिन्न प्रकार के कंटेंट क्षेत्रों की पहचान करता है। |
| [DetectLanguages(OcrInput input)](#DetectLanguages-com.aspose.ocr.OcrInput) | छवि पर पाठ का विश्लेषण करता है ताकि यह निर्धारित किया जा सके कि वह किस भाषा में लिखा गया है। |
| [DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)](#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean) | छवियों में पाठ क्षेत्रों का पता लगाता है। |
| [DetectTables(OcrInput images)](#DetectTables-com.aspose.ocr.OcrInput) | छवियों में तालिका क्षेत्रों का पता लगाता है। |
| [ImageHasText(String fullPath, String text)](#ImageHasText-java.lang.String-java.lang.String) | केस-इन्सेंसिटिव खोज के साथ जाँचें कि छवि में प्रदान किया गया पाठ अंश मौजूद है या नहीं। |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | केस-इन्सेंसिटिव खोज के साथ जाँचें कि छवि में प्रदान किया गया पाठ अंश मौजूद है या नहीं। |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | जाँचें कि छवि में प्रदान किया गया पाठ अंश मौजूद है या नहीं। |
| [ImageHasText(String fullPath, Pattern regex)](#ImageHasText-java.lang.String-java.util.regex.Pattern) | जाँचें कि छवि का पाठ प्रदान किए गए रेगुलर एक्सप्रेशन से मेल खाता है या नहीं। |
| [ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings) | जाँचें कि छवि का पाठ प्रदान किए गए रेगुलर एक्सप्रेशन से मेल खाता है या नहीं। |
| [ImageTextDiff(String fullPath1, String fullPath2)](#ImageTextDiff-java.lang.String-java.lang.String) | दोनों छवियों के पाठों की तुलना करें और एक संख्या लौटाएँ जो उनके समानता को दर्शाती है (0 से 1)। |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | दोनों छवियों के पाठों की तुलना करें और एक संख्या लौटाएँ जो उनके समानता को दर्शाती है (0 से 1)। |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | दोनों छवियों के पाठों की तुलना करें और एक संख्या लौटाएँ जो उनके समानता को दर्शाती है (0 से 1)। |
| [Recognize(OcrInput input)](#Recognize-com.aspose.ocr.OcrInput) | छवि को पहचानता है जिसमें आप निर्दिष्ट कर सकते हैं कि यह GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 को सपोर्ट करता है। |
| [Recognize(OcrInput input, RecognitionSettings settings)](#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings) | छवि को पहचानता है जिसमें आप निर्दिष्ट कर सकते हैं कि यह GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 को सपोर्ट करता है। |
| [RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)](#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings) | कार प्लेट को पहचानता है जिसमें आप निर्दिष्ट कर सकते हैं कि यह GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 को सपोर्ट करता है। |
| [RecognizeCharacters(OcrInput input)](#RecognizeCharacters-com.aspose.ocr.OcrInput) | छवियों में प्रतीकों का पता लगाता है। |
| [RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)](#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language) | छवियों में प्रतीकों का पता लगाता है। |
| [RecognizeFast(OcrInput input)](#RecognizeFast-com.aspose.ocr.OcrInput) | अच्छी गुणवत्ता वाली छवि पर पाठ को पहचानता है। |
| [RecognizeFormula(OcrInput input, boolean detectAreas)](#RecognizeFormula-com.aspose.ocr.OcrInput-boolean) | प्रदान किए गए इनपुट छवियों से गणितीय सूत्रों को पहचानता है। |
| [RecognizeHandwrittenText(OcrInput input)](#RecognizeHandwrittenText-com.aspose.ocr.OcrInput) | छवियों में हस्तलिखित पाठ को पहचानता है। |
| [RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)](#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings) | आईडी कार्ड को पहचानता है जिसमें आप निर्दिष्ट कर सकते हैं कि यह GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 को सपोर्ट करता है। |
| [RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)](#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings) | इनवॉइस को पहचानता है जिसमें आप निर्दिष्ट कर सकते हैं कि यह GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 को सपोर्ट करता है। |
| [RecognizePassport(OcrInput input, PassportRecognitionSettings settings)](#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings) | पासपोर्ट को पहचानता है और निर्दिष्ट करने की क्षमता रखता है। |
| [RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)](#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings) | रसीदों को पहचानता है और निर्दिष्ट करने की क्षमता रखता है। GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है। |
| [RecognizeTables(OcrInput input, Language language)](#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language) | टेबल और संरचना का पता लगाता है, टेक्स्ट सेल्स को पहचानता है। |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | RecognitionResult ऑब्जेक्ट्स की सूची से मल्टीपेज दस्तावेज़ प्राप्त करने की अनुमति देता है। |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | RecognitionResult ऑब्जेक्ट्स की सूची से मल्टीपेज दस्तावेज़ प्राप्त करने की अनुमति देता है। |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | RecognitionResult ऑब्जेक्ट्स की सूची से मल्टीपेज दस्तावेज़ प्राप्त करने की अनुमति देता है। |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | RecognitionResult ऑब्जेक्ट्स की सूची से मल्टीपेज दस्तावेज़ प्राप्त करने की अनुमति देता है। |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage) | स्पेल‑चेक सुधार के साथ RecognitionResult ऑब्जेक्ट्स की सूची से मल्टीपेज दस्तावेज़ प्राप्त करने की अनुमति देता है। |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | RecognitionResult ऑब्जेक्ट्स की सूची से मल्टीपेज दस्तावेज़ प्राप्त करने की अनुमति देता है। |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | RecognitionResult ऑब्जेक्ट्स की सूची से मल्टीपेज दस्तावेज़ प्राप्त करने की अनुमति देता है। |
| [close()](#close) |  |

### AsposeOCR() {#AsposeOCR}
```
public AsposeOCR()
```


सार्वजनिक कंस्ट्रक्टर।

### DebugMode {#DebugMode}
```
public static boolean DebugMode
```


डिबग मोड को सक्षम करता है। सक्षम होने पर, सिस्टम प्री‑प्रोसेस्ड इमेजेज़ और टेक्स्ट‑लाइन आयतों के साथ ड्रॉ की गई इमेजेज़ जैसे मध्यवर्ती इमेज प्रोसेसिंग परिणाम सहेजता है।

### DebugModeSaveDirectory {#DebugModeSaveDirectory}
```
public static String DebugModeSaveDirectory
```


डिबग परिणाम जहाँ सहेजे जाएंगे वह डायरेक्टरी। यदि सेट नहीं किया गया, तो डिफ़ॉल्ट रूप से वर्तमान कार्यशील डायरेक्टरी उपयोग की जाएगी।

### CalculateSkew(OcrInput input) {#CalculateSkew-com.aspose.ocr.OcrInput}
```
public ArrayList<SkewOutput> CalculateSkew(OcrInput input)
```


इमेज की स्क्यू कोणों की गणना करता है। GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | स्रोतों के साथ कंटेनर.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.SkewOutput> - डिग्री में स्क्यू कोणों की ArrayList [SkewOutput](../../com.aspose.ocr.models/skewoutput/)
### CompareImageTexts(String fullPath1, String fullPath2) {#CompareImageTexts-java.lang.String-java.lang.String}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2)
```


जाँचें कि दो छवियों में समान पाठ है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullPath1 | java.lang.String | पहली इमेज का पाथ। |
| fullPath2 | java.lang.String | दूसरी इमेज का पाथ। |

**Returns:**
boolean - यदि इमेजेज़ में समान टेक्स्ट (90% समानता) हो तो True।
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)
```


जाँचें कि दो छवियों में समान पाठ है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullPath1 | java.lang.String | पहली इमेज का पाथ। |
| fullPath2 | java.lang.String | दूसरी इमेज का पाथ। |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | पहचान सेटिंग्स। |

**Returns:**
boolean - यदि इमेजेज़ में समान टेक्स्ट (90% समानता) हो तो True।
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


जाँचें कि दो छवियों में समान पाठ है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullPath1 | java.lang.String | पहली इमेज का पाथ। |
| fullPath2 | java.lang.String | दूसरी इमेज का पाथ। |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | पहचान सेटिंग्स। |
| ignoreCase | boolean | True - इसका अर्थ है केस‑इन्सेंसिटिव खोज। |

**Returns:**
boolean - यदि इमेजेज़ में समान टेक्स्ट (90% समानता) हो तो True।
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)
```


पाठ को सुधारता है (गलत लिखे शब्दों को बदलता है)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सुधार के लिए टेक्स्ट। |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | उपयोग करने के लिए शब्दकोश [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |

**Returns:**
java.lang.String - बदले गए शब्दों के साथ टेक्स्ट।
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)
```


पाठ को सुधारता है (गलत लिखे शब्दों को बदलता है)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सुधार के लिए टेक्स्ट। |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | उपयोग करने के लिए शब्दकोश [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |
| dictionaryPath | java.lang.String | उपयोगकर्ता शब्दकोश (फ़्रीक्वेंसी शब्दकोश) का पूर्ण पाथ। शब्दकोश फ़ाइल फ़ॉर्मेट: UTF-8 एन्कोडिंग में साधारण टेक्स्ट फ़ाइल। शब्द और शब्द फ़्रीक्वेंसी कोमा द्वारा अलग किए जाते हैं, शब्द पहली कॉलम में और फ़्रीक्वेंसी दूसरी कॉलम में अपेक्षित है। प्रत्येक शब्द‑फ़्रीक्वेंसी जोड़े को अलग पंक्ति में रखा जाता है। एक पंक्ति को वर्णों की श्रृंखला के बाद लाइन फ़ीड ("\n"), कैरिज रिटर्न ("\r"), या कैरिज रिटर्न के तुरंत बाद लाइन फ़ीड ("\r\n") द्वारा परिभाषित किया जाता है। प्रत्येक शब्द को लोअर केस में होना चाहिए। |

**Returns:**
java.lang.String - बदले गए शब्दों के साथ टेक्स्ट।
### DetectDefects(OcrInput input, DefectType defectType) {#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType}
```
public ArrayList<DefectOutput> DetectDefects(OcrInput input, DefectType defectType)
```


इमेज के उन समस्याग्रस्त क्षेत्रों को स्वचालित रूप से खोजता है जो OCR की सटीकता को काफी प्रभावित कर सकते हैं। GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | स्रोतों के साथ कंटेनर.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| defectType | [DefectType](../../com.aspose.ocr.models/defecttype/) | पहचाने जाने वाले दोषों के प्रकार [DefectType](../../com.aspose.ocr.models/defecttype/). |

**Returns:**
java.util.ArrayList<com.aspose.ocr.DefectOutput> - [DefectOutput](../../com.aspose.ocr/defectoutput/) की ArrayList जिसमें पता लगाए गए पाठ क्षेत्रों या पंक्तियों शामिल हैं।
### DetectDocumentLayout(OcrInput input) {#DetectDocumentLayout-com.aspose.ocr.OcrInput}
```
public ArrayList<LayoutOutput> DetectDocumentLayout(OcrInput input)
```


छवि का विश्लेषण करता है और उसके भीतर विभिन्न प्रकार के सामग्री क्षेत्रों की पहचान करता है। GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | स्रोतों के साथ कंटेनर.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LayoutOutput> - पहचाने गए सामग्री क्षेत्र। [LayoutOutput](../../com.aspose.ocr.models/layoutoutput/) की ArrayList।
### DetectLanguages(OcrInput input) {#DetectLanguages-com.aspose.ocr.OcrInput}
```
public ArrayList<LanguageDetectionOutput> DetectLanguages(OcrInput input)
```


छवि पर पाठ का विश्लेषण करता है ताकि यह निर्धारित किया जा सके कि वह किस भाषा में लिखा गया है। यह सबसे उपयुक्त पहचान भाषा चुनने में मदद करता है और वर्तनी जांच या अनुवाद जैसे आगे के पाठ प्रसंस्करण कार्यों में सहायक होता है। GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | स्रोतों के साथ कंटेनर.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LanguageDetectionOutput> - सबसे संभावित भाषाओं की सूची लौटाता है, संभावना के आधार पर क्रमबद्ध। [LanguageDetectionOutput](../../com.aspose.ocr.models/languagedetectionoutput/) की ArrayList।
### DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas) {#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean}
```
public ArrayList<RectangleOutput> DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)
```


छवियों में पाठ क्षेत्रों का पता लगाता है। GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | स्रोतों के साथ कंटेनर.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| areasType | [AreasType](../../com.aspose.ocr.models/areastype/) | निर्धारित करता है कि कौन से आयत लौटाए जाएँ - पंक्ति या पैराग्राफ। |
| isDetectAreas | boolean | स्वचालित पाठ क्षेत्रों का पता लगाने को सक्षम करें। |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) की ArrayList जिसमें पता लगाए गए पाठ क्षेत्रों या पंक्तियों शामिल हैं।
### DetectTables(OcrInput images) {#DetectTables-com.aspose.ocr.OcrInput}
```
public ArrayList<RectangleOutput> DetectTables(OcrInput images)
```


छवियों में तालिका क्षेत्रों का पता लगाता है। GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | स्रोतों के साथ कंटेनर.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) की ArrayList जिसमें पता लगाए गए तालिका क्षेत्रों शामिल हैं।
### ImageHasText(String fullPath, String text) {#ImageHasText-java.lang.String-java.lang.String}
```
public boolean ImageHasText(String fullPath, String text)
```


केस-इन्सेंसिटिव खोज के साथ जाँचें कि छवि में प्रदान किया गया पाठ अंश मौजूद है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullPath | java.lang.String | छवि का पथ। |
| text | java.lang.String | छवि पर खोज के लिए पाठ अंश। |

**Returns:**
boolean - true यदि छवि में पाठ अंश मौजूद है। false - छवि में पाठ अंश नहीं है।
### ImageHasText(String fullPath, String text, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings)
```


केस-इन्सेंसिटिव खोज के साथ जाँचें कि छवि में प्रदान किया गया पाठ अंश मौजूद है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullPath | java.lang.String | छवि का पथ। |
| text | java.lang.String | छवि पर खोज के लिए पाठ अंश। |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | पहचान सेटिंग्स। |

**Returns:**
boolean - true यदि छवि में पाठ अंश मौजूद है। false - छवि में पाठ अंश नहीं है।
### ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)
```


जाँचें कि छवि में प्रदान किया गया पाठ अंश मौजूद है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullPath | java.lang.String | छवि का पथ। |
| text | java.lang.String | छवि पर खोज के लिए पाठ अंश। |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | पहचान सेटिंग्स। |
| ignoreCase | boolean | True - इसका अर्थ है केस‑इन्सेंसिटिव खोज। |

**Returns:**
boolean - true यदि छवि में पाठ अंश मौजूद है। false - छवि में पाठ अंश नहीं है।
### ImageHasText(String fullPath, Pattern regex) {#ImageHasText-java.lang.String-java.util.regex.Pattern}
```
public boolean ImageHasText(String fullPath, Pattern regex)
```


जाँचें कि छवि का पाठ प्रदान किए गए रेगुलर एक्सप्रेशन से मेल खाता है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullPath | java.lang.String | छवि का पथ। |
| regex | java.util.regex.Pattern | java.util.regex.Pattern ऑब्जेक्ट जिसमें प्रदान किया गया पैटर्न और विकल्प होते हैं। |

**Returns:**
boolean - true यदि छवि का पाठ प्रदान किए गए नियमित अभिव्यक्ति से मेल खाता है।
### ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)
```


जाँचें कि छवि का पाठ प्रदान किए गए रेगुलर एक्सप्रेशन से मेल खाता है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullPath | java.lang.String | छवि का पथ। |
| regex | java.util.regex.Pattern | java.util.regex.Pattern ऑब्जेक्ट जिसमें प्रदान किया गया पैटर्न और विकल्प होते हैं। |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | पहचान सेटिंग्स। |

**Returns:**
boolean - true यदि छवि का पाठ प्रदान किए गए नियमित अभिव्यक्ति से मेल खाता है।
### ImageTextDiff(String fullPath1, String fullPath2) {#ImageTextDiff-java.lang.String-java.lang.String}
```
public float ImageTextDiff(String fullPath1, String fullPath2)
```


दोनों छवियों के पाठों की तुलना करें और एक संख्या लौटाएँ जो उनके समानता को दर्शाती है (0 से 1)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullPath1 | java.lang.String | पहली इमेज का पाथ। |
| fullPath2 | java.lang.String | दूसरी इमेज का पाथ। |

**Returns:**
float - 0 का अर्थ है कि पाठ पूरी तरह अलग हैं; 1 का अर्थ है कि पाठ समान हैं।
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)
```


दोनों छवियों के पाठों की तुलना करें और एक संख्या लौटाएँ जो उनके समानता को दर्शाती है (0 से 1)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullPath1 | java.lang.String | पहली इमेज का पाथ। |
| fullPath2 | java.lang.String | दूसरी इमेज का पाथ। |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | पहचान सेटिंग्स। |

**Returns:**
float - 0 का अर्थ है कि पाठ पूरी तरह अलग हैं; 1 का अर्थ है कि पाठ समान हैं।
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


दोनों छवियों के पाठों की तुलना करें और एक संख्या लौटाएँ जो उनके समानता को दर्शाती है (0 से 1)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullPath1 | java.lang.String | पहली इमेज का पाथ। |
| fullPath2 | java.lang.String | दूसरी इमेज का पाथ। |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | पहचान सेटिंग्स। |
| ignoreCase | boolean | True - इसका अर्थ है केस‑इन्सेंसिटिव खोज। |

**Returns:**
float - 0 का अर्थ है कि पाठ पूरी तरह अलग हैं; 1 का अर्थ है कि पाठ समान हैं।
### Recognize(OcrInput input) {#Recognize-com.aspose.ocr.OcrInput}
```
public OcrOutput Recognize(OcrInput input)
```


छवि को पहचानता है जिसमें आप निर्दिष्ट कर सकते हैं कि यह GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 को सपोर्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). उदाहरण। |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### Recognize(OcrInput input, RecognitionSettings settings) {#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings}
```
public OcrOutput Recognize(OcrInput input, RecognitionSettings settings)
```


छवि को पहचानता है जिसमें आप निर्दिष्ट कर सकते हैं कि यह GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 को सपोर्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). उदाहरण। |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings) {#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings}
```
public OcrOutput RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)
```


कार प्लेट को पहचानता है जिसमें आप निर्दिष्ट कर सकते हैं कि यह GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 को सपोर्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). उदाहरण। |
| settings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCharacters(OcrInput input) {#RecognizeCharacters-com.aspose.ocr.OcrInput}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input)
```


छवियों में प्रतीकों का पता लगाता है। GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | स्रोतों के साथ कंटेनर.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - प्रत्येक छवि के लिए पता लगाए गए प्रतीकों के डेटा के साथ [Character](../../com.aspose.ocr.models/character/) की ArrayList।
### RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language) {#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)
```


छवियों में प्रतीकों का पता लगाता है। GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | स्रोतों के साथ कंटेनर.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | क्षेत्रों के पता लगाने के लिए उपयोग किए जाने वाले न्यूरल नेटवर्क का प्रकार निर्धारित करता है। |
| language | [Language](../../com.aspose.ocr.models/language/) | OCR के लिए उपयोग की जाने वाली भाषा। |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - पता लगाए गए प्रतीकों के डेटा के साथ [Character](../../com.aspose.ocr.models/character/) की ArrayList।
### RecognizeFast(OcrInput input) {#RecognizeFast-com.aspose.ocr.OcrInput}
```
public ArrayList<String> RecognizeFast(OcrInput input)
```


उच्च गुणवत्ता वाली छवि पर पाठ को पहचानता है। स्वचालित छवि विकृति सुधार और पाठ क्षेत्रों का पता लगाने का उपयोग नहीं करता। GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/) का उदाहरण। |

**Returns:**
java.util.ArrayList<java.lang.String> - पहचाने गए पाठ वाली ArrayList।
### RecognizeFormula(OcrInput input, boolean detectAreas) {#RecognizeFormula-com.aspose.ocr.OcrInput-boolean}
```
public OcrOutput RecognizeFormula(OcrInput input, boolean detectAreas)
```


प्रदान किए गए इनपुट छवियों से गणितीय सूत्रों को पहचानता है। GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). उदाहरण। |
| detectAreas | boolean | यदि true पर सेट किया गया है, तो पहचान करने से पहले स्वचालित रूप से सूत्र क्षेत्रों का पता लगाता है और उन्हें अलग करता है। यदि false है, तो पूरी छवि को एक सूत्र के रूप में प्रोसेस करता है। |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - OcrOutput list with images recognition results [OcrOutput](../../com.aspose.ocr/ocroutput/)
### RecognizeHandwrittenText(OcrInput input) {#RecognizeHandwrittenText-com.aspose.ocr.OcrInput}
```
public OcrOutput RecognizeHandwrittenText(OcrInput input)
```


छवियों पर हस्तलिखित पाठ को पहचानता है। GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). स्रोतों वाला कंटेनर। |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings) {#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings}
```
public OcrOutput RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)
```


आईडी कार्ड को पहचानता है जिसमें आप निर्दिष्ट कर सकते हैं कि यह GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 को सपोर्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). उदाहरण। |
| settings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings) {#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings}
```
public OcrOutput RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)
```


इनवॉइस को पहचानता है जिसमें आप निर्दिष्ट कर सकते हैं कि यह GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 को सपोर्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). उदाहरण। |
| settings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizePassport(OcrInput input, PassportRecognitionSettings settings) {#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings}
```
public OcrOutput RecognizePassport(OcrInput input, PassportRecognitionSettings settings)
```


निर्दिष्ट करने की क्षमता के साथ पासपोर्ट को पहचानता है। GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). उदाहरण। |
| settings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings) {#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings}
```
public OcrOutput RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)
```


रसीदों को पहचानता है और निर्दिष्ट करने की क्षमता रखता है। GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). उदाहरण। |
| settings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeTables(OcrInput input, Language language) {#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language}
```
public ArrayList<OCRTablePage> RecognizeTables(OcrInput input, Language language)
```


टेबल और संरचना का पता लगाता है, पाठ कोशिकाओं को पहचानता है। GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). उदाहरण। |
| language | [Language](../../com.aspose.ocr.models/language/) | पहचान के दौरान उपयोग किए जाने वाले वर्णमाला को निर्धारित करता है। |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.OCRTablePage> - तालिकाओं में पहचाने गए पाठ के साथ OCRTablePage सूची वस्तुएँ। [OCRTablePage](../../com.aspose.ocr.models/ocrtablepage/)
### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)
```


RecognitionResult ऑब्जेक्ट्स की सूची से मल्टीपेज दस्तावेज़ प्राप्त करने की अनुमति देता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | चयनित प्रारूप में पहचान परिणाम को सहेजने के लिए OutputStream। |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | दस्तावेज़ प्रारूप (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf)। |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | सूची [RecognitionResult](../../com.aspose.ocr/recognitionresult/) वस्तुओं की। |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


RecognitionResult ऑब्जेक्ट्स की सूची से मल्टीपेज दस्तावेज़ प्राप्त करने की अनुमति देता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | चयनित प्रारूप में पहचान परिणाम को सहेजने के लिए OutputStream। |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | दस्तावेज़ प्रारूप (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf)। |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | सूची [RecognitionResult](../../com.aspose.ocr/recognitionresult/) वस्तुओं की। |
| embeddedFontPath | java.lang.String | वैकल्पिक रूप से। उपयोगकर्ता फ़ॉन्ट का पूर्ण पथ। |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


RecognitionResult ऑब्जेक्ट्स की सूची से मल्टीपेज दस्तावेज़ प्राप्त करने की अनुमति देता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | चयनित प्रारूप में पहचान परिणाम को सहेजने के लिए OutputStream। |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | दस्तावेज़ प्रारूप (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf)। |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | सूची [RecognitionResult](../../com.aspose.ocr/recognitionresult/) वस्तुओं की। |
| embeddedFontPath | java.lang.String | वैकल्पिक रूप से। उपयोगकर्ता फ़ॉन्ट का पूर्ण पथ। |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | पृष्ठभूमि छवियों की गुणवत्ता कम करके PDF फ़ाइल का आकार घटाएँ। डिफ़ॉल्ट रूप में, मूल छवि गुणवत्ता बरकरार रहती है। |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)
```


RecognitionResult ऑब्जेक्ट्स की सूची से मल्टीपेज दस्तावेज़ प्राप्त करने की अनुमति देता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullFileName | java.lang.String | चयनित प्रारूप में पहचान परिणाम सहेजने के लिए पथ सहित फ़ाइलनाम। |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | दस्तावेज़ प्रारूप (Docx, Txt, Pdf, Xlsx, Xml, Json)। |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | सूची [RecognitionResult](../../com.aspose.ocr/recognitionresult/) वस्तुओं की। |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)
```


स्पेल‑चेक सुधार के साथ RecognitionResult ऑब्जेक्ट्स की सूची से मल्टीपेज दस्तावेज़ प्राप्त करने की अनुमति देता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullFileName | java.lang.String | चयनित प्रारूप में पहचान परिणाम सहेजने के लिए पथ सहित फ़ाइलनाम। |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | दस्तावेज़ प्रारूप (Docx, Txt, Pdf, Xlsx, Xml, Json)। |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | सूची [RecognitionResult](../../com.aspose.ocr/recognitionresult/) वस्तुओं की। |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) enum मान। |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


RecognitionResult ऑब्जेक्ट्स की सूची से मल्टीपेज दस्तावेज़ प्राप्त करने की अनुमति देता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullFileName | java.lang.String | चयनित प्रारूप में पहचान परिणाम सहेजने के लिए पथ सहित फ़ाइलनाम। |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | दस्तावेज़ प्रारूप (Docx, Txt, Pdf, Xlsx, Xml, Json)। |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | सूची [RecognitionResult](../../com.aspose.ocr/recognitionresult/) वस्तुओं की। |
| embeddedFontPath | java.lang.String | वैकल्पिक रूप से। उपयोगकर्ता फ़ॉन्ट का पूर्ण पथ। |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


RecognitionResult ऑब्जेक्ट्स की सूची से मल्टीपेज दस्तावेज़ प्राप्त करने की अनुमति देता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullFileName | java.lang.String | चयनित प्रारूप में पहचान परिणाम सहेजने के लिए पथ सहित फ़ाइलनाम। |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | दस्तावेज़ प्रारूप (Docx, Txt, Pdf, Xlsx, Xml, Json)। |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | सूची [RecognitionResult](../../com.aspose.ocr/recognitionresult/) वस्तुओं की। |
| embeddedFontPath | java.lang.String | वैकल्पिक रूप से। उपयोगकर्ता फ़ॉन्ट का पूर्ण पथ। |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | पृष्ठभूमि छवियों की गुणवत्ता कम करके PDF फ़ाइल का आकार घटाएँ। डिफ़ॉल्ट रूप में, मूल छवि गुणवत्ता बरकरार रहती है। |

### close() {#close}
```
public void close()
```