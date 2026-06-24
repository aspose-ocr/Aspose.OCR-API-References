---
title: "رخصة"
second_title: "مرجع Aspose.OCR لـ Java API"
description: "يوفر طرقًا لترخيص المكوّن"
type: docs
weight: 21
url: /ar/java/com.aspose.ocr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

يوفر طرقًا لترخيص المكوّن.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [License()](#License) | يُهيئ نسخة جديدة من هذه الفئة. |
## الدوال

| الدالة | الوصف |
| --- | --- |

| [setLicense(File licenseFile)](#setLicense-java.io.File) | يرخص المكوّن. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream) | يرخص المكوّن. |
| [setLicense(String licenseFilePath)](#setLicense-java.lang.String) | يرخص المكوّن. |
| [isValid()](#isValid--) | تحقق من الرخصة. |
### License() {#License}
```
public License()
```


يُهيئ نسخة جديدة من هذه الفئة.


### setLicense(File licenseFile) {#setLicense-java.io.File}
```
public static void setLicense(File licenseFile)
```


يرخص المكوّن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| licenseFile | java.io.File | تمثيل مسار اسم الملف |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream}
```
public static void setLicense(InputStream stream)
```


يرخص المكوّن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | دفق يحتوي على الرخصة. |

### setLicense(String licenseFilePath) {#setLicense-java.lang.String}
```
public static void setLicense(String licenseFilePath)
```


يرخص المكوّن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| licenseFilePath | java.lang.String | يمكن أن يكون اسم ملف كامل أو قصير. استخدم سلسلة فارغة للتبديل إلى وضع التقييم. |



### isValid() {#isValid--}
```
public static boolean isValid()
```


تحقق من الرخصة.

**Returns:**
boolean - قيمة منطقية تشير إلى صلاحية الرخصة.
