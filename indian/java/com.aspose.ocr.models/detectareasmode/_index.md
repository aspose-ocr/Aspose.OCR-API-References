---
title: "DetectAreasMode"
second_title: "Aspose.OCR जावा के लिए API संदर्भ"
description: 
type: docs
weight: 28
url: /hi/java/com.aspose.ocr.models/detectareasmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetectAreasMode extends Enum<DetectAreasMode>
```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [CURVED_TEXT](#CURVED-TEXT) | छवि में टेक्स्ट की वक्र रेखाओं को स्वतः सीधा करता है, पहचान की सटीकता में सुधार करता है और अधिक टेक्स्ट को पुनः प्राप्त और निकाला जा सकता है। |
| [FORMULA](#FORMULA) | गणितीय सूत्रों वाले सभी ब्लॉकों का पता लगाता है। |
| [LEAN](#LEAN) | जटिल लेआउट समर्थन को छोड़कर गति को प्राथमिकता देता है और संसाधन खपत को कम करता है। |
| [MULTICOLUMN](#MULTICOLUMN) | कॉलम में स्वरूपित बड़े टेक्स्ट ब्लॉकों का पता लगाता है। |
| [TABLE](#TABLE) | छवि में तालिका संरचनाओं का पता लगाता है और व्यक्तिगत कोशिकाओं से टेक्स्ट निकालता है। |
| [UNIVERSAL](#UNIVERSAL) | छवि में सभी टेक्स्ट ब्लॉकों का पता लगाता है, जिसमें फोटो पर बिखरा और अनियमित टेक्स्ट भी शामिल है। |

### CURVED_TEXT {#CURVED-TEXT}
```
public static final DetectAreasMode CURVED_TEXT
```


छवि में टेक्स्ट की वक्र रेखाओं को स्वतः सीधा करता है, पहचान की सटीकता में सुधार करता है और अधिक टेक्स्ट को पुनः प्राप्त और निकाला जा सकता है। इसके लिए पर्याप्त प्रोसेसिंग पावर और RAM की आवश्यकता होती है।

### FORMULA {#FORMULA}
```
public static final DetectAreasMode FORMULA
```


गणितीय सूत्रों वाले सभी ब्लॉकों का पता लगाता है।

### LEAN {#LEAN}
```
public static final DetectAreasMode LEAN
```


जटिल लेआउट समर्थन को छोड़कर गति को प्राथमिकता देता है और संसाधन खपत को कम करता है। यह केवल सरल छवियों के लिए उपयुक्त है जिनमें कुछ पंक्तियों का टेक्स्ट हो और बिना चित्रण या स्वरूपण के।

### MULTICOLUMN {#MULTICOLUMN}
```
public static final DetectAreasMode MULTICOLUMN
```


कॉलम में स्वरूपित बड़े टेक्स्ट ब्लॉकों का पता लगाता है। पुस्तक पृष्ठों, लेखों या अनुबंधों जैसे बहु-कॉलम लेआउट के लिए सबसे अच्छा विकल्प।

### TABLE {#TABLE}
```
public static final DetectAreasMode TABLE
```


छवि में तालिका संरचनाओं का पता लगाता है और व्यक्तिगत कोशिकाओं से टेक्स्ट निकालता है। स्कैन किए गए स्प्रेडशीट, रिपोर्ट और अन्य तालिका-आधारित दस्तावेज़ों के लिए अनुशंसित।

### UNIVERSAL {#UNIVERSAL}
```
public static final DetectAreasMode UNIVERSAL
```


छवि में सभी टेक्स्ट ब्लॉकों का पता लगाता है, जिसमें फोटो पर बिखरा और अनियमित टेक्स्ट भी शामिल है। तालिकाओं और बहु-कॉलम लेआउट को छोड़कर अधिकांश छवियों के लिए एक बहुमुखी विकल्प।

