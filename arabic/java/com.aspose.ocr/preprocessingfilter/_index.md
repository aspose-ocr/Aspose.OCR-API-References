---
title: "PreprocessingFilter"
second_title: "مرجع Aspose.OCR لـ Java API"
description: "الفئة الأساسية لأوامر معالجة الصور"
type: docs
weight: 24
url: /ar/java/com.aspose.ocr/preprocessingfilter/
---

**Inheritance:**
java.lang.Object
```
public class PreprocessingFilter
```

الفئة الأساسية لأوامر معالجة الصور.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PreprocessingFilter()](#PreprocessingFilter) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [Empty](#Empty) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [AutoDenoising()](#AutoDenoising) | يتيح استخدام شبكة عصبية إضافية لتحسين الصورة - تقليل الضوضاء. |
| [AutoDenoising(Rectangle area)](#AutoDenoising-java.awt.Rectangle) | يتيح استخدام شبكة عصبية إضافية لتحسين جزء من الصورة - تقليل الضوضاء. |
| [AutoDewarping()](#AutoDewarping) | يقوم تلقائيًا بتصحيح التشوهات الهندسية في الصورة. |
| [AutoSkew()](#AutoSkew) | يتيح تصحيح الميلان التلقائي للصورة. |
| [AutoSkew(Rectangle area)](#AutoSkew-java.awt.Rectangle) | يتيح تصحيح الميلان التلقائي لجزء من الصورة. |
| [Binarize()](#Binarize) | يحول الصورة إلى صورة بالأبيض والأسود. |
| [Binarize(Rectangle area)](#Binarize-java.awt.Rectangle) | يحول جزءًا من الصورة إلى صورة بالأبيض والأسود. |
| [BinarizeAndDilate()](#BinarizeAndDilate) | التوسيع يضيف بكسلات إلى حدود الكائنات في الصورة. |
| [BinarizeAndDilate(Rectangle area)](#BinarizeAndDilate-java.awt.Rectangle) | التوسيع يضيف بكسلات إلى حدود الكائنات في جزء من الصورة. |
| [ContrastCorrection()](#ContrastCorrection) | مرشح تصحيح التباين. |
| [ContrastCorrection(Rectangle area)](#ContrastCorrection-java.awt.Rectangle) | مرشح تصحيح التباين لجزء من الصورة. |
| [Invert()](#Invert) | يقلب الألوان تلقائيًا في صورة المستند. |
| [Invert(Rectangle area)](#Invert-java.awt.Rectangle) | يقلب الألوان تلقائيًا في جزء من الصورة. |
| [Median()](#Median) | يقوم مرشح الوسيط بالمرور عبر كل عنصر في الصورة واستبدال كل بكسل بوسيط بكسلاته المجاورة. |
| [Median(Rectangle area)](#Median-java.awt.Rectangle) | يقوم مرشح الوسيط بالمرور عبر كل عنصر من جزء الصورة واستبدال كل بكسل بوسيط بكسلاته المجاورة. |
| [Resize(int width, int height)](#Resize-int-int) | إعادة تحجيم الصورة - تكبير أو تصغير دقة الصورة. |
| [Resize(int width, int height, InterpolationFilterType type)](#Resize-int-int-com.aspose.ocr.InterpolationFilterType) | إعادة تحجيم الصورة - تكبير أو تصغير دقة الصورة. |
| [Rotate(float angle)](#Rotate-float) | تدوير الصورة الأصلية. |
| [Rotate(float angle, Rectangle area)](#Rotate-float-java.awt.Rectangle) | تدوير جزء من الصورة. |
| [Scale(float ratio)](#Scale-float) | إعادة تحجيم الصورة - تكبير أو تصغير دقة الصورة. |
| [Scale(float ratio, InterpolationFilterType type)](#Scale-float-com.aspose.ocr.InterpolationFilterType) | إعادة تحجيم الصورة - تكبير أو تصغير دقة الصورة. |
| [Threshold(int value)](#Threshold-int) | إنشاء صورة ثنائية بناءً على تعيين قيمة عتبة لشدة بكسل الصورة الأصلية. |
| [Threshold(int value, Rectangle area)](#Threshold-int-java.awt.Rectangle) | إنشاء جزء من صورة ثنائية بناءً على تعيين قيمة عتبة لشدة بكسل جزء الصورة الأصلية. |
| [ToGrayscale()](#ToGrayscale) | تحويل الصورة إلى صورة بتدرج الرمادي. |
| [add(PreprocessingFilter filter)](#add-com.aspose.ocr.PreprocessingFilter) | إضافة المرشح الجديد إلى المجموعة لتشغيل جميع العمليات لاحقًا. |
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


يتيح استخدام شبكة عصبية إضافية لتحسين الصورة - تقليل الضوضاء. مفيد للصور التي تحتوي على عيوب المسح، تشوهات، بقع، توهجات، تدرجات، عناصر غريبة.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDenoising(Rectangle area) {#AutoDenoising-java.awt.Rectangle}
```
public static PreprocessingFilter AutoDenoising(Rectangle area)
```


يتيح استخدام شبكة عصبية إضافية لتحسين جزء من الصورة - تقليل الضوضاء. مفيد للصور التي تحتوي على عيوب المسح، تشوهات، بقع، توهجات، تدرجات، عناصر غريبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| منطقة | java.awt.Rectangle | مستطيل للمعالجة المسبقة. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDewarping() {#AutoDewarping}
```
public static PreprocessingFilter AutoDewarping()
```


يقوم تلقائيًا بتصحيح التشوهات الهندسية في الصورة. يتطلب موارد عالية جدًا!

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDewarpingFilter object.
### AutoSkew() {#AutoSkew}
```
public static PreprocessingFilter AutoSkew()
```


يتيح تصحيح الميلان التلقائي للصورة.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### AutoSkew(Rectangle area) {#AutoSkew-java.awt.Rectangle}
```
public static PreprocessingFilter AutoSkew(Rectangle area)
```


يتيح تصحيح الميلان التلقائي لجزء من الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| منطقة | java.awt.Rectangle | مستطيل للمعالجة المسبقة. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### Binarize() {#Binarize}
```
public static PreprocessingFilter Binarize()
```


تحويل الصورة إلى صورة بالأبيض والأسود. الصور الثنائية هي صور يكون لبكسلاتها قيمتان محتملتان فقط للشدة. عادةً ما تُعرض باللونين الأسود والأبيض. عدديًا، تكون القيمتان غالبًا 0 للون الأسود و255 للون الأبيض. تُنتج الصور الثنائية عن طريق تطبيق عتبة تلقائية على الصورة.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Binarize(Rectangle area) {#Binarize-java.awt.Rectangle}
```
public static PreprocessingFilter Binarize(Rectangle area)
```


تحويل جزء من الصورة إلى صورة بالأبيض والأسود. الصور الثنائية هي صور يكون لبكسلاتها قيمتان محتملتان فقط للشدة. عادةً ما تُعرض باللونين الأسود والأبيض. عدديًا، تكون القيمتان غالبًا 0 للون الأسود و255 للون الأبيض. تُنتج الصور الثنائية عن طريق تطبيق عتبة تلقائية على الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| منطقة | java.awt.Rectangle | مستطيل للمعالجة المسبقة. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### BinarizeAndDilate() {#BinarizeAndDilate}
```
public static PreprocessingFilter BinarizeAndDilate()
```


التوسيع يضيف بكسلات إلى حدود الكائنات في الصورة.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### BinarizeAndDilate(Rectangle area) {#BinarizeAndDilate-java.awt.Rectangle}
```
public static PreprocessingFilter BinarizeAndDilate(Rectangle area)
```


التوسيع يضيف بكسلات إلى حدود الكائنات في جزء من الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| منطقة | java.awt.Rectangle | مستطيل للمعالجة المسبقة. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### ContrastCorrection() {#ContrastCorrection}
```
public static PreprocessingFilter ContrastCorrection()
```


مرشح تصحيح التباين.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### ContrastCorrection(Rectangle area) {#ContrastCorrection-java.awt.Rectangle}
```
public static PreprocessingFilter ContrastCorrection(Rectangle area)
```


مرشح تصحيح التباين لجزء من الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| منطقة | java.awt.Rectangle | مستطيل للمعالجة المسبقة. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### Invert() {#Invert}
```
public static PreprocessingFilter Invert()
```


يقلب الألوان تلقائيًا في صورة المستند.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Invert(Rectangle area) {#Invert-java.awt.Rectangle}
```
public static PreprocessingFilter Invert(Rectangle area)
```


يقلب الألوان تلقائيًا في جزء من الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| منطقة | java.awt.Rectangle | مستطيل للمعالجة المسبقة. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Median() {#Median}
```
public static PreprocessingFilter Median()
```


يقوم مرشح الوسيط بالمرور عبر كل عنصر في الصورة واستبدال كل بكسل بوسيط بكسلاته المجاورة.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Median(Rectangle area) {#Median-java.awt.Rectangle}
```
public static PreprocessingFilter Median(Rectangle area)
```


يقوم مرشح الوسيط بالمرور عبر كل عنصر من جزء الصورة واستبدال كل بكسل بوسيط بكسلاته المجاورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| منطقة | java.awt.Rectangle | مستطيل للمعالجة المسبقة. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Resize(int width, int height) {#Resize-int-int}
```
public static PreprocessingFilter Resize(int width, int height)
```


إعادة تحجيم الصورة - تكبير أو تصغير دقة الصورة. InterpolationFilterType = bilinear أو أقرب جار @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | العرض الجديد للصورة. |
| الارتفاع | int | الارتفاع الجديد للصورة. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Resize(int width, int height, InterpolationFilterType type) {#Resize-int-int-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Resize(int width, int height, InterpolationFilterType type)
```


إعادة تحجيم الصورة - تكبير أو تصغير دقة الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | العرض الجديد للصورة. |
| الارتفاع | int | الارتفاع الجديد للصورة. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Rotate(float angle) {#Rotate-float}
```
public static PreprocessingFilter Rotate(float angle)
```


تدوير الصورة الأصلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران. القيمة من -360 إلى 360. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Rotate(float angle, Rectangle area) {#Rotate-float-java.awt.Rectangle}
```
public static PreprocessingFilter Rotate(float angle, Rectangle area)
```


تدوير جزء من الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران. القيمة من -360 إلى 360. |
| منطقة | java.awt.Rectangle | مستطيل للمعالجة المسبقة. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Scale(float ratio) {#Scale-float}
```
public static PreprocessingFilter Scale(float ratio)
```


إعادة تحجيم الصورة - تكبير أو تصغير دقة الصورة. InterpolationFilterType الافتراضي ثنائي الخط أو أقرب جار @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نسبة | float | عامل التحجيم. القيمة الموصى بها من 0.1 إلى 1 للتقليل. من 1 إلى 10 للتكبير. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Scale(float ratio, InterpolationFilterType type) {#Scale-float-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Scale(float ratio, InterpolationFilterType type)
```


إعادة تحجيم الصورة - تكبير أو تصغير دقة الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نسبة | float | عامل التحجيم. القيمة الموصى بها من 0.1 إلى 1 للتقليل. من 1 إلى 10 للتكبير. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Threshold(int value) {#Threshold-int}
```
public static PreprocessingFilter Threshold(int value)
```


إنشاء صورة ثنائية بناءً على تعيين قيمة عتبة لشدة بكسل الصورة الأصلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int | القيمة القصوى. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Threshold(int value, Rectangle area) {#Threshold-int-java.awt.Rectangle}
```
public static PreprocessingFilter Threshold(int value, Rectangle area)
```


إنشاء جزء من صورة ثنائية بناءً على تعيين قيمة عتبة لشدة بكسل جزء الصورة الأصلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int | القيمة القصوى. |
| منطقة | java.awt.Rectangle | مستطيل للمعالجة المسبقة. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### ToGrayscale() {#ToGrayscale}
```
public static PreprocessingFilter ToGrayscale()
```


يقوم بتحويل الصورة إلى صورة رمادية. الصورة الرمادية تحتوي على 256 مستوى إضاءة في الصورة (0 إلى 255).

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - GrayscaleFilter object.
### add(PreprocessingFilter filter) {#add-com.aspose.ocr.PreprocessingFilter}
```
public void add(PreprocessingFilter filter)
```


أضف الفلتر الجديد إلى المجموعة لتشغيل جميع العمليات لاحقًا. التناسق في المجموعة مهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filter | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | عملية جديدة لإضافتها إلى قائمة الفلاتر. |

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

