---
title: "OcrInput"
second_title: "Aspose.OCR 用于 Python via .NET API 参考"
description: 
type: docs
weight: 240
url: /zh/python-net/aspose.ocr/ocrinput/
---

## OcrInput class

用于收集所有图像/文档以进行预处理/识别的容器。

OcrInput 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| OcrInput(type, filters) | 初始化 OcrInput 类的新实例 |
| OcrInput(type) | 初始化 OcrInput 类的新实例 |
## Indexer
| 名称 | 描述 |
| :- | :- |
| [index] | 返回有关已处理/已识别图像的信息。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| add(full_path) | 添加包含用于识别/处理的图像的路径或 URI。<br/>
            图像的类型必须与构造函数中指定的类型相对应。 |
| add(stream) | 添加包含用于识别/处理的图像的内存流。<br/>
            图像的类型必须与构造函数中指定的类型相对应。 |
| add(full_path, start_page, pages_count) | 添加用于识别/处理的多页图像/文档。<br/>
            图像的类型必须与构造函数中指定的类型相对应。 |
| add(stream, start_page, pages_count) | 添加包含用于识别/处理的多页图像的内存流。<br/>
            图像的类型必须与构造函数中指定的类型相对应。 |
| add(arr, width, height, pixel_format) | 将解码后的图像添加到用于识别/处理的列表中。<br/>            图像的类型必须与构造函数中指定的类型（SingleImage）相对应。 |
| replace_filters(filters) | 移除旧的过滤器并设置新的。 |
| clear_filters() | 移除所有过滤器。 |
| add_base64(base64) | 添加包含图像的 base64 字符串用于识别/处理。<br/>            图像的类型必须与构造函数中指定的类型相对应。 |
| clear() | 移除所有过滤器。 |
| count() | 用于处理/识别的项目数量。 |
| get_input_type() | 允许用于识别的图像类型。 |

### 另请参见

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

