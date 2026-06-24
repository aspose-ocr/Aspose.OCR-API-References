---
title: "RecognitionResult"
second_title: "适用于 Python via .NET 的 Aspose.OCR API 参考"
description: 
type: docs
weight: 290
url: /zh/python-net/aspose.ocr/recognitionresult/
---

## RecognitionResult class

图像识别的结果。<br/> 包含带有识别信息的元素以及用于导出结果的方法。

RecognitionResult 类型公开以下成员：


## 属性
| 名称 | 描述 |
| :- | :- |
| recognition_regions_result | 获取包含区域列表（矩形）的识别结果列表。 |
| recognition_lines_result | 获取包含行（矩形）列表的识别结果列表。 |
| recognition_characters_list | 一组由识别算法找到的字符，按概率降序排列。 |
| recognition_text | 获取单个字符串形式的识别结果。 |
| file_name | 文件的完整路径。 |
| warnings | 获取警告消息列表，描述生成过程中出现的非关键错误。 |
| serializable_image |  |
## Methods
| 名称 | 描述 |
| :- | :- |
| save(full_file_name, save_format, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) | 将文档保存为纯文本、PDF 或 Microsoft Word 文档。 |
| save(full_file_name, save_format, embedded_font_path, optimize_pdf) | 将文档保存为纯文本、PDF 或 Microsoft Word 文档。 |
| save(full_file_name, save_format, optimize_pdf) | 将文档保存为纯文本、PDF 或 Microsoft Word 文档。 |
| save(stream, save_format, optimize_pdf) | 将文档保存为纯文本、PDF 或 Microsoft Word 文档。 |
| save(stream, save_format, apply_spelling_correction, language, dictionary_path) | 将文档保存为纯文本、PDF 或 Microsoft Word 文档。 |
| get_spell_check_corrected_text(language, dictionary_path) | 纠正文本（替换拼写错误的单词）。 |
| get_spell_check_error_list(language, dictionary_path) | 查找给定输入文本中拼写错误的单词，并提供建议的拼写。 |
| get_json(is_readable) | 生成包含识别结果的 JSON 字符串。 |
| get_xml() | 生成包含识别结果的 XML 字符串。 |
| get_keywords() | 从护照获取关键字（测试模式。仅适用于美国和马达加斯加护照）。 |

### 另请参见

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

