---
title: "模型"
second_title: "Aspose.OCR 用于 Python via Java API 参考"
description: 
type: docs
weight: 271
url: /zh/python-java/aspose/models/
---

模块模型
=============

类
-------

`AreasType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   确定模型检测到的区域类型。
在 get_text_areas 中使用，以指示将获得的结果——段落坐标或行坐标。

### 祖先（在 MRO 中）

    * enum.Enum

### 类变量

`LINES`
:   将区域设置为行

`PARAGRAPHS`
:   将区域设置为段落

`WORDS`
:   将区域设置为单词

`DetectAreasMode(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   确定用于区域检测的神经网络类型。
在 RecognitionSettings 中使用，以指定要识别的图像类型。

### 祖先（在 MRO 中）

    * enum.Enum

### 类变量

`COMBINE`
:   检测包含文本的段落，然后使用其他神经网络模型检测段落内部的区域。
更适用于结构复杂的图像。

`CURVED_TEXT`
:   检测线条并识别弯曲图像上的文本。
首选模式用于书籍和杂志页面的照片。

`DOCUMENT`
:   检测段落，使用文档的神经网络模型。
更适用于多列文档、带图片的文档或其他非文本对象的文档。

`NONE`
:   不检测段落。
更适用于没有图片的简单双列文档。

`PHOTO`
:   检测段落，使用用于照片的神经网络模型。
更适用于包含大量图片和其他非文本对象的图像。

`TABLE`
:   检测带有文本的单元格。
首选模式用于具有表格结构的图像。

`TEXT_IN_WILD`
:   一个超强的神经网络，专门用于从低质量图像中提取文字，如街道照片、车牌、护照照片、仪表照片以及背景噪声较大的照片。

`Format(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   将识别结果格式化为文档进行保存。

### 祖先（在 MRO 中）

    * enum.Enum

### 类变量

`DOCX`
:   将结果保存为 Office Open XML Word 处理 ML 文档（无宏）。

`EPUB`
:   将文档保存为 EPUB 文件。

`HTML`
:   将文档保存为 HTML 文件。

`JSON`
:   将结果保存为使用 JavaScript 对象表示法的纯文本。

`PDF`
:   将结果保存为 PDF（Adobe 可移植文档）文件。

`PDF_NO_IMG`
:   将文档保存为不含图像的可搜索 PDF（Adobe 可移植文档）文件。

`RTF`
:   将文档保存为 RTF 文件。

`TEXT`
:   将结果保存为纯文本格式。

`XLSX`
:   将结果保存为 Excel（2007 及以后）工作簿文件。

`XML`
:   将结果保存为 XML 文档。

`ImageData(javaClass)`
:

### 祖先（在 MRO 中）

    * aspose.helper.BaseJavaClass

### 方法

`initParams(self)`
:

`InputType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   用于处理/识别的图像/文档类型。

### 祖先（在 MRO 中）

    * enum.Enum

### 类变量

`BASE64`
:   包含图像的 base64 字符串或指向包含 base64 内容的 .txt 文件的路径。支持 GIF、PNG、JPEG、BMP、TIFF。

`DIRECTORY`
:   目录路径。不支持嵌套压缩包和文件夹。
支持 GIF、PNG、JPEG、BMP、TIFF。
默认处理的图像数量为全部。

`PDF`
:   来自文件或二进制数组的扫描 PDF 文档。

`SINGLE_IMAGE`
:   支持 GIF、PNG、JPEG、BMP、TIFF、JFIF、二进制数组。

`TIFF`
:   来自文件或 InputStream 的多页 TIFF、TIF 文档。

`URL`
:   图像上的链接。支持 GIF、PNG、JPEG、BMP、TIFF。

`ZIP`
:   ZIP 压缩包的完整名称。不支持嵌套压缩包和文件夹。
支持 GIF、PNG、JPEG、BMP、TIFF、JFIF。
默认处理的图像数量为全部。

`Language(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   用于识别的语言模型。

### 祖先（在 MRO 中）

    * enum.Enum

### 类变量

`BEL`
:   白俄罗斯字母表

`BUL`
:   保加利亚字母表

`CHI`
:   中文字母表

`CYRILLIC`
:   多语言（西里尔字母）支持

`CZE`
:   捷克字母表

`DAN`
:   丹麦字母表

`DEU`
:   德语字母表

`DUM`
:   荷兰语字母表

`ENG`
:   英语字母表

`EST`
:   爱沙尼亚语字母表

`FIN`
:   芬兰语字母表

`FRA`
:   法语字母表

`HIN`
:   印地语字母表

`ITA`
:   意大利语字母表

`KAZ`
:   哈萨克语字母表

`LATIN`
:   多语言（拉丁字母）支持

`LAV`
:   拉脱维亚语字母表

`LIT`
:   立陶宛语字母表

`NONE`
:   多语言支持

`NOR`
:   挪威字母表

`POL`
:   波兰字母表

`POR`
:   葡萄牙字母表

`RUM`
:   罗马尼亚字母表

`RUS`
:   俄语字母表

`SLK`
:   斯洛伐克字母表

`SLV`
:   斯洛文尼亚字母表

`SPA`
:   西班牙字母表

`SRP`
:   塞尔维亚字母表

`SRP_HRV`
:   塞尔维亚-克罗地亚字母表

`SWE`
:   瑞典字母表

`UKR`
:   乌克兰字母表

`ModelsConverter()`
:

### 方法

`convertInputTypeToJava(jType)`
:

`convertToJavaAreasMode(jType)`
:

`convertToJavaAreasType(jType)`
:

`convertToJavaFormat(jType)`
:

`convertToJavaLanguage(jType)`
:

`convertToJavaSpellCheckLanguage(jType)`
:

`OcrInput(type: models.InputType, filters: models.PreprocessingFilter = None)`
:   用于收集图像的主类。
    
构造函数用于创建容器并设置图像/文档的类型以及用于后续处理/识别的过滤器。
@param type: 设置将添加到容器的图像/文档类型。
@param filters: 设置将用于后续处理或识别的处理过滤器。

### 方法

`add(self, fullPath: str, startPage: int = None, pagesNumber: int = None)`
:   添加包含图像的路径或 URI 以进行识别/处理。
图像的类型必须与构造函数中指定的类型相对应。
@param fullPath: 图像/文档/文件夹/归档的路径。
@param startPage: 用于处理/识别的第一页/图像。用于文档、zip、文件夹。
@param pagesNumber: 用于处理/识别的页面/图像的总数量。用于文档、zip、文件夹。默认 = 全部。

`addStream(self, image_data_binary, startPage: int = None, pagesNumber: int = None)`
:   添加包含图像的 InputStream 以进行识别/处理。
图像的类型必须与构造函数中指定的类型相对应。
        
\code
input = OcrInput(InputType.SINGLE_IMAGE)
file = open(imgPath, "rb")
image_data_binary = file.read()
file.close()
input.addStream(image_data_binary)
result = api.recognize(input, RecognitionSettings())
\endcode
        
@param image_data_binary: 包含图像或文档的二进制数据。
@param startPage: 用于处理/识别的第一页/图像。用于文档、zip、文件夹。
@param pagesNumber: 用于处理/识别的页面/图像的总数量。用于文档、zip、文件夹。默认 = 全部。

`add_base64(self, base64: str)`
:   添加包含图像的 base64 字符串用于识别/处理。
图像的类型必须与构造函数中指定的类型相对应。
@param base64: 单图像的 Base64 字符串。

`clear(self)`
:   将用于处理/识别的项目数量设置为 0。
清除集合。

`clear_filters(self)`
:   移除所有过滤器。

`get(self, index: int) ‑> models.ImageData`
:   返回已处理/已识别图像的信息。
@param index: 图像在列表中的位置。
@return: ImageData 对象。

`getJavaClass(self)`
:

`init(self, javaClass)`
:

`size(self)`
:   用于处理/识别的项目数量。
@return: 项目数量。

`PreprocessingFilter()`
:   图像处理命令的基类。

### 祖先（在 MRO 中）

    * aspose.helper.BaseJavaClass

### 类变量

`JAVA_CLASS_NAME`
:

### 静态方法

`auto_denoising()`
:   启用额外神经网络以改进图像——降低噪声。
适用于带有扫描伪影、失真、斑点、耀斑、渐变、外来元素的图像。
@return: AutoDenoisingFilter 对象。

`auto_dewarping()`
:   自动校正图像中的几何畸变。
资源消耗极大！
@return: AutoDewarpingFilter 对象。

`auto_skew()`
:   启用自动图像倾斜校正。
@return: AutoSkewFilter 对象。

`binarize()`
:   将图像转换为黑白图像。
二值图像是像素仅具有两种可能强度值的图像。
它们通常显示为黑白。数值上，这两个值通常为黑色的0和白色的255。
二值图像是通过对图像进行自动阈值处理生成的。
@return: BinarizeFilter 对象。

`binarize_and_dilate()`
:   膨胀会向图像中对象的边界添加像素。
@return: DilateFilter 对象。

`contrast_correction()`
:   对比度校正滤镜。
@return: ContrastCorrectionFilter 对象。

`invert()`
:   自动反转文档图像中的颜色。
@return: InvertFilter 对象。

`median()`
:   中值滤波器遍历图像的每个元素，并用相邻像素的中值替换每个像素。
@return: MedianFilter 对象。

`resize(width: int, height: int)`
:   重新缩放图像——放大或缩小图像分辨率。
@param width: 图像的新宽度。
@param height: 图像的新高度。
@return: ResizeFilter 对象。

`rotate(angle: float)`
:   旋转原始图像。
@param angle: 旋转角度。值范围为 -360 到 360。
@return: RotateFilter 对象。

`scale(ratio: float)`
:   重新缩放图像 - 放大或缩小图像分辨率。
InterpolationFilterType 双线性或最近邻。
@param ratio: 缩放因子。建议的取值范围：0.1 到 1 用于缩小，1 到 10 用于放大。
@return: ScaleFilter 对象。

`threshold(value: int)`
:   基于对原始图像像素强度设置阈值来创建二值图像。
@param value: 最大值。
@return: BinarizeFilter 对象。

`to_grayscale()`
:   将图像转换为灰度图像。
灰度图像在图像中有 256 级亮度 (0 到 255)。
@return: GrayscaleFilter 对象。

### 方法

`add(self, filter)`
:   将过滤器添加到集合中以进行进一步的预处理。
@param filter: PreprocessingFilter 对象。

`getJavaClass(self)`
:

`SpellCheckError(javaClass)`
:   表示带有附加数据的拼写错误单词。

### 祖先（在 MRO 中）

    * aspose.helper.BaseJavaClass

### 方法

`initParams(self)`
:

`SpellCheckLanguage(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   用于拼写检查校正的字典语言。

### 祖先（在 MRO 中）

    * enum.Enum

### 类变量

`CZE`
:   捷克语字典

`DAN`
:   丹麦语词典

`DEU`
:   德语词典

`DUM`
:   荷兰语词典

`ENG`
:   英语词典

`EST`
:   爱沙尼亚语词典

`FIN`
:   芬兰语词典

`FRA`
:   法语词典

`ITA`
:   意大利语词典

`LAV`
:   拉脱维亚语词典

`LIT`
:   立陶宛语词典

`POL`
:   波兰语词典

`POR`
:   葡萄牙语词典

`RUM`
:   罗马尼亚语词典

`SLK`
:   斯洛伐克语词典

`SLV`
:   斯洛文尼亚语词典

`SPA`
:   西班牙语词典

`SWE`
:   瑞典语词典

`SuggestedWord(javaClass)`
:   来自 get_spell_check_error_list 的拼写建议。

### 祖先（在 MRO 中）

    * aspose.helper.BaseJavaClass

### 方法

`initParams(self)`
:


### 另请参见

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)