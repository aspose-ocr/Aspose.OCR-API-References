---
title: "OcrInput"
second_title: "مرجع Aspose.OCR لـ Java API"
description: "الفئة الرئيسية للتعرف على النص من الصور"
type: docs
weight: 20
url: /ar/java/com.aspose.ocr/ocrinput/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class OcrInput implements Iterable<ImageData>
```

الفئة الرئيسية للتعرف على النص من الصور.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [OcrInput(InputType type, PreprocessingFilter filters)](#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter) | المُنشئ لإنشاء حاوية وتعيين نوع الصور / المستندات والفلاتر للمعالجة / التعرف اللاحقة. |
| [OcrInput(InputType type)](#OcrInput-com.aspose.ocr.InputType) |  |
## الدوال

| الدالة | الوصف |
| --- | --- |
| [add(int[] pixels, int width, int height, int bitsPerPixel)](#add-int---int-int-int) | أضف الصورة المفكوكة إلى القائمة للتعرف / المعالجة. |
| [add(BufferedImage image)](#add-java.awt.image.BufferedImage) | أضف الـ BufferedImage الذي يحتوي على الصورة للتعرف / المعالجة. |
| [add(BufferedImage image, int startPage, int pagesCount)](#add-java.awt.image.BufferedImage-int-int) | أضف الـ BufferedImage الذي يحتوي على صورة متعددة الصفحات للتعرف / المعالجة. |
| [add(InputStream stream)](#add-java.io.InputStream) | أضف الـ InputStream الذي يحتوي على الصورة للتعرف / المعالجة. |
| [add(InputStream stream, int startPage, int pagesCount)](#add-java.io.InputStream-int-int) | أضف الـ InputStream الذي يحتوي على صورة متعددة الصفحات للتعرف / المعالجة. |
| [add(String fullPath)](#add-java.lang.String) | أضف المسار أو URI الذي يحتوي على الصورة للتعرف / المعالجة. |
| [add(String fullPath, int startPage, int pagesCount)](#add-java.lang.String-int-int) | أضف الصور / المستندات متعددة الصفحات للتعرف / المعالجة. |
| [addBase64(String base64)](#addBase64-java.lang.String) | أضف سلسلة base64 التي تحتوي على الصورة للتعرف / المعالجة. |
| [clear()](#clear) | اضبط عدد العناصر للمعالجة / التعرف إلى 0. |
| [clearFilters()](#clearFilters) | إزالة جميع الفلاتر. |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [get(int index)](#get-int) | يعيد معلومات حول الصورة المعالجة / المعترف بها. |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [iterator()](#iterator) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [replaceFilters(PreprocessingFilter filters)](#replaceFilters-com.aspose.ocr.PreprocessingFilter) | إزالة الفلاتر القديمة وتعيين جديدة. |
| [size()](#size) | عدد العناصر للمعالجة / التعرف. |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OcrInput(InputType type, PreprocessingFilter filters) {#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter}
```
public OcrInput(InputType type, PreprocessingFilter filters)
```


المُنشئ لإنشاء حاوية وتعيين نوع الصور / المستندات والفلاتر للمعالجة / التعرف اللاحقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) | تحديد نوع الصور/المستندات التي ستُضاف إلى الحاوية. |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | تحديد فلاتر المعالجة التي ستُطبق للمعالجة أو التعرف اللاحق. |

### OcrInput(InputType type) {#OcrInput-com.aspose.ocr.InputType}
```
public OcrInput(InputType type)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) |  |

### add(int[] pixels, int width, int height, int bitsPerPixel) {#add-int---int-int-int}
```
public void add(int[] pixels, int width, int height, int bitsPerPixel)
```


إضافة الصورة المفككة إلى القائمة للتعرف / المعالجة. يجب أن يتطابق نوع الصورة مع النوع المحدد في المُنشئ (SingleImage).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسلات | int[] | تم تمثيل البكسلات كقيم صحيحة 32-بت (rgb). |
| العرض | int | عرض الصورة. |
| الارتفاع | int | ارتفاع الصورة. |
| bitsPerPixel | int | يدعم 1-32 بت. |

### add(BufferedImage image) {#add-java.awt.image.BufferedImage}
```
public void add(BufferedImage image)
```


إضافة BufferedImage التي تحتوي على الصورة للتعرف / المعالجة. يجب أن يتطابق نوع الصورة مع النوع المحدد في المُنشئ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | java.awt.image.BufferedImage | BufferedImage التي تحتوي على الصورة أو المستند. |

### add(BufferedImage image, int startPage, int pagesCount) {#add-java.awt.image.BufferedImage-int-int}
```
public void add(BufferedImage image, int startPage, int pagesCount)
```


إضافة BufferedImage التي تحتوي على الصورة متعددة الصفحات للتعرف / المعالجة. يجب أن يتطابق نوع الصورة مع النوع المحدد في المُنشئ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | java.awt.image.BufferedImage | BufferedImage التي تحتوي على المستند متعدد الصفحات. |
| startPage | int | الصفحة/الصورة الأولى للمعالجة / التعرف. تُستخدم للمستندات. |
| pagesCount | int | الإجمالي الكلي للصفحات/الصور للمعالجة / التعرف. تُستخدم للمستندات. الافتراضي = الكل. |

### add(InputStream stream) {#add-java.io.InputStream}
```
public void add(InputStream stream)
```


إضافة InputStream التي تحتوي على الصورة للتعرف / المعالجة. يجب أن يتطابق نوع الصورة مع النوع المحدد في المُنشئ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream يحتوي على الصورة أو المستند. |

### add(InputStream stream, int startPage, int pagesCount) {#add-java.io.InputStream-int-int}
```
public void add(InputStream stream, int startPage, int pagesCount)
```


أضف InputStream الذي يحتوي على الصورة متعددة الصفحات للتعرف / المعالجة. يجب أن يتطابق نوع الصورة مع النوع المحدد في المُنشئ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream يحتوي على المستند متعدد الصفحات. |
| startPage | int | الصفحة/الصورة الأولى للمعالجة / التعرف. تُستخدم للمستندات. |
| pagesCount | int | الإجمالي الكلي للصفحات/الصور للمعالجة / التعرف. تُستخدم للمستندات. الافتراضي = الكل. |

### add(String fullPath) {#add-java.lang.String}
```
public void add(String fullPath)
```


أضف المسار أو URI الذي يحتوي على الصورة للتعرف / المعالجة. يجب أن يتطابق نوع الصورة مع النوع المحدد في المُنشئ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath | java.lang.String | المسار إلى الصورة/ المستند / المجلد / الأرشيف. |

### add(String fullPath, int startPage, int pagesCount) {#add-java.lang.String-int-int}
```
public void add(String fullPath, int startPage, int pagesCount)
```


أضف الصور / المستندات متعددة الصفحات للتعرف / المعالجة. يجب أن يتطابق نوع الصورة مع النوع المحدد في المُنشئ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPath | java.lang.String | المسار إلى الصورة/ المستند / المجلد / الأرشيف. |
| startPage | int | الصفحة / الصورة الأولى للمعالجة / التعرف. استخدم للمستندات، zip، المجلدات. |
| pagesCount | int | العدد الإجمالي للصفحات / الصور للمعالجة / التعرف. استخدم للمستندات، zip، المجلدات. الافتراضي = الكل. |

### addBase64(String base64) {#addBase64-java.lang.String}
```
public void addBase64(String base64)
```


أضف سلسلة base64 التي تحتوي على الصورة للتعرف / المعالجة. يجب أن يتطابق نوع الصورة مع النوع المحدد في المُنشئ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| base64 | java.lang.String | سلسلة Base64 بصورة واحدة. |

### clear() {#clear}
```
public void clear()
```


عيّن عدد العناصر للمعالجة / التعرف إلى 0. امسح المجموعة.

### clearFilters() {#clearFilters}
```
public void clearFilters()
```


إزالة جميع الفلاتر.

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int}
```
public ImageData get(int index)
```


يعيد معلومات حول الصورة المعالجة / المعترف بها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | موضع الصورة في القائمة. |

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


إزالة الفلاتر القديمة وتعيين جديدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | سيتم تطبيق مرشحات المعالجة لمزيد من المعالجة أو التعرف. |

### size() {#size}
```
public int size()
```


عدد العناصر للمعالجة / التعرف.

**Returns:**
int - عدد العناصر.
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

