---
title: "RecognitionSettings"
second_title: "Aspose.OCR Python के लिए via .NET API संदर्भ"
description: 
type: docs
weight: 330
url: /hi/python-net/aspose.ocr/recognitionsettings/
---

## RecognitionSettings class

छवि पहचान के लिए सेटिंग्स।<br/>            पहचान प्रक्रिया को अनुकूलित करने की अनुमति देने वाले तत्व शामिल हैं।

RecognitionSettings प्रकार निम्नलिखित सदस्य उजागर करता है:
## निर्माता
| नाम | विवरण |
| :- | :- |
| RecognitionSettings() | नया उदाहरण प्रारंभ करता है |
| RecognitionSettings(language, recognition_areas, recognize_single_line) | RecognitionSettings वर्ग का नया उदाहरण प्रारंभ करता है |
## गुणधर्म
| नाम | विवरण |
| :- | :- |
| recognize_vertical_lines |  |
| threads_count | प्रसंस्करण के लिए थ्रेड्स की संख्या प्राप्त करता है या सेट करता है। |
| language | OCR के लिए उपयोग की जाने वाली भाषा प्राप्त करता है या सेट करता है। |
| ignored_symbols | पहचान प्रतीकों के लिए ब्लैकलिस्ट सेट करता है। |
| allowed_symbols | वर्णमाला प्रॉपर्टी के साथ अनुमत अक्षर सेट करें। |
| allowed_characters | अनुमत अक्षरों का सेट। पहचान परिणाम के लिए अनुमत अक्षरों के प्रकार को निर्धारित करता है। |
| automatic_color_inversion | डार्क/काले पृष्ठभूमि पर सफेद टेक्स्ट वाली छवियों का पता लगाएँ और उनके लिए स्वचालित रूप से एक विशेष OCR एल्गोरिद्म चुनें। |
| recognition_areas | प्रसंस्करण के लिए पाठ क्षेत्रों की सूची प्राप्त करता है या सेट करता है। |
| recognize_single_line | एकल-लाइन छवि पहचान सेट करता है। <br/> डिफ़ॉल्ट रूप से अक्षम (false)। <br/> लाइनों में विभाजन से संबंधित सभी प्रोसेसिंग चरणों को अक्षम करता है। <br/> यदि आपकी छवि में केवल एक लाइन है तो इस पैरामीटर को true सेट करें। RecognitionAreas सेटिंग्स को अक्षम करता है, इसलिए सभी क्षेत्र सेटिंग्स को नजरअंदाज़ किया जाएगा। |
| language_detection_level |  |
| lines_filtration | टेबल्स में टेक्स्ट पहचानने की अनुमति देता है (रेखाओं से घिरे क्षेत्रों)। |
| detect_areas_mode | दस्तावेज़ प्रकार क्षेत्रों के लिए इष्टतम मोड चुनने की अनुमति देता है: दस्तावेज़, फोटो, साधारण टेक्स्ट, कॉलम, छवि। |
| upscale_small_font | छोटे फ़ॉन्ट पहचान के लिए विशेष रूप से अतिरिक्त एल्गोरिदम उपयोग करने की अनुमति देता है।<br/> छोटे आकार के अक्षरों वाली छवियों के लिए उपयोगी। |

### संबंधित देखें

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

