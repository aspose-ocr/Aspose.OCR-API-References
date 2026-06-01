---
title: "InputType"
second_title: "Aspose.OCR जावा के लिए API संदर्भ"
description: "प्रसंस्करण / पहचान के लिए इमेज/दस्तावेज़ के प्रकार"
type: docs
weight: 38
url: /hi/java/com.aspose.ocr/inputtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum InputType extends Enum<InputType>
```

प्रसंस्करण/पहचान के लिए छवि/दस्तावेज़ के प्रकार।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [Base64](#Base64) | छवि के साथ base64 स्ट्रिंग या base64 सामग्री वाली .txt फ़ाइल का पथ। |
| [Directory](#Directory) | डायरेक्टरी का पथ। |
| [PDF](#PDF) | फ़ाइल या InputStream से स्कैन किया गया PDF दस्तावेज़। |
| [SingleImage](#SingleImage) | GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage का समर्थन करता है। |
| [TIFF](#TIFF) | फ़ाइल या InputStream से मल्टीपेज TIFF, TIF दस्तावेज़। |
| [URL](#URL) | छवि पर लिंक। |
| [Zip](#Zip) | ZIP आर्काइव का पूर्ण नाम। |

### Base64 {#Base64}
```
public static final InputType Base64
```


छवि के साथ base64 स्ट्रिंग या base64 सामग्री वाली .txt फ़ाइल का पथ। GIF, PNG, JPEG, BMP, TIFF का समर्थन करता है।

### Directory {#Directory}
```
public static final InputType Directory
```


डायरेक्टरी का पथ। नेस्टेड आर्काइव और फ़ोल्डर समर्थित नहीं हैं। GIF, PNG, JPEG, BMP, TIFF का समर्थन करता है। डिफ़ॉल्ट रूप से सभी प्रसंस्कृत छवियों को शामिल किया जाता है।

### PDF {#PDF}
```
public static final InputType PDF
```


फ़ाइल या InputStream से स्कैन किया गया PDF दस्तावेज़।

### SingleImage {#SingleImage}
```
public static final InputType SingleImage
```


GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage का समर्थन करता है।

### TIFF {#TIFF}
```
public static final InputType TIFF
```


फ़ाइल या InputStream से मल्टीपेज TIFF, TIF दस्तावेज़।

### URL {#URL}
```
public static final InputType URL
```


छवि पर लिंक। GIF, PNG, JPEG, BMP, TIFF का समर्थन करता है।

### Zip {#Zip}
```
public static final InputType Zip
```


ZIP आर्काइव का पूर्ण नाम। नेस्टेड आर्काइव और फ़ोल्डर समर्थित नहीं हैं। GIF, PNG, JPEG, BMP, TIFF, JFIF का समर्थन करता है। डिफ़ॉल्ट रूप से सभी प्रसंस्कृत छवियों को शामिल किया जाता है।
