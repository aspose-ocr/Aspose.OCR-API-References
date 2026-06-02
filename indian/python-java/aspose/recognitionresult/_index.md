---
title: "RecognitionResult"
second_title: "Aspose.OCR के लिए Python, Java API संदर्भ"
description: 
type: docs
weight: 171
url: /hi/python-java/aspose/recognitionresult/
---

मॉड्यूल recognitionresult
========================

क्लासेस
-------

`LinesResult(javaClass)`
:

### पूर्वज (in MRO)

    * aspose.helper.BaseJavaClass

### विधियाँ

`initParams(self)`
:

`RecognitionResult(javaClass)`
:
छवि पहचान के परिणाम। पहचान वाले तत्वों को समाहित करता है
परिणाम निर्यात के लिए जानकारी और विधियाँ।

### स्थैतिक विधियाँ

`save_multipage_document(self, fullPath: str)`
:
निजी

### इंस्टेंस वेरिएबल्स

`recognition_areas_text`
:   क्षेत्रों (आयत) की सूची के पहचान परिणामों की सूची।

`recognition_lines_result`
:   पंक्तियों (आयत) की सूची के साथ पहचान परिणामों की सूची प्राप्त करता है।

### विधियाँ

`getJavaClass(self)`
:

`get_json(self)`
:
पहचान परिणामों के साथ JSON स्ट्रिंग बनाएं।
@return: JSON स्ट्रिंग के रूप में पहचान परिणाम।

`get_spell_check_corrected_text(self, language: aspose.models.SpellCheckLanguage) ‑> str`
:
पाठ को ठीक करता है (गलत वर्तनी वाले शब्दों को बदलता है)।
@param language: उपयोग करने के लिए शब्दकोश।
@return: सुधारा गया पहचान परिणाम स्ट्रिंग।

`get_spell_check_error_list(self, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
दिए गए इनपुट टेक्स्ट के लिए सुझाए गए वर्तनी के साथ गलत लिखे शब्द खोजें।
@param language: उपयोग करने के लिए शब्दकोश।
@return: SpellCheckError ऑब्जेक्ट की सूची जो प्रत्येक गलत शब्द को दर्शाती है, जिसमें सुझाए गए सही वर्तनी की सूचियाँ होती हैं,
और संपादन दूरी के साथ।

`get_xml(self)`
:
पहचान परिणामों के साथ JSON स्ट्रिंग बनाएं।
@return: पहचान परिणाम XML स्ट्रिंग के रूप में।

`init(self)`
:

`save(self, fullFileName: str, format: aspose.models.Format)`
:
दस्तावेज़ को साधारण टेक्स्ट या अन्य दस्तावेज़ फ़ॉर्मेट में सहेजता है।
@param fullFileName: पहचान परिणाम सहेजने के लिए पथ के साथ फ़ाइलनाम।
@param format: फ़ॉर्मेट का दस्तावेज़ फ़ॉर्मेट एन्‍युम प्रकार।

`save_spell_check_corrected_text(self, fullFileName: str, format: aspose.models.Format, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
पाठ को ठीक करता है (गलत वर्तनी वाले शब्दों को बदलता है)।
सही किया गया टेक्स्ट दस्तावेज़ में साधारण टेक्स्ट या अन्य फ़ॉर्मेट में सहेजता है।
@param fullFileName: पहचान परिणाम सहेजने के लिए पथ के साथ फ़ाइलनाम
@param format: फ़ॉर्मेट का दस्तावेज़ फ़ॉर्मेट एन्‍युम प्रकार।
@param language: वर्तनी जांच के लिए शब्दकोश।

`use_user_dictionary(self, dictionaryPath: str)`
:
वर्तनी‑जांच सुधार के लिए अपना शब्दकोश उपयोग करने की अनुमति देता है।
@param dictionaryPath: उपयोगकर्ता शब्दकोश (आवृत्ति शब्दकोश) का पूर्ण पथ।
शब्दकोश फ़ाइल फ़ॉर्मेट:
UTF-8 एन्कोडिंग में साधारण टेक्स्ट फ़ाइल।
शब्द और शब्द आवृत्ति को कॉमा से अलग किया जाता है, शब्द पहली कॉलम में और आवृत्ति दूसरी कॉलम में अपेक्षित है।
हर शब्द‑आवृत्ति‑जोड़ी एक अलग पंक्ति में। एक पंक्ति को वर्णों की श्रृंखला के रूप में परिभाषित किया जाता है जो लाइन फ़ीड ("
") , कैरिज रिटर्न ("
"),
या एक कैरिज रिटर्न जो तुरंत लाइन फीड के बाद आता है("

").
प्रत्येक शब्द को लोअर केस में होने की अपेक्षा है।
उदाहरण:
\code
word,5984819
hello,5761742
down,5582768
\endcode

`RectangleOutput(javaClass)`
:
पता लगाए गए टेक्स्ट क्षेत्रों या लाइनों के बारे में डेटा।
\code
source - फ़ाइल या URL का पूर्ण पथ, यदि कोई हो। स्ट्रीम, बाइट एरे, base64 के लिए खाली।
page - पृष्ठ संख्या।
image_index - पृष्ठ पर छवि का क्रमांक।
rectangles - पहचाने गए टेक्स्ट क्षेत्रों या लाइनों की सूची।
\endcode

### पूर्वज (in MRO)

    * aspose.helper.BaseJavaClass

### विधियाँ

`initParams(self)`
:

`SkewOutput(javaClass)`
:
डिग्री में विकृति कोण और फ़ाइल के नाम के बारे में डेटा।
\code
source - फ़ाइल या URL का पूर्ण पथ, यदि कोई हो। स्ट्रीम, बाइट एरे, base64 के लिए खाली।
page - पृष्ठ संख्या।
image_index - पृष्ठ पर छवि का क्रमांक।
angle - डिग्री में स्क्यू कोण।
\endcode

### पूर्वज (in MRO)

    * aspose.helper.BaseJavaClass

### विधियाँ

`initParams(self)`
:


### और देखें

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)