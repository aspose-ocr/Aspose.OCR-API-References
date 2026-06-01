---
title: "OcrInput"
second_title: "Aspose.OCR जावा के लिए API संदर्भ"
description: "छवियों से पाठ पहचानने के लिए मुख्य क्लास"
type: docs
weight: 20
url: /hi/java/com.aspose.ocr/ocrinput/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class OcrInput implements Iterable<ImageData>
```

छवियों से टेक्स्ट पहचानने के लिए मुख्य क्लास।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [OcrInput(InputType type, PreprocessingFilter filters)](#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter) | कंटेनर बनाने और छवियों/दस्तावेज़ों तथा आगे की प्रसंस्करण/पहचान के लिए फ़िल्टर के प्रकार को सेट करने के लिए कन्स्ट्रक्टर। |
| [OcrInput(InputType type)](#OcrInput-com.aspose.ocr.InputType) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [add(int[] pixels, int width, int height, int bitsPerPixel)](#add-int---int-int-int) | डिकोडेड छवि को पहचान/प्रसंस्करण की सूची में जोड़ें। |
| [add(BufferedImage image)](#add-java.awt.image.BufferedImage) | पहचान/प्रसंस्करण के लिए छवि शामिल करने वाले BufferedImage को जोड़ें। |
| [add(BufferedImage image, int startPage, int pagesCount)](#add-java.awt.image.BufferedImage-int-int) | पहचान/प्रसंस्करण के लिए मल्टीपेज छवि शामिल करने वाले BufferedImage को जोड़ें। |
| [add(InputStream stream)](#add-java.io.InputStream) | पहचान/प्रसंस्करण के लिए छवि शामिल करने वाले InputStream को जोड़ें। |
| [add(InputStream stream, int startPage, int pagesCount)](#add-java.io.InputStream-int-int) | पहचान/प्रसंस्करण के लिए मल्टीपेज छवि शामिल करने वाले InputStream को जोड़ें। |
| [add(String fullPath)](#add-java.lang.String) | पहचान/प्रसंस्करण के लिए छवि शामिल करने वाले पाथ या URI को जोड़ें। |
| [add(String fullPath, int startPage, int pagesCount)](#add-java.lang.String-int-int) | पहचान/प्रसंस्करण के लिए मल्टीपेज छवियों/दस्तावेज़ों को जोड़ें। |
| [addBase64(String base64)](#addBase64-java.lang.String) | पहचान/प्रसंस्करण के लिए छवि शामिल करने वाली base64 स्ट्रिंग को जोड़ें। |
| [clear()](#clear) | प्रसंस्करण/पहचान के लिए आइटम की संख्या को 0 सेट करें। |
| [clearFilters()](#clearFilters) | सभी फ़िल्टर हटाएँ। |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [get(int index)](#get-int) | प्रसंस्कृत / पहचाने गए चित्र के बारे में जानकारी लौटाता है। |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [iterator()](#iterator) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [replaceFilters(PreprocessingFilter filters)](#replaceFilters-com.aspose.ocr.PreprocessingFilter) | पुराने फ़िल्टर हटाएँ और नए सेट करें। |
| [size()](#size) | प्रसंस्करण / पहचान के लिए वस्तुओं की संख्या। |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OcrInput(InputType type, PreprocessingFilter filters) {#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter}
```
public OcrInput(InputType type, PreprocessingFilter filters)
```


कंटेनर बनाने और छवियों/दस्तावेज़ों तथा आगे की प्रसंस्करण/पहचान के लिए फ़िल्टर के प्रकार को सेट करने के लिए कन्स्ट्रक्टर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) | छवियों/दस्तावेज़ प्रकार को सेट करें जो कंटेनर में जोड़े जाएंगे। |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | सेट किए गए प्रसंस्करण फ़िल्टर आगे के प्रसंस्करण या पहचान पर लागू होंगे। |

### OcrInput(InputType type) {#OcrInput-com.aspose.ocr.InputType}
```
public OcrInput(InputType type)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) |  |

### add(int[] pixels, int width, int height, int bitsPerPixel) {#add-int---int-int-int}
```
public void add(int[] pixels, int width, int height, int bitsPerPixel)
```


पहचान / प्रसंस्करण के लिए डिकोडेड चित्र को सूची में जोड़ें। चित्र का प्रकार कंस्ट्रक्टर में निर्दिष्ट प्रकार (SingleImage) के अनुरूप होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पिक्सेल | int[] | पिक्सेल को 32-बिट पूर्णांक मानों (rgb) के रूप में दर्शाया जाता है। |
| चौड़ाई | int | चित्र की चौड़ाई। |
| ऊँचाई | int | चित्र की ऊँचाई। |
| bitsPerPixel | int | 1-32 बिट्स का समर्थन करता है। |

### add(BufferedImage image) {#add-java.awt.image.BufferedImage}
```
public void add(BufferedImage image)
```


पहचान / प्रसंस्करण के लिए छवि वाले BufferedImage को जोड़ें। छवि का प्रकार कंस्ट्रक्टर में निर्दिष्ट प्रकार के अनुरूप होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| छवि | java.awt.image.BufferedImage | छवि या दस्तावेज़ वाले BufferedImage। |

### add(BufferedImage image, int startPage, int pagesCount) {#add-java.awt.image.BufferedImage-int-int}
```
public void add(BufferedImage image, int startPage, int pagesCount)
```


पहचान / प्रसंस्करण के लिए बहुपृष्ठीय छवि वाले BufferedImage को जोड़ें। छवि का प्रकार कंस्ट्रक्टर में निर्दिष्ट प्रकार के अनुरूप होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| छवि | java.awt.image.BufferedImage | बहुपृष्ठीय दस्तावेज़ वाले BufferedImage। |
| startPage | int | प्रसंस्करण / पहचान के लिए पहला पृष्ठ/छवि। दस्तावेज़ों के लिए उपयोग करें। |
| pagesCount | int | प्रसंस्करण / पहचान के लिए पृष्ठों/छवियों की कुल संख्या। दस्तावेज़ों के लिए उपयोग करें। डिफ़ॉल्ट = सभी। |

### add(InputStream stream) {#add-java.io.InputStream}
```
public void add(InputStream stream)
```


पहचान / प्रसंस्करण के लिए छवि वाले InputStream को जोड़ें। छवि का प्रकार कंस्ट्रक्टर में निर्दिष्ट प्रकार के अनुरूप होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | छवि या दस्तावेज़ को समाहित करने वाला InputStream। |

### add(InputStream stream, int startPage, int pagesCount) {#add-java.io.InputStream-int-int}
```
public void add(InputStream stream, int startPage, int pagesCount)
```


पहचान / प्रसंस्करण के लिए बहुपृष्ठीय छवि को समाहित करने वाला InputStream जोड़ें। छवि का प्रकार कंस्ट्रक्टर में निर्दिष्ट प्रकार के अनुरूप होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | बहुपृष्ठीय दस्तावेज़ को समाहित करने वाला InputStream। |
| startPage | int | प्रसंस्करण / पहचान के लिए पहला पृष्ठ/छवि। दस्तावेज़ों के लिए उपयोग करें। |
| pagesCount | int | प्रसंस्करण / पहचान के लिए पृष्ठों/छवियों की कुल संख्या। दस्तावेज़ों के लिए उपयोग करें। डिफ़ॉल्ट = सभी। |

### add(String fullPath) {#add-java.lang.String}
```
public void add(String fullPath)
```


पहचान / प्रसंस्करण के लिए छवि को समाहित करने वाला पथ या URI जोड़ें। छवि का प्रकार कंस्ट्रक्टर में निर्दिष्ट प्रकार के अनुरूप होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullPath | java.lang.String | छवि/दस्तावेज़/फ़ोल्डर/आर्काइव का पथ। |

### add(String fullPath, int startPage, int pagesCount) {#add-java.lang.String-int-int}
```
public void add(String fullPath, int startPage, int pagesCount)
```


पहचान / प्रसंस्करण के लिए बहुपृष्ठीय छवियों / दस्तावेज़ों को जोड़ें। छवि का प्रकार कंस्ट्रक्टर में निर्दिष्ट प्रकार के अनुरूप होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullPath | java.lang.String | छवि/दस्तावेज़/फ़ोल्डर/आर्काइव का पथ। |
| startPage | int | प्रसंस्करण / पहचान के लिए पहला पृष्ठ/छवि। दस्तावेज़, ज़िप, फ़ोल्डर के लिए उपयोग करें। |
| pagesCount | int | प्रसंस्करण / पहचान के लिए पृष्ठों/छवियों की कुल संख्या। दस्तावेज़, ज़िप, फ़ोल्डर के लिए उपयोग करें। डिफ़ॉल्ट = सभी। |

### addBase64(String base64) {#addBase64-java.lang.String}
```
public void addBase64(String base64)
```


पहचान / प्रसंस्करण के लिए छवि को समाहित करने वाला base64 स्ट्रिंग जोड़ें। छवि का प्रकार कंस्ट्रक्टर में निर्दिष्ट प्रकार के अनुरूप होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| base64 | java.lang.String | एकल छवि वाला Base64 स्ट्रिंग। |

### clear() {#clear}
```
public void clear()
```


प्रसंस्करण / पहचान के लिए आइटम्स की संख्या 0 सेट करें। संग्रह को साफ़ करें।

### clearFilters() {#clearFilters}
```
public void clearFilters()
```


सभी फ़िल्टर हटाएँ।

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
### get(int index) {#get-int}
```
public ImageData get(int index)
```


प्रसंस्कृत / पहचाने गए चित्र के बारे में जानकारी लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | सूची में छवि की स्थिति। |

**Returns:**
[ImageData](../../com.aspose.ocr/imagedata/) - The object of @see [ImageData](../../com.aspose.ocr/imagedata/)
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
### iterator() {#iterator}
```
public Iterator<ImageData> iterator()
```




**Returns:**
java.util.Iterator<com.aspose.ocr.ImageData>
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




### replaceFilters(PreprocessingFilter filters) {#replaceFilters-com.aspose.ocr.PreprocessingFilter}
```
public void replaceFilters(PreprocessingFilter filters)
```


पुराने फ़िल्टर हटाएँ और नए सेट करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | आगे के प्रसंस्करण या पहचान के लिए प्रोसेसिंग फ़िल्टर लागू किए जाएंगे। |

### size() {#size}
```
public int size()
```


प्रसंस्करण / पहचान के लिए वस्तुओं की संख्या।

**Returns:**
int - आइटम्स की संख्या।
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

