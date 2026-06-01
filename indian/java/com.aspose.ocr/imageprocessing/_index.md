---
title: "ImageProcessing"
second_title: "Aspose.OCR जावा के लिए API संदर्भ"
description: "Aspose OCR लाइब्रेरी के लिए सहायक क्लास"
type: docs
weight: 19
url: /hi/java/com.aspose.ocr/imageprocessing/
---

**Inheritance:**
java.lang.Object
```
public class ImageProcessing
```

Aspose OCR लाइब्रेरी के लिए सहायक क्लास। छवियों को पूर्व-प्रसंस्करण और सहेजने की अनुमति देता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [ImageProcessing()](#ImageProcessing) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [Render(OcrInput images)](#Render-com.aspose.ocr.OcrInput) | OCR की सटीकता बढ़ाने के लिए इमेज प्रोसेसिंग का उपयोग करें। |
| [Save(OcrInput images, String folderPath)](#Save-com.aspose.ocr.OcrInput-java.lang.String) | OCR की सटीकता बढ़ाने के लिए इमेज प्रोसेसिंग का उपयोग करें। |

### ImageProcessing() {#ImageProcessing}
```
public ImageProcessing()
```


### Render(OcrInput images) {#Render-com.aspose.ocr.OcrInput}
```
public static OcrInput Render(OcrInput images)
```


OCR की सटीकता बढ़ाने के लिए इमेज प्रोसेसिंग का उपयोग करें। एक फ़िल्टरों की सूची बनाएं जो इनपुट इमेज पर आपके द्वारा निर्दिष्ट क्रम में लागू होगी। फ़िल्टर बनाने का उदाहरण: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); आपको सभी की आवश्यकता नहीं है। केवल वही सेट करें जिसकी आपको ज़रूरत है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | विभिन्न छवियों को शामिल करने वाला OcrInput ऑब्जेक्ट @see \#OcrInput. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput in Image field.
### Save(OcrInput images, String folderPath) {#Save-com.aspose.ocr.OcrInput-java.lang.String}
```
public static OcrInput Save(OcrInput images, String folderPath)
```


OCR की सटीकता बढ़ाने के लिए इमेज प्रोसेसिंग का उपयोग करें। एक फ़िल्टरों की सूची बनाएं जो इनपुट इमेज पर आपके द्वारा निर्दिष्ट क्रम में लागू होगी। फ़िल्टर बनाने का उदाहरण: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); आपको सभी की आवश्यकता नहीं है। केवल वही सेट करें जिसकी आपको ज़रूरत है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | विभिन्न छवियों को शामिल करने वाला OcrInput ऑब्जेक्ट @see \#OcrInput. |
| folderPath | java.lang.String | प्रसंस्कृत छवियों को सहेजने के लिए छवि नामों के बिना पथ। |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput.
