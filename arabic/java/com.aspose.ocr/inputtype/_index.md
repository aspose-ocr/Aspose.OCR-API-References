---
title: "InputType"
second_title: "مرجع Aspose.OCR لـ Java API"
description: "أنواع الصور/ المستندات للمعالجة / التعرف"
type: docs
weight: 38
url: /ar/java/com.aspose.ocr/inputtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum InputType extends Enum<InputType>
```

أنواع الصور/ المستندات للمعالجة / التعرف.
## الحقول

| الحقل | الوصف |
| --- | --- |
| [Base64](#Base64) | سلسلة base64 مع الصورة أو المسار إلى ملف .txt الذي يحتوي على محتوى base64. |
| [Directory](#Directory) | المسار إلى الدليل. |
| [PDF](#PDF) | مستند PDF ممسوح ضوئيًا من ملف أو من InputStream. |
| [SingleImage](#SingleImage) | يدعم GIF، PNG، JPEG، BMP، TIFF، JFIF، InputStream، BufferedImage. |
| [TIFF](#TIFF) | مستند TIFF متعدد الصفحات، TIF من ملف أو من InputStream. |
| [URL](#URL) | رابط على الصورة. |
| [Zip](#Zip) | الاسم الكامل لأرشيف ZIP. |

### Base64 {#Base64}
```
public static final InputType Base64
```


سلسلة base64 مع الصورة أو المسار إلى ملف .txt الذي يحتوي على محتوى base64. يدعم GIF، PNG، JPEG، BMP، TIFF.

### Directory {#Directory}
```
public static final InputType Directory
```


المسار إلى الدليل. لا يتم دعم الأرشيفات والمجلدات المتداخلة. يدعم GIF، PNG، JPEG، BMP، TIFF. العدد الافتراضي للصور المعالجة هو الكل.

### PDF {#PDF}
```
public static final InputType PDF
```


مستند PDF ممسوح ضوئيًا من ملف أو من InputStream.

### SingleImage {#SingleImage}
```
public static final InputType SingleImage
```


يدعم GIF، PNG، JPEG، BMP، TIFF، JFIF، InputStream، BufferedImage.

### TIFF {#TIFF}
```
public static final InputType TIFF
```


مستند TIFF متعدد الصفحات، TIF من ملف أو من InputStream.

### URL {#URL}
```
public static final InputType URL
```


رابط على الصورة. يدعم GIF، PNG، JPEG، BMP، TIFF.

### Zip {#Zip}
```
public static final InputType Zip
```


الاسم الكامل لأرشيف ZIP. لا يتم دعم الأرشيفات والمجلدات المتداخلة. يدعم GIF، PNG، JPEG، BMP، TIFF، JFIF. العدد الافتراضي للصور المعالجة هو الكل.
