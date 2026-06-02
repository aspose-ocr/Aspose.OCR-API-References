---
title: "RecognitionResult"
second_title: "Aspose.OCR 用于 Python 通过 Java API 参考"
description: 
type: docs
weight: 171
url: /zh/python-java/aspose/recognitionresult/
---

模块 recognitionresult
========================

类
-------

`LinesResult(javaClass)`
:

### 祖先 (在 MRO 中)

    * aspose.helper.BaseJavaClass

### 方法

`initParams(self)`
:

`RecognitionResult(javaClass)`
:
图像识别的结果。包含带有识别信息的元素
用于结果导出的信息和方法。

### 静态方法

`save_multipage_document(self, fullPath: str)`
:
私有

### 实例变量

`recognition_areas_text`
:   列表，包含一系列区域（矩形）的识别结果。

`recognition_lines_result`
:   获取包含一系列行（矩形）的识别结果列表。

### 方法

`getJavaClass(self)`
:

`get_json(self)`
:
生成包含识别结果的 JSON 字符串。
@return: 以 JSON 字符串形式返回识别结果。

`get_spell_check_corrected_text(self, language: aspose.models.SpellCheckLanguage) ‑> str`
:
纠正文本（替换拼写错误的单词）。
@param language: 要使用的字典。
@return: 更正后的识别结果字符串。

`get_spell_check_error_list(self, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
查找给定输入文本中拼写错误的单词，并提供建议的拼写。
@param language: 要使用的字典。
@return: SpellCheckError 对象的列表，表示拼写错误的单词以及每个错误单词的建议正确拼写列表，
并附带编辑距离。

`get_xml(self)`
:
生成包含识别结果的 JSON 字符串。
@return: 以 XML 字符串形式返回的识别结果。

`init(self)`
:

`save(self, fullFileName: str, format: aspose.models.Format)`
:
将文档保存为纯文本或其他文档格式。
@param fullFileName: 用于保存识别结果的带路径的文件名。
@param format: Format 的文档格式枚举类型。

`save_spell_check_corrected_text(self, fullFileName: str, format: aspose.models.Format, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
纠正文本（替换拼写错误的单词）。
将更正后的文本以纯文本或其他格式保存到文档中。
@param fullFileName: 用于保存识别结果的带路径的文件名
@param format: Format 的文档格式枚举类型。
@param language: 用于拼写检查的字典。

`use_user_dictionary(self, dictionaryPath: str)`
:
允许使用自定义字典进行拼写检查校正。
@param dictionaryPath: 用户字典（频率字典）的完整路径。
字典文件格式：
UTF-8 编码的纯文本文件。
单词和词频用逗号分隔，单词位于第一列，词频位于第二列。
每个单词‑词频对占一行。行的定义是由字符序列后跟换行符 ("
", 一个回车符 (")
"),
或紧接着回车的换行符(\"

\")
每个单词都应使用小写。
示例:
\code
word,5984819
hello,5761742
down,5582768
\endcode

`RectangleOutput(javaClass)`
:
关于检测到的文本区域或行的数据。
\code
source - 文件或 URL 的完整路径（如果有）。对于流、字节数组、base64 为空。
page - 页码。
image_index - 页面上图像的序列号。
rectangles - 检测到的文本区域或行的列表。
\endcode

### 祖先 (在 MRO 中)

    * aspose.helper.BaseJavaClass

### 方法

`initParams(self)`
:

`SkewOutput(javaClass)`
:
关于倾斜角度（度）和文件名的数据。
\code
source - 文件或 URL 的完整路径（如果有）。对于流、字节数组、base64 为空。
page - 页码。
image_index - 页面上图像的序列号。
angle - 倾斜角度（度）。
\endcode

### 祖先 (在 MRO 中)

    * aspose.helper.BaseJavaClass

### 方法

`initParams(self)`
:


### 另见

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)