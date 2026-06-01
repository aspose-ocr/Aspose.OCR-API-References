---
title: "PreprocessingFilter"
second_title: "Aspose.OCR जावा के लिए API संदर्भ"
description: "छवि प्रसंस्करण कमांड्स के लिए बेस क्लास"
type: docs
weight: 24
url: /hi/java/com.aspose.ocr/preprocessingfilter/
---

**Inheritance:**
java.lang.Object
```
public class PreprocessingFilter
```

छवि प्रसंस्करण कमांड के लिए बेस क्लास।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [PreprocessingFilter()](#PreprocessingFilter) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [Empty](#Empty) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [AutoDenoising()](#AutoDenoising) | छवि को सुधारने के लिए अतिरिक्त न्यूरल नेटवर्क के उपयोग को सक्षम करता है - शोर को कम करता है। |
| [AutoDenoising(Rectangle area)](#AutoDenoising-java.awt.Rectangle) | छवि के भाग को सुधारने के लिए अतिरिक्त न्यूरल नेटवर्क के उपयोग को सक्षम करता है - शोर को कम करता है। |
| [AutoDewarping()](#AutoDewarping) | छवि में ज्यामितीय विकृतियों को स्वचालित रूप से सुधारता है। |
| [AutoSkew()](#AutoSkew) | छवि के स्वचालित विकृति सुधार को सक्षम करता है। |
| [AutoSkew(Rectangle area)](#AutoSkew-java.awt.Rectangle) | छवि के भाग के स्वचालित विकृति सुधार को सक्षम करता है। |
| [Binarize()](#Binarize) | एक छवि को काली-श्वेत छवि में परिवर्तित करता है। |
| [Binarize(Rectangle area)](#Binarize-java.awt.Rectangle) | छवि के भाग को काली-श्वेत छवि में परिवर्तित करता है। |
| [BinarizeAndDilate()](#BinarizeAndDilate) | डाइलेशन छवि में वस्तुओं की सीमाओं में पिक्सेल जोड़ता है। |
| [BinarizeAndDilate(Rectangle area)](#BinarizeAndDilate-java.awt.Rectangle) | डाइलेशन छवि के भाग में वस्तुओं की सीमाओं में पिक्सेल जोड़ता है। |
| [ContrastCorrection()](#ContrastCorrection) | कॉन्ट्रास्ट सुधार फ़िल्टर। |
| [ContrastCorrection(Rectangle area)](#ContrastCorrection-java.awt.Rectangle) | छवि के भाग के लिए कॉन्ट्रास्ट सुधार फ़िल्टर। |
| [Invert()](#Invert) | दस्तावेज़ छवि में रंगों को स्वचालित रूप से उलटता है। |
| [Invert(Rectangle area)](#Invert-java.awt.Rectangle) | छवि के भाग में रंगों को स्वचालित रूप से उलटता है। |
| [Median()](#Median) | मीडियन फ़िल्टर छवि के प्रत्येक तत्व के माध्यम से चलता है और प्रत्येक पिक्सेल को उसके पड़ोसी पिक्सेल के मीडियन से बदल देता है। |
| [Median(Rectangle area)](#Median-java.awt.Rectangle) | मीडियन फ़िल्टर छवि के भाग के प्रत्येक तत्व के माध्यम से चलता है और प्रत्येक पिक्सेल को उसके पड़ोसी पिक्सेलों के मीडियन से बदल देता है। |
| [Resize(int width, int height)](#Resize-int-int) | छवि को पुनः स्केल करें - छवि रिज़ॉल्यूशन को अपस्केल या डाउनस्केल करें। |
| [Resize(int width, int height, InterpolationFilterType type)](#Resize-int-int-com.aspose.ocr.InterpolationFilterType) | छवि को पुनः स्केल करें - अपस्केल या डाउनस्केल छवि रिज़ॉल्यूशन। |
| [Rotate(float angle)](#Rotate-float) | मूल छवि को घुमाएँ। |
| [Rotate(float angle, Rectangle area)](#Rotate-float-java.awt.Rectangle) | छवि के भाग को घुमाएँ। |
| [Scale(float ratio)](#Scale-float) | छवि को पुनः स्केल करें - छवि रिज़ॉल्यूशन को अपस्केल या डाउनस्केल करें। |
| [Scale(float ratio, InterpolationFilterType type)](#Scale-float-com.aspose.ocr.InterpolationFilterType) | छवि को पुनः स्केल करें - छवि रिज़ॉल्यूशन को अपस्केल या डाउनस्केल करें। |
| [Threshold(int value)](#Threshold-int) | मूल छवि की पिक्सेल तीव्रता पर थ्रेशोल्ड मान सेट करके एक बाइनरी छवि बनाएँ। |
| [Threshold(int value, Rectangle area)](#Threshold-int-java.awt.Rectangle) | मूल छवि भाग की पिक्सेल तीव्रता पर थ्रेशोल्ड मान सेट करके बाइनरी छवि भाग बनाएँ। |
| [ToGrayscale()](#ToGrayscale) | एक छवि को ग्रेस्केल छवि में बदलता है। |
| [add(PreprocessingFilter filter)](#add-com.aspose.ocr.PreprocessingFilter) | सभी ऑपरेशनों को आगे चलाने के लिए नई फ़िल्टर को संग्रह में जोड़ें। |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### PreprocessingFilter() {#PreprocessingFilter}
```
public PreprocessingFilter()
```


### Empty {#Empty}
```
public static final PreprocessingFilter Empty
```


### AutoDenoising() {#AutoDenoising}
```
public static PreprocessingFilter AutoDenoising()
```


छवि को सुधारने के लिए अतिरिक्त न्यूरल नेटवर्क के उपयोग को सक्षम करता है - शोर को कम करता है। स्कैन आर्टिफैक्ट, विकृति, धब्बे, फ्लेयर, ग्रेडिएंट और विदेशी तत्वों वाली छवियों के लिए उपयोगी।

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDenoising(Rectangle area) {#AutoDenoising-java.awt.Rectangle}
```
public static PreprocessingFilter AutoDenoising(Rectangle area)
```


छवि के भाग को सुधारने के लिए अतिरिक्त न्यूरल नेटवर्क के उपयोग को सक्षम करता है - शोर को कम करता है। स्कैन आर्टिफैक्ट, विकृति, धब्बे, फ्लेयर, ग्रेडिएंट और विदेशी तत्वों वाली छवियों के लिए उपयोगी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| क्षेत्र | java.awt.Rectangle | पूर्व-प्रसंस्करण के लिए आयत। |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDewarping() {#AutoDewarping}
```
public static PreprocessingFilter AutoDewarping()
```


छवि में ज्यामितीय विकृतियों को स्वचालित रूप से सुधारता है। अत्यधिक संसाधन-गहन!

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDewarpingFilter object.
### AutoSkew() {#AutoSkew}
```
public static PreprocessingFilter AutoSkew()
```


छवि के स्वचालित विकृति सुधार को सक्षम करता है।

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### AutoSkew(Rectangle area) {#AutoSkew-java.awt.Rectangle}
```
public static PreprocessingFilter AutoSkew(Rectangle area)
```


छवि के भाग के स्वचालित विकृति सुधार को सक्षम करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| क्षेत्र | java.awt.Rectangle | पूर्व-प्रसंस्करण के लिए आयत। |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### Binarize() {#Binarize}
```
public static PreprocessingFilter Binarize()
```


एक छवि को काली-और-सफ़ेद छवि में बदलता है। बाइनरी छवियाँ वे छवियाँ हैं जिनके पिक्सेल केवल दो संभावित तीव्रता मान रखते हैं। इन्हें सामान्यतः काली और सफ़ेद के रूप में प्रदर्शित किया जाता है। संख्यात्मक रूप से, ये दो मान अक्सर काली के लिए 0 और सफ़ेद के लिए 255 होते हैं। बाइनरी छवियाँ स्वचालित थ्रेशोल्डिंग द्वारा उत्पन्न की जाती हैं।

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Binarize(Rectangle area) {#Binarize-java.awt.Rectangle}
```
public static PreprocessingFilter Binarize(Rectangle area)
```


छवि के भाग को काली-और-सफ़ेद छवि में बदलता है। बाइनरी छवियाँ वे छवियाँ हैं जिनके पिक्सेल केवल दो संभावित तीव्रता मान रखते हैं। इन्हें सामान्यतः काली और सफ़ेद के रूप में प्रदर्शित किया जाता है। संख्यात्मक रूप से, ये दो मान अक्सर काली के लिए 0 और सफ़ेद के लिए 255 होते हैं। बाइनरी छवियाँ स्वचालित थ्रेशोल्डिंग द्वारा उत्पन्न की जाती हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| क्षेत्र | java.awt.Rectangle | पूर्व-प्रसंस्करण के लिए आयत। |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### BinarizeAndDilate() {#BinarizeAndDilate}
```
public static PreprocessingFilter BinarizeAndDilate()
```


डाइलेशन छवि में वस्तुओं की सीमाओं में पिक्सेल जोड़ता है।

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### BinarizeAndDilate(Rectangle area) {#BinarizeAndDilate-java.awt.Rectangle}
```
public static PreprocessingFilter BinarizeAndDilate(Rectangle area)
```


डाइलेशन छवि के भाग में वस्तुओं की सीमाओं में पिक्सेल जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| क्षेत्र | java.awt.Rectangle | पूर्व-प्रसंस्करण के लिए आयत। |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### ContrastCorrection() {#ContrastCorrection}
```
public static PreprocessingFilter ContrastCorrection()
```


कॉन्ट्रास्ट सुधार फ़िल्टर।

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### ContrastCorrection(Rectangle area) {#ContrastCorrection-java.awt.Rectangle}
```
public static PreprocessingFilter ContrastCorrection(Rectangle area)
```


छवि के भाग के लिए कॉन्ट्रास्ट सुधार फ़िल्टर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| क्षेत्र | java.awt.Rectangle | पूर्व-प्रसंस्करण के लिए आयत। |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### Invert() {#Invert}
```
public static PreprocessingFilter Invert()
```


दस्तावेज़ छवि में रंगों को स्वचालित रूप से उलटता है।

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Invert(Rectangle area) {#Invert-java.awt.Rectangle}
```
public static PreprocessingFilter Invert(Rectangle area)
```


छवि के भाग में रंगों को स्वचालित रूप से उलटता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| क्षेत्र | java.awt.Rectangle | पूर्व-प्रसंस्करण के लिए आयत। |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Median() {#Median}
```
public static PreprocessingFilter Median()
```


मीडियन फ़िल्टर छवि के प्रत्येक तत्व के माध्यम से चलता है और प्रत्येक पिक्सेल को उसके पड़ोसी पिक्सेल के मीडियन से बदल देता है।

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Median(Rectangle area) {#Median-java.awt.Rectangle}
```
public static PreprocessingFilter Median(Rectangle area)
```


मीडियन फ़िल्टर छवि के भाग के प्रत्येक तत्व के माध्यम से चलता है और प्रत्येक पिक्सेल को उसके पड़ोसी पिक्सेलों के मीडियन से बदल देता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| क्षेत्र | java.awt.Rectangle | पूर्व-प्रसंस्करण के लिए आयत। |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Resize(int width, int height) {#Resize-int-int}
```
public static PreprocessingFilter Resize(int width, int height)
```


छवि को पुनः स्केल करें - अपस्केल या डाउनस्केल छवि रिज़ॉल्यूशन। InterpolationFilterType = bilinear या nearest neighbor @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| चौड़ाई | int | छवि की नई चौड़ाई। |
| ऊँचाई | int | छवि की नई ऊँचाई। |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Resize(int width, int height, InterpolationFilterType type) {#Resize-int-int-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Resize(int width, int height, InterpolationFilterType type)
```


छवि को पुनः स्केल करें - अपस्केल या डाउनस्केल छवि रिज़ॉल्यूशन।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| चौड़ाई | int | छवि की नई चौड़ाई। |
| ऊँचाई | int | छवि की नई ऊँचाई। |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Rotate(float angle) {#Rotate-float}
```
public static PreprocessingFilter Rotate(float angle)
```


मूल छवि को घुमाएँ।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| कोण | float | घूर्णन का कोण। मान -360 से 360 तक। |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Rotate(float angle, Rectangle area) {#Rotate-float-java.awt.Rectangle}
```
public static PreprocessingFilter Rotate(float angle, Rectangle area)
```


छवि के भाग को घुमाएँ।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| कोण | float | घूर्णन का कोण। मान -360 से 360 तक। |
| क्षेत्र | java.awt.Rectangle | पूर्व-प्रसंस्करण के लिए आयत। |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Scale(float ratio) {#Scale-float}
```
public static PreprocessingFilter Scale(float ratio)
```


छवि का पुनःआकार - छवि रिज़ॉल्यूशन को अपस्केल या डाउनस्केल करें। InterpolationFilterType डिफ़ॉल्ट बाइलिनियर या निकटतम पड़ोसी @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| अनुपात | float | स्केलिंग कारक। संकुचित करने के लिए अनुशंसित मान 0.1 से 1 तक। बढ़ाने के लिए 1 से 10 तक। |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Scale(float ratio, InterpolationFilterType type) {#Scale-float-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Scale(float ratio, InterpolationFilterType type)
```


छवि को पुनः स्केल करें - छवि रिज़ॉल्यूशन को अपस्केल या डाउनस्केल करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| अनुपात | float | स्केलिंग कारक। संकुचित करने के लिए अनुशंसित मान 0.1 से 1 तक। बढ़ाने के लिए 1 से 10 तक। |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Threshold(int value) {#Threshold-int}
```
public static PreprocessingFilter Threshold(int value)
```


मूल छवि की पिक्सेल तीव्रता पर थ्रेशोल्ड मान सेट करके एक बाइनरी छवि बनाएँ।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | अधिकतम मान। |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Threshold(int value, Rectangle area) {#Threshold-int-java.awt.Rectangle}
```
public static PreprocessingFilter Threshold(int value, Rectangle area)
```


मूल छवि भाग की पिक्सेल तीव्रता पर थ्रेशोल्ड मान सेट करके बाइनरी छवि भाग बनाएँ।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | अधिकतम मान। |
| क्षेत्र | java.awt.Rectangle | पूर्व-प्रसंस्करण के लिए आयत। |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### ToGrayscale() {#ToGrayscale}
```
public static PreprocessingFilter ToGrayscale()
```


एक छवि को ग्रेस्केल छवि में परिवर्तित करता है। ग्रेस्केल छवि में 256 स्तर की प्रकाशता होती है (0 से 255)।

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - GrayscaleFilter object.
### add(PreprocessingFilter filter) {#add-com.aspose.ocr.PreprocessingFilter}
```
public void add(PreprocessingFilter filter)
```


सभी ऑपरेशनों को आगे चलाने के लिए नया फ़िल्टर संग्रह में जोड़ें। संग्रह में निरंतरता महत्वपूर्ण है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filter | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | फ़िल्टर सूची में जोड़ने के लिए नया ऑपरेशन। |

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait}
```
public final void wait()
```




### wait(long arg0) {#wait-long}
```
public final native void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

