---
title: "RecognitionSettings"
second_title: "Aspose.OCR के लिए Python, Java API संदर्भ"
description: 
type: docs
weight: 191
url: /hi/python-java/aspose/recognitionsettings/
---

मॉड्यूल recognitionsettings
==========================

क्लासेस
-------

`CarPlateRecognitionSettings()`
:

### क्लास वेरिएबल्स

`JAVA_CLASS_NAME`
:

### विधियाँ

`set_allowed_characters(self, allowedCharacters: str)`
:
अनुमत अक्षरों का सेट। पहचान परिणाम के लिए अनुमत अक्षरों की एरे निर्धारित करता है।
@param allowedCharacters: अक्षरों की स्ट्रिंग शामिल करता है।

`set_ignored_characters(self, ignoredCharacters: str)`
:
पहचान प्रतीकों के लिए ब्लैकलिस्ट सेट करता है।
@param ignoredCharacters: पहचान से बाहर किए गए अक्षर।

`set_language(self, language: aspose.models.Language)`
:
OCR के लिए उपयोग की जाने वाली भाषा सेट करता है।
डिफ़ॉल्ट रूप से मल्टी-लैंग्वेज (कोई नहीं)।
@param language: enum Language मान शामिल करता है।

`set_threads_count(self, threadsCount: int)`
:
प्रोसेसिंग के लिए थ्रेड्स की संख्या प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट रूप से, 0 का अर्थ है कि छवि को आपके प्रोसेसर की संख्या के बराबर थ्रेड्स की संख्या के साथ प्रोसेस किया जाएगा।
ThreadsCount = 1 का मतलब है कि छवि मुख्य थ्रेड में प्रोसेस होगी।
@param threadsCount: छवि के टुकड़ों की समानांतर पहचान के लिए बनाए जाने वाले थ्रेड्स की संख्या।

`IDCardRecognitionSettings()`
:

### क्लास वेरिएबल्स

`JAVA_CLASS_NAME`
:

### विधियाँ

`set_allowed_characters(self, allowedCharacters: str)`
:
अनुमत अक्षरों का सेट। पहचान परिणाम के लिए अनुमत अक्षरों की एरे निर्धारित करता है।
@param allowedCharacters: अक्षरों की स्ट्रिंग शामिल करता है।

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
गहरे/काले पृष्ठभूमि पर सफेद टेक्स्ट वाली छवियों का पता लगाता है और उनके लिए स्वचालित रूप से एक विशेष OCR एल्गोरिद्म चुनता है।
@param automaticColorInversion: बूलियन मान शामिल करता है - automaticColorInversion सेट है। डिफ़ॉल्ट रूप से True।

`set_ignored_characters(self, ignoredCharacters: str)`
:
पहचान प्रतीकों के लिए ब्लैकलिस्ट सेट करता है।
@param ignoredCharacters: पहचान से बाहर किए गए अक्षर।

`set_language(self, language: aspose.models.Language)`
:
OCR के लिए उपयोग की जाने वाली भाषा सेट करता है।
डिफ़ॉल्ट रूप से मल्टी-लैंग्वेज (कोई नहीं)।
@param language: enum Language मान शामिल करता है।

`set_threads_count(self, threadsCount: int)`
:
प्रोसेसिंग के लिए थ्रेड्स की संख्या प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट रूप से, 0 का अर्थ है कि छवि को आपके प्रोसेसर की संख्या के बराबर थ्रेड्स की संख्या के साथ प्रोसेस किया जाएगा।
ThreadsCount = 1 का मतलब है कि छवि मुख्य थ्रेड में प्रोसेस होगी।
@param threadsCount: छवि के टुकड़ों की समानांतर पहचान के लिए बनाए जाने वाले थ्रेड्स की संख्या।

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
छोटे फ़ॉन्ट की पहचान के लिए विशेष रूप से अतिरिक्त एल्गोरिद्म का उपयोग करने की अनुमति देता है।
छोटे आकार के अक्षरों वाली छवियों के लिए उपयोगी।
@param upscaleSmallFont: बूलियन मान शामिल करता है - upscaleSmallFont सेट है।

`InvoiceRecognitionSettings()`
:

### क्लास वेरिएबल्स

`JAVA_CLASS_NAME`
:

### विधियाँ

`set_allowed_characters(self, allowedCharacters: str)`
:
अनुमत अक्षरों का सेट। पहचान परिणाम के लिए अनुमत अक्षरों की एरे निर्धारित करता है।
@param allowedCharacters: अक्षरों की स्ट्रिंग शामिल करता है।

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
गहरे/काले पृष्ठभूमि पर सफेद टेक्स्ट वाली छवियों का पता लगाता है और उनके लिए स्वचालित रूप से एक विशेष OCR एल्गोरिद्म चुनता है।
@param automaticColorInversion: बूलियन मान शामिल करता है - automaticColorInversion सेट है। डिफ़ॉल्ट रूप से True।

`set_ignored_characters(self, ignoredCharacters: str)`
:
पहचान प्रतीकों के लिए ब्लैकलिस्ट सेट करता है।
@param ignoredCharacters: पहचान से बाहर किए गए अक्षर।

`set_language(self, language: aspose.models.Language)`
:
OCR के लिए उपयोग की जाने वाली भाषा सेट करता है।
डिफ़ॉल्ट रूप से मल्टी-लैंग्वेज (कोई नहीं)।
@param language: enum Language मान शामिल करता है।

`set_threads_count(self, threadsCount: int)`
:
प्रोसेसिंग के लिए थ्रेड्स की संख्या प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट रूप से, 0 का अर्थ है कि छवि को आपके प्रोसेसर की संख्या के बराबर थ्रेड्स की संख्या के साथ प्रोसेस किया जाएगा।
ThreadsCount = 1 का मतलब है कि छवि मुख्य थ्रेड में प्रोसेस होगी।
@param threadsCount: छवि के टुकड़ों की समानांतर पहचान के लिए बनाए जाने वाले थ्रेड्स की संख्या।

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
छोटे फ़ॉन्ट की पहचान के लिए विशेष रूप से अतिरिक्त एल्गोरिद्म का उपयोग करने की अनुमति देता है।
छोटे आकार के अक्षरों वाली छवियों के लिए उपयोगी।
@param upscaleSmallFont: बूलियन मान शामिल करता है - upscaleSmallFont सेट है।

`PassportRecognitionSettings()`
:

### क्लास वेरिएबल्स

`JAVA_CLASS_NAME`
:

### विधियाँ

`set_allowed_characters(self, allowedCharacters: str)`
:
अनुमत अक्षरों का सेट। पहचान परिणाम के लिए अनुमत अक्षरों की एरे निर्धारित करता है।
@param allowedCharacters: अक्षरों की स्ट्रिंग शामिल करता है।

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
गहरे/काले पृष्ठभूमि पर सफेद टेक्स्ट वाली छवियों का पता लगाता है और उनके लिए स्वचालित रूप से एक विशेष OCR एल्गोरिद्म चुनता है।
@param automaticColorInversion: बूलियन मान शामिल करता है - automaticColorInversion सेट है। डिफ़ॉल्ट रूप से True।

`set_ignored_characters(self, ignoredCharacters: str)`
:
पहचान प्रतीकों के लिए ब्लैकलिस्ट सेट करता है।
@param ignoredCharacters: पहचान से बाहर किए गए अक्षर।

`set_language(self, language: aspose.models.Language)`
:
OCR के लिए उपयोग की जाने वाली भाषा सेट करता है।
डिफ़ॉल्ट रूप से मल्टी-लैंग्वेज (कोई नहीं)।
@param language: enum Language मान शामिल करता है।

`set_threads_count(self, threadsCount: int)`
:
प्रोसेसिंग के लिए थ्रेड्स की संख्या प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट रूप से, 0 का अर्थ है कि छवि को आपके प्रोसेसर की संख्या के बराबर थ्रेड्स की संख्या के साथ प्रोसेस किया जाएगा।
ThreadsCount = 1 का मतलब है कि छवि मुख्य थ्रेड में प्रोसेस होगी।
@param threadsCount: छवि के टुकड़ों की समानांतर पहचान के लिए बनाए जाने वाले थ्रेड्स की संख्या।

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
छोटे फ़ॉन्ट की पहचान के लिए विशेष रूप से अतिरिक्त एल्गोरिद्म का उपयोग करने की अनुमति देता है।
छोटे आकार के अक्षरों वाली छवियों के लिए उपयोगी।
@param upscaleSmallFont: बूलियन मान शामिल करता है - upscaleSmallFont सेट है।

`ReceiptRecognitionSettings()`
:

### क्लास वेरिएबल्स

`JAVA_CLASS_NAME`
:

### विधियाँ

`set_allowed_characters(self, allowedCharacters: str)`
:
अनुमत अक्षरों का सेट। पहचान परिणाम के लिए अनुमत अक्षरों की एरे निर्धारित करता है।
@param allowedCharacters: अक्षरों की स्ट्रिंग शामिल करता है।

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
गहरे/काले पृष्ठभूमि पर सफेद टेक्स्ट वाली छवियों का पता लगाता है और उनके लिए स्वचालित रूप से एक विशेष OCR एल्गोरिद्म चुनता है।
@param automaticColorInversion: बूलियन मान शामिल करता है - automaticColorInversion सेट है। डिफ़ॉल्ट रूप से True।

`set_ignored_characters(self, ignoredCharacters: str)`
:
पहचान प्रतीकों के लिए ब्लैकलिस्ट सेट करता है।
@param ignoredCharacters: पहचान से बाहर किए गए अक्षर।

`set_language(self, language: aspose.models.Language)`
:
OCR के लिए उपयोग की जाने वाली भाषा सेट करता है।
डिफ़ॉल्ट रूप से मल्टी-लैंग्वेज (कोई नहीं)।
@param language: enum Language मान शामिल करता है।

`set_threads_count(self, threadsCount: int)`
:
प्रोसेसिंग के लिए थ्रेड्स की संख्या प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट रूप से, 0 का अर्थ है कि छवि को आपके प्रोसेसर की संख्या के बराबर थ्रेड्स की संख्या के साथ प्रोसेस किया जाएगा।
ThreadsCount = 1 का मतलब है कि छवि मुख्य थ्रेड में प्रोसेस होगी।
@param threadsCount: छवि के टुकड़ों की समानांतर पहचान के लिए बनाए जाने वाले थ्रेड्स की संख्या।

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
छोटे फ़ॉन्ट की पहचान के लिए विशेष रूप से अतिरिक्त एल्गोरिद्म का उपयोग करने की अनुमति देता है।
छोटे आकार के अक्षरों वाली छवियों के लिए उपयोगी।
@param upscaleSmallFont: बूलियन मान शामिल करता है - upscaleSmallFont सेट है।

`RecognitionSettings()`
:
छवि पहचान के लिए सेटिंग्स।
ऐसे तत्व शामिल हैं जो पहचान प्रक्रिया को अनुकूलित करने की अनुमति देते हैं।
    
    
डिफ़ॉल्ट कन्स्ट्रक्टर: recognitionAreas को null सेट करें, linesFiltration को false, autoSkew को false, recognizeSingleLine को false सेट करें।

### क्लास वेरिएबल्स

`JAVA_CLASS_NAME`
:

### विधियाँ

`set_allowed_characters(self, allowedCharacters: str)`
:
अनुमत अक्षरों का सेट। पहचान परिणाम के लिए अनुमत अक्षरों की एरे निर्धारित करता है।
@param allowedCharacters: अक्षरों की स्ट्रिंग शामिल करता है।

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
गहरे/काले पृष्ठभूमि पर सफेद टेक्स्ट वाली छवियों का पता लगाता है और उनके लिए स्वचालित रूप से एक विशेष OCR एल्गोरिद्म चुनता है।
@param automaticColorInversion: बूलियन मान शामिल करता है - automaticColorInversion सेट है। डिफ़ॉल्ट रूप से True।

`set_detect_areas_mode(self, detectAreasMode: aspose.models.DetectAreasMode)`
:
क्षेत्र पहचान के लिए उपयोग किए गए न्यूरल नेटवर्क के प्रकार को निर्धारित करता है।
@param detectAreasMode: इसमें enum DetectAreasMode मान शामिल है।

`set_ignored_characters(self, ignoredCharacters: str)`
:
पहचान प्रतीकों के लिए ब्लैकलिस्ट सेट करता है।
@param ignoredCharacters: पहचान से बाहर किए गए अक्षर।

`set_language(self, language: aspose.models.Language)`
:
OCR के लिए उपयोग की जाने वाली भाषा सेट करता है।
डिफ़ॉल्ट रूप से मल्टी-लैंग्वेज (कोई नहीं)।
@param language: enum Language मान शामिल करता है।

`set_recognize_single_line(self, recognizeSingleLine: bool)`
:
एक-लाइन छवि पहचान सेट करता है।
डिफ़ॉल्ट रूप से अक्षम (false)।
लाइन में विभाजन से संबंधित सभी प्रोसेसिंग चरणों को अक्षम करें।
यदि आपकी छवि में केवल एक लाइन है तो इस पैरामीटर को true सेट करें। set_recognition_areas सेटिंग्स को अक्षम करता है, इसलिए सभी क्षेत्र सेटिंग्स को नजरअंदाज़ किया जाएगा।
@param recognizeSingleLine: एक-लाइन छवि के लिए True

`set_threads_count(self, threadsCount: int)`
:
प्रोसेसिंग के लिए थ्रेड्स की संख्या प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट रूप से, 0 का अर्थ है कि छवि को आपके प्रोसेसर की संख्या के बराबर थ्रेड्स की संख्या के साथ प्रोसेस किया जाएगा।
ThreadsCount = 1 का मतलब है कि छवि मुख्य थ्रेड में प्रोसेस होगी।
@param threadsCount: छवि के टुकड़ों की समानांतर पहचान के लिए बनाए जाने वाले थ्रेड्स की संख्या।

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
छोटे फ़ॉन्ट की पहचान के लिए विशेष रूप से अतिरिक्त एल्गोरिद्म का उपयोग करने की अनुमति देता है।
छोटे आकार के अक्षरों वाली छवियों के लिए उपयोगी।
@param upscaleSmallFont: बूलियन मान शामिल करता है - upscaleSmallFont सेट है।



### और देखें

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)