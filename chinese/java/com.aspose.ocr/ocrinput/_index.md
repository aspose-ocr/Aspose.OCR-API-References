---
title: "OcrInput"
second_title: "Aspose.OCR for Java API 参考"
description: "用于从图像识别文本的主类"
type: docs
weight: 20
url: /zh/java/com.aspose.ocr/ocrinput/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class OcrInput implements Iterable<ImageData>
```

用于从图像中识别文本的主类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OcrInput(InputType type, PreprocessingFilter filters)](#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter) | 构造函数用于创建容器并设置图像/文档的类型以及后续处理/识别的过滤器。 |
| [OcrInput(InputType type)](#OcrInput-com.aspose.ocr.InputType) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(int[] pixels, int width, int height, int bitsPerPixel)](#add-int---int-int-int) | 将解码后的图像添加到用于识别/处理的列表中。 |
| [add(BufferedImage image)](#add-java.awt.image.BufferedImage) | 添加包含图像的 BufferedImage 以进行识别/处理。 |
| [add(BufferedImage image, int startPage, int pagesCount)](#add-java.awt.image.BufferedImage-int-int) | 添加包含多页图像的 BufferedImage 以进行识别/处理。 |
| [add(InputStream stream)](#add-java.io.InputStream) | 添加包含图像的 InputStream 以进行识别/处理。 |
| [add(InputStream stream, int startPage, int pagesCount)](#add-java.io.InputStream-int-int) | 添加包含多页图像的 InputStream 以进行识别/处理。 |
| [add(String fullPath)](#add-java.lang.String) | 添加包含图像的路径或 URI 以进行识别/处理。 |
| [add(String fullPath, int startPage, int pagesCount)](#add-java.lang.String-int-int) | 添加多页图像/文档以进行识别/处理。 |
| [addBase64(String base64)](#addBase64-java.lang.String) | 添加包含图像的 base64 字符串以进行识别/处理。 |
| [clear()](#clear) | 将处理/识别的项目数量设置为 0。 |
| [clearFilters()](#clearFilters) | 移除所有过滤器。 |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [get(int index)](#get-int) | 返回有关已处理/已识别图像的信息。 |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [iterator()](#iterator) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [replaceFilters(PreprocessingFilter filters)](#replaceFilters-com.aspose.ocr.PreprocessingFilter) | 移除旧过滤器并设置新过滤器。 |
| [size()](#size) | 用于处理/识别的项目数量。 |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OcrInput(InputType type, PreprocessingFilter filters) {#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter}
```
public OcrInput(InputType type, PreprocessingFilter filters)
```


构造函数用于创建容器并设置图像/文档的类型以及后续处理/识别的过滤器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) | 设置将添加到容器的图像/文档类型。 |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | 设置的处理过滤器将用于后续的处理或识别。 |

### OcrInput(InputType type) {#OcrInput-com.aspose.ocr.InputType}
```
public OcrInput(InputType type)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) |  |

### add(int[] pixels, int width, int height, int bitsPerPixel) {#add-int---int-int-int}
```
public void add(int[] pixels, int width, int height, int bitsPerPixel)
```


将解码后的图像添加到用于识别/处理的列表中。图像的类型必须与构造函数中指定的类型（SingleImage）相对应。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | int[] | 像素以 32 位整数值（rgb）表示。 |
| 宽度 | int | 图像宽度。 |
| 高度 | int | 图像高度。 |
| bitsPerPixel | int | 支持 1-32 位。 |

### add(BufferedImage image) {#add-java.awt.image.BufferedImage}
```
public void add(BufferedImage image)
```


添加包含图像的 BufferedImage 以进行识别/处理。图像的类型必须与构造函数中指定的类型相对应。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图像 | java.awt.image.BufferedImage | 包含图像或文档的 BufferedImage。 |

### add(BufferedImage image, int startPage, int pagesCount) {#add-java.awt.image.BufferedImage-int-int}
```
public void add(BufferedImage image, int startPage, int pagesCount)
```


添加包含多页图像的 BufferedImage 以进行识别/处理。图像的类型必须与构造函数中指定的类型相对应。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图像 | java.awt.image.BufferedImage | 包含多页文档的 BufferedImage。 |
| startPage | int | 用于处理/识别的第一页/图像。用于文档。 |
| pagesCount | int | 用于处理/识别的页面/图像的总数量。用于文档。默认 = 全部。 |

### add(InputStream stream) {#add-java.io.InputStream}
```
public void add(InputStream stream)
```


添加包含图像的 InputStream 以进行识别/处理。图像的类型必须与构造函数中指定的类型相对应。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含图像或文档的 InputStream。 |

### add(InputStream stream, int startPage, int pagesCount) {#add-java.io.InputStream-int-int}
```
public void add(InputStream stream, int startPage, int pagesCount)
```


添加包含多页图像的 InputStream 用于识别/处理。图像的类型必须与构造函数中指定的类型相对应。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含多页文档的 InputStream。 |
| startPage | int | 用于处理/识别的第一页/图像。用于文档。 |
| pagesCount | int | 用于处理/识别的页面/图像的总数量。用于文档。默认 = 全部。 |

### add(String fullPath) {#add-java.lang.String}
```
public void add(String fullPath)
```


添加包含图像的路径或 URI 用于识别/处理。图像的类型必须与构造函数中指定的类型相对应。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullPath | java.lang.String | 图像/文档/文件夹/存档的路径。 |

### add(String fullPath, int startPage, int pagesCount) {#add-java.lang.String-int-int}
```
public void add(String fullPath, int startPage, int pagesCount)
```


添加多页图像/文档用于识别/处理。图像的类型必须与构造函数中指定的类型相对应。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullPath | java.lang.String | 图像/文档/文件夹/存档的路径。 |
| startPage | int | 用于处理/识别的第一页/图像。适用于文档、zip、文件夹。 |
| pagesCount | int | 用于处理/识别的页面/图像总数。适用于文档、zip、文件夹。默认 = 全部。 |

### addBase64(String base64) {#addBase64-java.lang.String}
```
public void addBase64(String base64)
```


添加包含图像的 base64 字符串用于识别/处理。图像的类型必须与构造函数中指定的类型相对应。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| base64 | java.lang.String | 包含单个图像的 Base64 字符串。 |

### clear() {#clear}
```
public void clear()
```


将用于处理/识别的项目数量设置为 0。清空集合。

### clearFilters() {#clearFilters}
```
public void clearFilters()
```


移除所有过滤器。

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
### get(int index) {#get-int}
```
public ImageData get(int index)
```


返回有关已处理/已识别图像的信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 图像在列表中的位置。 |

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


移除旧过滤器并设置新过滤器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | 处理过滤器将用于后续的处理或识别。 |

### size() {#size}
```
public int size()
```


用于处理/识别的项目数量。

**Returns:**
int - 项目数量。
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

