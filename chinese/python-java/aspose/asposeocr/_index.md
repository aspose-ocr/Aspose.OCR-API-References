---
title: "AsposeOcr"
second_title: "Aspose.OCR 用于 Python via Java API 参考"
description: 
type: docs
weight: 11
url: /zh/python-java/aspose/asposeocr/
---


模块 asposeocr
================
Python 接口用于 Aspose OCR

**Aspose.OCR for Python via .Java** is a powerful,
而轻松易用的光学字符识别 (OCR)
用于您的 Python 应用程序和笔记本的引擎。
在不到 **10** 行代码的情况下，您可以识别
基于拉丁文、斯拉夫文的 **28** 种语言的文本，
以及亚洲文字，返回最流行的
文档和数据交换格式。
无需学习复杂的数学模型，
构建机器学习算法并训练神经
网络——我们简单且强大的 API 将为您完成所有工作。

类
-------

`AsposeOcr()`
:
AsposeOcr 识别的主类。
    
此示例展示了如何识别图像。
\code
api = AsposeOcr()
input = OcrInput(InputType.SINGLE_IMAGE)
input.add(os.path.join(self.dataDir, "SpanishOCR.bmp"))
result = api.recognize(input)
\endcode

### 静态方法

`save_multipage_document(fullFileName: str, saveFormat: aspose.models.Format, results: List)`
:
允许从 RecognitionResult 对象列表获取多页文档。
@param fullFileName: 用于在选定格式中保存识别结果的带路径的文件名。
@param saveFormat: 文档格式（Docx、Txt、Pdf、Xlsx、Xml、Json）。
@param results:

### 方法

`calculate_skew(self, input: aspose.models.OcrInput) -> List[aspose.recognitionresult.SkewOutput]`
:
计算图像的倾斜角度。
支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、二进制数组、文件夹、数组、ZIP 压缩包、URL、Base64。
@param input: :py:any:`~aspose.models.OcrInput`. 实例。包含来源的容器。
@return: 以度为单位的倾斜角度列表 - SkewOutput。

`compare_image_texts(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) -> bool`
:
检查两个图像是否包含相同的文本。
@param fullPath1: 第一个图像的路径。
@param fullPath2: 第二个图像的路径。
@param settings: 识别设置。
@param ignoreCase: True - 表示不区分大小写的搜索。
@return: 如果图像的文本相同（相似度 90%），返回 True。

`correct_spelling(self, text: str, language: aspose.models.SpellCheckLanguage) -> str`
:
纠正文本（替换拼写错误的单词）。
@param text: 待纠正的文本。
@param language: 用于 SpellCheckLanguage 的字典。
@return: 替换单词后的文本。

`detect_rectangles(self, input: aspose.models.OcrInput, areasType: aspose.models.AreasType, isDetectAreas: bool) -> List[aspose.recognitionresult.RectangleOutput]`
:
检测图像上的文本区域。
支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、二进制数组、文件夹、数组、ZIP 压缩包、URL、Base64。
@param input: :py:any:`~aspose.models.OcrInput`. 实例。
@param areasType: 确定返回哪些矩形 - 行、段落或单词。
@param isDetectAreas: 启用自动文本区域检测。
@return: 包含检测到的文本区域或行的 RectangleOutput 列表。

`image_has_text(self, fullPath: str, text: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) -> bool`
:
检查图像是否包含提供的文本片段。
@param fullPath: 图像的路径。
@param text: 用于在图像上搜索的文本片段。
@param settings: 识别设置。
@param ignoreCase: True - 表示不区分大小写的搜索。
@return: 如果图像包含文本片段则返回 True；否则返回 False（图像不包含文本片段）。

`image_text_diff(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> float`
:
比较两幅图像上的文本，并返回一个表示相似度的数值（0 到 1）。
@param fullPath1: 第一个图像的路径。
@param fullPath2: 第二个图像的路径。
@param settings: 识别设置。
@param ignoreCase: True - 表示不区分大小写的搜索。
@return: 0 表示文本完全不同；1 表示文本完全相同。

`recognize(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
识别图像，并可指定 RecognitionSettings。
支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、二进制数组、文件夹、数组、ZIP 压缩包、URL、Base64。
@param input: :py:any:`~aspose.models.OcrInput`. 实例。
@param settings: RecognitionSettings 对象。
@return: 包含图像识别结果的 RecognitionResult 列表。

`recognize_car_plate(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.CarPlateRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
识别车牌，并可指定 CarPlateRecognitionSettings。
支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、二进制数组、文件夹、数组、ZIP 压缩包、URL、Base64。
@param input: :py:any:`~aspose.models.OcrInput`. 实例。
@param settings: CarPlateRecognitionSettings
@return: 包含图像识别结果的 RecognitionResult 列表。

`recognize_fast(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
识别高质量图像上的文本。未使用自动图像倾斜校正和文本区域
检测。
支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、二进制数组、文件夹、数组、ZIP 压缩包、URL、Base64。
@param input: :py:any:`~aspose.models.OcrInput`. 实例。
@return: 包含图像识别结果的 RecognitionResult 列表。

`recognize_id_card(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.IDCardRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
识别身份证，并可指定 IDCardRecognitionSettings。
支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、二进制数组、文件夹、数组、ZIP 压缩包、URL、Base64。
@param input: :py:any:`~aspose.models.OcrInput`. 实例。
@param settings: IDCardRecognitionSettings
@return: 包含图像识别结果的 RecognitionResult 列表。

`recognize_invoice(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.InvoiceRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
识别发票，并可指定 InvoiceRecognitionSettings。
支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、二进制数组、文件夹、数组、ZIP 压缩包、URL、Base64。
@param input: :py:any:`~aspose.models.OcrInput`. 实例。
@param settings: InvoiceRecognitionSettings
@return: 包含图像识别结果的 RecognitionResult 列表。

`recognize_lines(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
识别单行图像，并可指定 RecognitionSettings。
@param input: :py:any:`~aspose.models.OcrInput`. 实例。
@param settings: RecognitionSettings 对象。
@return: 包含图像识别结果的 RecognitionResult 列表。

`recognize_passport(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.PassportRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
识别护照，并且可以指定 PassportRecognitionSettings。
支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、二进制数组、文件夹、数组、ZIP 压缩包、URL、Base64。
@param input: :py:any:`~aspose.models.OcrInput`. 实例。
@param settings: PassportRecognitionSettings
@return: 包含图像识别结果的 RecognitionResult 列表。

`recognize_receipt(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.ReceiptRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
识别收据，并且可以指定 ReceiptRecognitionSettings。
支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、二进制数组、文件夹、数组、ZIP 压缩包、URL、Base64。
@param input: :py:any:`~aspose.models.OcrInput`. 实例。
@param settings: ReceiptRecognitionSettings
@return: 包含图像识别结果的 RecognitionResult 列表。

`recognize_street_photo(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
识别街景照片中的文本。
从街景照片、交通摄像头图像、身份证、驾驶执照以及其他文本稀疏且背景嘈杂/彩色的图像中提取文本。
支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、二进制数组、文件夹、数组、ZIP 压缩包、URL、Base64。
@param input: :py:any:`~aspose.models.OcrInput`. 实例。
@return: 包含图像识别结果的 RecognitionResult 列表。

`shutdown(self)`
:
关闭 JVM 机器。

`ImageProcessing()`
:
Aspose OCR 库的辅助类。允许对图像进行预处理并保存。

### 静态方法

`save(images, folderPath)`
:
使用图像处理来提高 OCR 的准确性。
创建一个过滤器列表，这些过滤器将按照您指定的顺序应用于输入图像。
\code
filters = new PreprocessingFilter();
filters.add(PreprocessingFilter.auto_dewarping());
filters.add(PreprocessingFilter.invert());
filters.add(PreprocessingFilter.threshold(150));
filters.add(PreprocessingFilter.binarize());
filters.add(PreprocessingFilter.rotate(180));
filters.add(PreprocessingFilter.scale(6));
filters.add(PreprocessingFilter.dilate());
        
images = OcrInput(InputType.PDF, filters);
\endcode
您并不需要全部。仅设置您需要的部分。
@param images: OcrInput 对象，包含不同的图像 OcrInput.
@param folderPath: 用于保存处理后图像的路径，不包含图像名称。
@return: OcrInput 对象，包含处理后图像的结果 OcrInput.


### 另请参见

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)