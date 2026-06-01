---
title: "OcrOutput"
second_title: "Aspose.OCR जावा के लिए API संदर्भ"
description: 
type: docs
weight: 21
url: /hi/java/com.aspose.ocr/ocroutput/
---

**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList
```
public class OcrOutput extends ArrayList<RecognitionResult>
```
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [OcrOutput()](#OcrOutput) | OcrOutput क्लास का नया इंस्टेंस एक खाली संग्रह के साथ प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |

| [getTableData()](#getTableData) | सभी पहचाने गए पृष्ठों से निकाले गए संरचित तालिका डेटा को लौटाता है। |
| [save(OutputStream stream)](#save-java.io.OutputStream) | सभी पहचान परिणामों को निर्दिष्ट प्रारूप में मेमोरी स्ट्रीम में सहेजें। |
| [save(OutputStream stream, Format saveFormat)](#save-java.io.OutputStream-com.aspose.ocr.models.Format) | सभी पहचान परिणामों को निर्दिष्ट प्रारूप में मेमोरी स्ट्रीम में सहेजें। |
| [save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | सभी पहचान परिणामों को निर्दिष्ट प्रारूप में मेमोरी स्ट्रीम में सहेजें। |
| [save(String fullFileName)](#save-java.lang.String) | सभी पहचान परिणाम को एक फ़ाइल में सहेजें। |
| [save(String fullFileName, Format saveFormat)](#save-java.lang.String-com.aspose.ocr.models.Format) | सभी पहचान परिणाम को एक फ़ाइल में सहेजें। |
| [save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | सभी पहचान परिणाम को एक फ़ाइल में सहेजें। |
| [savePdf(OutputStream stream)](#savePdf-java.io.OutputStream) | सभी पहचान परिणामों को इन‑मेमोरी सर्चेबल PDF दस्तावेज़ में सहेजें, मूल छवियों को पृष्ठभूमि के रूप में एम्बेड करें। |
| [savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | सभी पहचान परिणामों को इन‑मेमोरी सर्चेबल PDF दस्तावेज़ में सहेजें, मूल छवियों को पृष्ठभूमि के रूप में एम्बेड करें। |
| [savePdf(String fullFileName)](#savePdf-java.lang.String) | सभी पहचान परिणामों को सर्चेबल PDF फ़ाइल में सहेजें, जहाँ मूल छवियों को पृष्ठभूमि के रूप में सेट किया गया है। |
| [savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | सभी पहचान परिणामों को सर्चेबल PDF फ़ाइल में सहेजें, जहाँ मूल छवियों को पृष्ठभूमि के रूप में सेट किया गया है। |

### getTableData() {#getTableData}
```
public OCRTable getTableData()
```


सभी पहचाने गए पृष्ठों से निकाले गए संरचित तालिका डेटा को लौटाता है।

प्रत्येक पृष्ठ में पंक्तियाँ होती हैं, और प्रत्येक पंक्ति में मान्यता प्राप्त पाठ और वैकल्पिक स्थिति जानकारी वाले सेल होते हैं।

**Returns:**
[OCRTable](../../com.aspose.ocr.models/ocrtable/) - an [OCRTable](../../com.aspose.ocr.models/ocrtable/) structure representing all tables in the document


### save(OutputStream stream) {#save-java.io.OutputStream}
```
public void save(OutputStream stream)
```


सभी पहचान परिणामों को निर्दिष्ट प्रारूप में मेमोरी स्ट्रीम में सहेजें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | चयनित प्रारूप में पहचान परिणाम को सहेजने के लिए OutputStream। |

### save(OutputStream stream, Format saveFormat) {#save-java.io.OutputStream-com.aspose.ocr.models.Format}
```
public void save(OutputStream stream, Format saveFormat)
```


सभी पहचान परिणामों को निर्दिष्ट प्रारूप में मेमोरी स्ट्रीम में सहेजें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | चयनित प्रारूप में पहचान परिणाम को सहेजने के लिए OutputStream। |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | दस्तावेज़ फ़ॉर्मेट (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub)। |

### save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


सभी पहचान परिणामों को निर्दिष्ट प्रारूप में मेमोरी स्ट्रीम में सहेजें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | चयनित प्रारूप में पहचान परिणाम को सहेजने के लिए OutputStream। |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | दस्तावेज़ फ़ॉर्मेट (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub)। |
| embeddedFontPath | java.lang.String | वैकल्पिक। उपयोगकर्ता फ़ॉन्ट का पूर्ण पथ। |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | पृष्ठभूमि छवियों की गुणवत्ता कम करके PDF फ़ाइल का आकार घटाएँ। डिफ़ॉल्ट रूप में, मूल छवि गुणवत्ता बरकरार रहती है। |

### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


सभी पहचान परिणाम को एक फ़ाइल में सहेजें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullFileName | java.lang.String | चयनित प्रारूप में पहचान परिणाम सहेजने के लिए पथ सहित फ़ाइलनाम। |

### save(String fullFileName, Format saveFormat) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format saveFormat)
```


सभी पहचान परिणाम को एक फ़ाइल में सहेजें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullFileName | java.lang.String | चयनित प्रारूप में पहचान परिणाम सहेजने के लिए पथ सहित फ़ाइलनाम। |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | दस्तावेज़ फ़ॉर्मेट (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub)। |

### save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


सभी पहचान परिणाम को एक फ़ाइल में सहेजें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullFileName | java.lang.String | चयनित प्रारूप में पहचान परिणाम सहेजने के लिए पथ सहित फ़ाइलनाम। |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | दस्तावेज़ फ़ॉर्मेट (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub)। |
| embeddedFontPath | java.lang.String | वैकल्पिक। उपयोगकर्ता फ़ॉन्ट का पूर्ण पथ। |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | पृष्ठभूमि छवियों की गुणवत्ता कम करके PDF फ़ाइल का आकार घटाएँ। डिफ़ॉल्ट रूप में, मूल छवि गुणवत्ता बरकरार रहती है। |

### savePdf(OutputStream stream) {#savePdf-java.io.OutputStream}
```
public void savePdf(OutputStream stream)
```


सभी पहचान परिणामों को इन‑मेमोरी सर्चेबल PDF दस्तावेज़ में सहेजें, मूल छवियों को पृष्ठभूमि के रूप में एम्बेड करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | चयनित प्रारूप में पहचान परिणाम को सहेजने के लिए OutputStream। |

### savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


सभी पहचान परिणामों को इन‑मेमोरी सर्चेबल PDF दस्तावेज़ में सहेजें, मूल छवियों को पृष्ठभूमि के रूप में एम्बेड करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | चयनित प्रारूप में पहचान परिणाम को सहेजने के लिए OutputStream। |
| embeddedFontPath | java.lang.String | वैकल्पिक। उपयोगकर्ता फ़ॉन्ट का पूर्ण पथ। |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | पृष्ठभूमि छवियों की गुणवत्ता कम करके PDF फ़ाइल का आकार घटाएँ। डिफ़ॉल्ट रूप में, मूल छवि गुणवत्ता बरकरार रहती है। |

### savePdf(String fullFileName) {#savePdf-java.lang.String}
```
public void savePdf(String fullFileName)
```


सभी पहचान परिणामों को सर्चेबल PDF फ़ाइल में सहेजें, जहाँ मूल छवियों को पृष्ठभूमि के रूप में सेट किया गया है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullFileName | java.lang.String | चयनित प्रारूप में पहचान परिणाम सहेजने के लिए पथ सहित फ़ाइलनाम। |

### savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


सभी पहचान परिणामों को सर्चेबल PDF फ़ाइल में सहेजें, जहाँ मूल छवियों को पृष्ठभूमि के रूप में सेट किया गया है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fullFileName | java.lang.String | चयनित प्रारूप में पहचान परिणाम सहेजने के लिए पथ सहित फ़ाइलनाम। |
| embeddedFontPath | java.lang.String | वैकल्पिक। उपयोगकर्ता फ़ॉन्ट का पूर्ण पथ। |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | पृष्ठभूमि छवियों की गुणवत्ता कम करके PDF फ़ाइल का आकार घटाएँ। डिफ़ॉल्ट रूप में, मूल छवि गुणवत्ता बरकरार रहती है। |

### size() {#size}
```
public int size()
```




**Returns:**
int
