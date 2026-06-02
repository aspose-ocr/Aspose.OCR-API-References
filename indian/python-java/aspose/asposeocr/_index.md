---
title: "AsposeOcr"
second_title: "Aspose.OCR के लिए Python, Java API संदर्भ"
description: 
type: docs
weight: 11
url: /hi/python-java/aspose/asposeocr/
---


मॉड्यूल asposeocr
================
Aspose OCR के लिए Python इंटरफ़ेस

**Aspose.OCR for Python via .Java** is a powerful,
जबकि उपयोग में आसान ऑप्टिकल कैरेक्टर रिकग्निशन (OCR)
आपके Python अनुप्रयोगों और नोटबुक्स के लिए इंजन।
कोड की **10** से कम पंक्तियों में, आप पहचान सकते हैं
पाठ **28** भाषाओं में, लैटिन, सिरिलिक पर आधारित,
और एशियाई लिपियों में, सबसे लोकप्रिय
दस्तावेज़ और डेटा विनिमय स्वरूपों में।
जटिल गणितीय मॉडलों को सीखने की आवश्यकता नहीं है,
मशीन लर्निंग एल्गोरिदम बनाएं और न्यूरल
नेटवर्क्स — हमारा सरल और मजबूत API आपके लिए सब कुछ करेगा।

क्लासेस
-------

`AsposeOcr()`
:
AsposeOcr पहचान के लिए मुख्य क्लास।
    
यह उदाहरण दिखाता है कि छवि को कैसे पहचानें।
\code
api = AsposeOcr()
input = OcrInput(InputType.SINGLE_IMAGE)
input.add(os.path.join(self.dataDir, "SpanishOCR.bmp"))
result = api.recognize(input)
\endcode

### स्थैतिक विधियाँ

`save_multipage_document(fullFileName: str, saveFormat: aspose.models.Format, results: List)`
:
RecognitionResult वस्तुओं की सूची से मल्टीपेज दस्तावेज़ प्राप्त करने की अनुमति देता है।
@param fullFileName: चयनित स्वरूप में पहचान परिणाम को सहेजने के लिए पथ सहित फ़ाइलनाम।
@param saveFormat: दस्तावेज़ स्वरूप (Docx, Txt, Pdf, Xlsx, Xml, Json)।
@param results:

### विधियाँ

`calculate_skew(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.SkewOutput]`
:
एक छवि के विकृति कोणों की गणना करता है।
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, बाइनरी एरे, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।
@param input: :py:any:`~aspose.models.OcrInput`. उदाहरण। स्रोतों वाला कंटेनर।
@return: डिग्री में विकृति कोणों की सूची - SkewOutput.

`compare_image_texts(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
जाँचें कि दो छवियों में समान पाठ है या नहीं।
@param fullPath1: पहली छवि का पथ।
@param fullPath2: दूसरी छवि का पथ।
@param settings: पहचान सेटिंग्स।
@param ignoreCase: True - मतलब केस-इंसेंसिटिव खोज।
@return: True यदि छवियों में समान पाठ है (90% समानता)।

`correct_spelling(self, text: str, language: aspose.models.SpellCheckLanguage) ‑> str`
:
पाठ को ठीक करता है (गलत वर्तनी वाले शब्दों को बदलता है)।
@param text: सुधार के लिए पाठ।
@param language: SpellCheckLanguage के लिए शब्दकोश।
@return: बदले हुए शब्दों के साथ पाठ।

`detect_rectangles(self, input: aspose.models.OcrInput, areasType: aspose.models.AreasType, isDetectAreas: bool) ‑> List[aspose.recognitionresult.RectangleOutput]`
:
छवियों पर पाठ क्षेत्रों का पता लगाता है।
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, बाइनरी एरे, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।
@param input: :py:any:`~aspose.models.OcrInput`. उदाहरण।
@param areasType: निर्धारित करता है कि कौन से आयत लौटाए जाएँ - पंक्ति, पैराग्राफ या शब्द।
@param isDetectAreas: स्वचालित पाठ क्षेत्रों का पता लगाने को सक्षम करें।
@return: पता लगाए गए पाठ क्षेत्रों या पंक्तियों के साथ RectangleOutput की सूची।

`image_has_text(self, fullPath: str, text: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
जाँचें कि छवि में प्रदान किया गया पाठ अंश है या नहीं।
@param fullPath: छवि का पथ।
@param text: छवि पर खोजने के लिए टेक्स्ट अंश।
@param settings: पहचान सेटिंग्स।
@param ignoreCase: True - मतलब केस-इंसेंसिटिव खोज।
@return: सत्य यदि छवि में टेक्स्ट अंश मौजूद है। असत्य - छवि में टेक्स्ट अंश नहीं है।

`image_text_diff(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> float`
:
दो छवियों पर टेक्स्ट की तुलना करें और एक संख्या लौटाएँ जो दर्शाती है कि वे कितने समान हैं (0 से 1)।
@param fullPath1: पहली छवि का पथ।
@param fullPath2: दूसरी छवि का पथ।
@param settings: पहचान सेटिंग्स।
@param ignoreCase: True - मतलब केस-इंसेंसिटिव खोज।
@return: 0 का अर्थ है कि टेक्स्ट पूरी तरह अलग हैं; 1 का अर्थ है कि टेक्स्ट समान हैं।

`recognize(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
RecognitionSettings निर्दिष्ट करने की क्षमता के साथ छवि को पहचानता है।
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, बाइनरी एरे, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।
@param input: :py:any:`~aspose.models.OcrInput`. उदाहरण।
@param settings: RecognitionSettings ऑब्जेक्ट।
@return: छवियों की पहचान परिणामों के साथ RecognitionResult सूची।

`recognize_car_plate(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.CarPlateRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
CarPlateRecognitionSettings निर्दिष्ट करने की क्षमता के साथ कार प्लेट को पहचानता है।
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, बाइनरी एरे, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।
@param input: :py:any:`~aspose.models.OcrInput`. उदाहरण।
@param settings: CarPlateRecognitionSettings
@return: छवियों की पहचान परिणामों के साथ RecognitionResult सूची।

`recognize_fast(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
उच्च गुणवत्ता वाली छवि पर टेक्स्ट को पहचानता है। स्वचालित छवि विकृति सुधार और टेक्स्ट क्षेत्रों का उपयोग नहीं करता है
पता लगाना।
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, बाइनरी एरे, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।
@param input: :py:any:`~aspose.models.OcrInput`. उदाहरण।
@return: छवियों की पहचान परिणामों के साथ RecognitionResult सूची।

`recognize_id_card(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.IDCardRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
IDCardRecognitionSettings निर्दिष्ट करने की क्षमता के साथ आईडी कार्ड को पहचानता है।
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, बाइनरी एरे, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।
@param input: :py:any:`~aspose.models.OcrInput`. उदाहरण।
@param settings: IDCardRecognitionSettings
@return: छवियों की पहचान परिणामों के साथ RecognitionResult सूची।

`recognize_invoice(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.InvoiceRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
InvoiceRecognitionSettings निर्दिष्ट करने की क्षमता के साथ चालान को पहचानें
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, बाइनरी एरे, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।
@param input: :py:any:`~aspose.models.OcrInput`. उदाहरण।
@param settings: InvoiceRecognitionSettings
@return: छवियों की पहचान परिणामों के साथ RecognitionResult सूची।

`recognize_lines(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
RecognitionSettings निर्दिष्ट करने की क्षमता के साथ एकल पंक्ति छवि को पहचानता है।
@param input: :py:any:`~aspose.models.OcrInput`. उदाहरण।
@param settings: RecognitionSettings ऑब्जेक्ट।
@return: छवियों की पहचान परिणामों के साथ RecognitionResult सूची।

`recognize_passport(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.PassportRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
पासपोर्ट को पहचानता है और PassportRecognitionSettings निर्दिष्ट करने की क्षमता रखता है।
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, बाइनरी एरे, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।
@param input: :py:any:`~aspose.models.OcrInput`. उदाहरण।
@param settings: PassportRecognitionSettings
@return: छवियों की पहचान परिणामों के साथ RecognitionResult सूची।

`recognize_receipt(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.ReceiptRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
रसीदों को पहचानता है और ReceiptRecognitionSettings निर्दिष्ट करने की क्षमता रखता है।
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, बाइनरी एरे, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।
@param input: :py:any:`~aspose.models.OcrInput`. उदाहरण।
@param settings: ReceiptRecognitionSettings
@return: छवियों की पहचान परिणामों के साथ RecognitionResult सूची।

`recognize_street_photo(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
सड़क फोटो में टेक्स्ट को पहचानता है।
सड़क फोटो, ट्रैफ़िक कैमरा छवियों, आईडी कार्ड, ड्राइवर लाइसेंस और अन्य छवियों से, जिनमें विरल टेक्स्ट और शोरयुक्त/रंगीन पृष्ठभूमि हो, टेक्स्ट निकालें।
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, बाइनरी एरे, फ़ोल्डर, एरे, ज़िप आर्काइव, URL, base64 का समर्थन करता है।
@param input: :py:any:`~aspose.models.OcrInput`. उदाहरण।
@return: छवियों की पहचान परिणामों के साथ RecognitionResult सूची।

`shutdown(self)`
:
JVM मशीन को बंद करें।

`ImageProcessing()`
:
Aspose OCR लाइब्रेरी के लिए सहायक क्लास। छवियों को पूर्व-प्रसंस्करण और सहेजने की अनुमति देता है।

### स्थैतिक विधियाँ

`save(images, folderPath)`
:
OCR की सटीकता सुधारने के लिए इमेज प्रोसेसिंग का उपयोग करें।
फ़िल्टरों की एक सूची बनाएं जो इनपुट इमेज पर आपके द्वारा निर्दिष्ट क्रम में लागू होगी।
\code
filters = new PreprocessingFilter();
filters.add(PreprocessingFilter.auto_dewarping());
filters.add(PreprocessingFilter.invert());
filters.add(PreprocessingFilter.threshold(150));
filters.add(PreprocessingFilter.binarize());
filters.add(PreprocessingFilter.rotate(180));
filters.add(PreprocessingFilter.scale(6));
filters.add(PreprocessingFilter.dilate());
        
images = OcrInput(InputType.PDF, filters);
\endcode
आपको सभी की आवश्यकता नहीं है। केवल वही सेट करें जिसकी आपको ज़रूरत है।
@param images: विभिन्न छवियों को समाहित करने वाला OcrInput ऑब्जेक्ट OcrInput.
@param folderPath: प्रोसेस की गई छवियों को सहेजने के लिए छवि नामों के बिना पथ.
@return: परिणाम प्रोसेस की गई छवियों को समाहित करने वाला OcrInput ऑब्जेक्ट OcrInput.


### और देखें

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)