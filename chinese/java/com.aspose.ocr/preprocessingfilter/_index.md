---
title: "PreprocessingFilter"
second_title: "Aspose.OCR for Java API 参考"
description: "图像处理命令的基类"
type: docs
weight: 24
url: /zh/java/com.aspose.ocr/preprocessingfilter/
---

**Inheritance:**
java.lang.Object
```
public class PreprocessingFilter
```

图像处理命令的基类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PreprocessingFilter()](#PreprocessingFilter) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [Empty](#Empty) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [AutoDenoising()](#AutoDenoising) | 启用额外神经网络以改进图像——降低噪声。 |
| [AutoDenoising(Rectangle area)](#AutoDenoising-java.awt.Rectangle) | 启用额外神经网络以改进图像的部分——降低噪声。 |
| [AutoDewarping()](#AutoDewarping) | 自动校正图像中的几何畸变。 |
| [AutoSkew()](#AutoSkew) | 启用自动图像倾斜校正。 |
| [AutoSkew(Rectangle area)](#AutoSkew-java.awt.Rectangle) | 启用自动图像部分倾斜校正。 |
| [Binarize()](#Binarize) | 将图像转换为黑白图像。 |
| [Binarize(Rectangle area)](#Binarize-java.awt.Rectangle) | 将图像的部分转换为黑白图像。 |
| [BinarizeAndDilate()](#BinarizeAndDilate) | 膨胀在图像中为对象的边界添加像素。 |
| [BinarizeAndDilate(Rectangle area)](#BinarizeAndDilate-java.awt.Rectangle) | 膨胀在图像的部分为对象的边界添加像素。 |
| [ContrastCorrection()](#ContrastCorrection) | 对比度校正滤镜。 |
| [ContrastCorrection(Rectangle area)](#ContrastCorrection-java.awt.Rectangle) | 图像部分的对比度校正滤镜。 |
| [Invert()](#Invert) | 自动反转文档图像的颜色。 |
| [Invert(Rectangle area)](#Invert-java.awt.Rectangle) | 自动反转图像部分的颜色。 |
| [Median()](#Median) | 中值滤波器遍历图像的每个元素，并用相邻像素的中值替换每个像素。 |
| [Median(Rectangle area)](#Median-java.awt.Rectangle) | 中值滤波器遍历图像部分的每个元素，并用相邻像素的中值替换每个像素。 |
| [Resize(int width, int height)](#Resize-int-int) | 重新缩放图像 - 放大或缩小图像分辨率。 |
| [Resize(int width, int height, InterpolationFilterType type)](#Resize-int-int-com.aspose.ocr.InterpolationFilterType) | 重新缩放图像 - 放大或缩小图像分辨率。 |
| [Rotate(float angle)](#Rotate-float) | 旋转原始图像。 |
| [Rotate(float angle, Rectangle area)](#Rotate-float-java.awt.Rectangle) | 旋转图像的部分。 |
| [Scale(float ratio)](#Scale-float) | 重新缩放图像 - 放大或缩小图像分辨率。 |
| [Scale(float ratio, InterpolationFilterType type)](#Scale-float-com.aspose.ocr.InterpolationFilterType) | 重新缩放图像 - 放大或缩小图像分辨率。 |
| [Threshold(int value)](#Threshold-int) | 基于对原始图像像素强度设置阈值来创建二值图像。 |
| [Threshold(int value, Rectangle area)](#Threshold-int-java.awt.Rectangle) | 基于对原始图像部分像素强度设置阈值来创建二值图像部分。 |
| [ToGrayscale()](#ToGrayscale) | 将图像转换为灰度图像。 |
| [add(PreprocessingFilter filter)](#add-com.aspose.ocr.PreprocessingFilter) | 将新过滤器添加到集合中，以进一步运行所有操作。 |
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


启用额外神经网络以改进图像——降低噪声。适用于带有扫描伪影、失真、斑点、耀斑、渐变和外来元素的图像。

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDenoising(Rectangle area) {#AutoDenoising-java.awt.Rectangle}
```
public static PreprocessingFilter AutoDenoising(Rectangle area)
```


启用额外神经网络以改进图像的部分——降低噪声。适用于带有扫描伪影、失真、斑点、耀斑、渐变和外来元素的图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 区域 | java.awt.Rectangle | 用于预处理的 Rectangle。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDewarping() {#AutoDewarping}
```
public static PreprocessingFilter AutoDewarping()
```


自动校正图像中的几何畸变。极度占用资源！

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDewarpingFilter object.
### AutoSkew() {#AutoSkew}
```
public static PreprocessingFilter AutoSkew()
```


启用自动图像倾斜校正。

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### AutoSkew(Rectangle area) {#AutoSkew-java.awt.Rectangle}
```
public static PreprocessingFilter AutoSkew(Rectangle area)
```


启用自动图像部分倾斜校正。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 区域 | java.awt.Rectangle | 用于预处理的 Rectangle。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### Binarize() {#Binarize}
```
public static PreprocessingFilter Binarize()
```


将图像转换为黑白图像。二值图像是像素仅具有两种可能强度值的图像。它们通常显示为黑白。数值上，这两个值通常为黑色的 0 和白色的 255。二值图像是通过对图像进行自动阈值处理生成的。

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Binarize(Rectangle area) {#Binarize-java.awt.Rectangle}
```
public static PreprocessingFilter Binarize(Rectangle area)
```


将图像的部分转换为黑白图像。二值图像是像素仅具有两种可能强度值的图像。它们通常显示为黑白。数值上，这两个值通常为黑色的 0 和白色的 255。二值图像是通过对图像进行自动阈值处理生成的。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 区域 | java.awt.Rectangle | 用于预处理的 Rectangle。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### BinarizeAndDilate() {#BinarizeAndDilate}
```
public static PreprocessingFilter BinarizeAndDilate()
```


膨胀在图像中为对象的边界添加像素。

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### BinarizeAndDilate(Rectangle area) {#BinarizeAndDilate-java.awt.Rectangle}
```
public static PreprocessingFilter BinarizeAndDilate(Rectangle area)
```


膨胀在图像的部分为对象的边界添加像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 区域 | java.awt.Rectangle | 用于预处理的 Rectangle。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### ContrastCorrection() {#ContrastCorrection}
```
public static PreprocessingFilter ContrastCorrection()
```


对比度校正滤镜。

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### ContrastCorrection(Rectangle area) {#ContrastCorrection-java.awt.Rectangle}
```
public static PreprocessingFilter ContrastCorrection(Rectangle area)
```


图像部分的对比度校正滤镜。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 区域 | java.awt.Rectangle | 用于预处理的 Rectangle。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### Invert() {#Invert}
```
public static PreprocessingFilter Invert()
```


自动反转文档图像的颜色。

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Invert(Rectangle area) {#Invert-java.awt.Rectangle}
```
public static PreprocessingFilter Invert(Rectangle area)
```


自动反转图像部分的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 区域 | java.awt.Rectangle | 用于预处理的 Rectangle。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Median() {#Median}
```
public static PreprocessingFilter Median()
```


中值滤波器遍历图像的每个元素，并用相邻像素的中值替换每个像素。

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Median(Rectangle area) {#Median-java.awt.Rectangle}
```
public static PreprocessingFilter Median(Rectangle area)
```


中值滤波器遍历图像部分的每个元素，并用相邻像素的中值替换每个像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 区域 | java.awt.Rectangle | 用于预处理的 Rectangle。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Resize(int width, int height) {#Resize-int-int}
```
public static PreprocessingFilter Resize(int width, int height)
```


重新缩放图像 - 放大或缩小图像分辨率。InterpolationFilterType = 双线性或最近邻 @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 图像的新宽度。 |
| 高度 | int | 图像的新高度。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Resize(int width, int height, InterpolationFilterType type) {#Resize-int-int-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Resize(int width, int height, InterpolationFilterType type)
```


重新缩放图像 - 放大或缩小图像分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 图像的新宽度。 |
| 高度 | int | 图像的新高度。 |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Rotate(float angle) {#Rotate-float}
```
public static PreprocessingFilter Rotate(float angle)
```


旋转原始图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | float | 旋转角度。取值范围为 -360 到 360。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Rotate(float angle, Rectangle area) {#Rotate-float-java.awt.Rectangle}
```
public static PreprocessingFilter Rotate(float angle, Rectangle area)
```


旋转图像的部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | float | 旋转角度。取值范围为 -360 到 360。 |
| 区域 | java.awt.Rectangle | 用于预处理的 Rectangle。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Scale(float ratio) {#Scale-float}
```
public static PreprocessingFilter Scale(float ratio)
```


重新缩放图像 - 放大或缩小图像分辨率。InterpolationFilterType 默认双线性或最近邻 @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 比例 | float | 缩放因子。建议值为 0.1 到 1 用于缩小。1 到 10 用于放大。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Scale(float ratio, InterpolationFilterType type) {#Scale-float-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Scale(float ratio, InterpolationFilterType type)
```


重新缩放图像 - 放大或缩小图像分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 比例 | float | 缩放因子。建议值为 0.1 到 1 用于缩小。1 到 10 用于放大。 |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Threshold(int value) {#Threshold-int}
```
public static PreprocessingFilter Threshold(int value)
```


基于对原始图像像素强度设置阈值来创建二值图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 最大值。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Threshold(int value, Rectangle area) {#Threshold-int-java.awt.Rectangle}
```
public static PreprocessingFilter Threshold(int value, Rectangle area)
```


基于对原始图像部分像素强度设置阈值来创建二值图像部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 最大值。 |
| 区域 | java.awt.Rectangle | 用于预处理的 Rectangle。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### ToGrayscale() {#ToGrayscale}
```
public static PreprocessingFilter ToGrayscale()
```


将图像转换为灰度图像。灰度图像在图像中具有 256 级亮度（0 到 255）。

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - GrayscaleFilter object.
### add(PreprocessingFilter filter) {#add-com.aspose.ocr.PreprocessingFilter}
```
public void add(PreprocessingFilter filter)
```


将新过滤器添加到集合中以进一步运行所有操作。集合的一致性很重要。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filter | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | 要添加到过滤器列表的新操作。 |

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

