---
title: "ImageProcessing"
second_title: "Aspose.OCR Python के लिए via .NET API संदर्भ"
description: 
type: docs
weight: 120
url: /hi/python-net/aspose.ocr/imageprocessing/
---

## ImageProcessing class

Aspose OCR लाइब्रेरी के लिए हेल्पर क्लास। छवियों को पूर्व-प्रसंस्करण और सहेजने की अनुमति देता है।

ImageProcessing प्रकार निम्नलिखित सदस्यों को उजागर करता है:
## विधियाँ
| नाम | विवरण |
| :- | :- |
| save(images, folder_path) | OCR की सटीकता सुधारने के लिए इमेज प्रोसेसिंग का उपयोग करें।<br/>            इनपुट इमेज पर लागू होने वाले फ़िल्टरों की सूची बनाएं, जिसे आप निर्दिष्ट क्रम में लागू करेंगे।<br/>            फ़िल्टर बनाने का उदाहरण:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            आपको सभी की आवश्यकता नहीं है। केवल वही सेट करें जिसकी आपको ज़रूरत है। |
| render(images) | OCR की सटीकता सुधारने के लिए इमेज प्रोसेसिंग का उपयोग करें।<br/>            इनपुट इमेज पर लागू होने वाले फ़िल्टरों की सूची बनाएं, जिसे आप निर्दिष्ट क्रम में लागू करेंगे।<br/>            फ़िल्टर बनाने का उदाहरण:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            आपको सभी की आवश्यकता नहीं है। केवल वही सेट करें जिसकी आपको ज़रूरत है। |

### संबंधित देखें

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

