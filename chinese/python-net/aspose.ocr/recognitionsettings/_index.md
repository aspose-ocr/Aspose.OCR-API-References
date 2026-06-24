---
title: "RecognitionSettings"
second_title: "适用于 Python via .NET 的 Aspose.OCR API 参考"
description: 
type: docs
weight: 330
url: /zh/python-net/aspose.ocr/recognitionsettings/
---

## RecognitionSettings class

图像识别的设置。<br/>            包含允许自定义识别过程的元素。

RecognitionSettings 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| RecognitionSettings() | 初始化一个新实例 |
| RecognitionSettings(language, recognition_areas, recognize_single_line) | 初始化 RecognitionSettings 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| recognize_vertical_lines |  |
| threads_count | 获取或设置用于处理的线程数量。 |
| language | 获取或设置用于 OCR 的语言。 |
| ignored_symbols | 设置识别符号的黑名单。 |
| allowed_symbols | 使用 alphabet 属性设置允许的字符。 |
| allowed_characters | 允许的字符集。确定识别结果允许的字符类型。 |
| automatic_color_inversion | 检测文字为白色、背景为深色/黑色的图像，并自动为其选择特殊的 OCR 算法。 |
| recognition_areas | 获取或设置用于处理的文本区域列表。 |
| recognize_single_line | 设置单行图像识别。 <br/>            默认情况下为禁用 (false)。 <br/>            禁用所有与拆分为行相关的处理步骤。 <br/>            如果您的图像仅包含一行，请将此参数设为 true。禁用 RecognitionAreas 设置，因此所有区域设置将被忽略。 |
| language_detection_level |  |
| lines_filtration | 允许识别表格中的文本（被线条包围的区域）。 |
| detect_areas_mode | 允许为文档类型区域选择最佳模式：document、photo、plain text、column、image。 |
| upscale_small_font | 允许您使用专门针对小字体识别的额外算法。<br/>            对于包含小尺寸字符的图像非常有用。 |

### 另请参见

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

