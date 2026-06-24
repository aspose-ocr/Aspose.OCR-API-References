---
title: "DetectAreasMode"
second_title: "适用于 Python via .NET 的 Aspose.OCR API 参考"
description: 
type: docs
weight: 540
url: /zh/python-net/aspose.ocr/detectareasmode/
---

## DetectAreasMode enumeration

确定用于区域检测的神经网络类型。

## Members
| 成员名称 | 描述 |
| :- | :- |
| LEAN | 通过省略对复杂布局的支持来优先考虑速度并降低资源消耗。仅适用于仅包含少量文本行且没有插图或格式的简单图像。 |
| MULTICOLUMN | 检测以列格式排列的大块文本。是书页、文章或合同等多列布局的最佳选择。 |
| UNIVERSAL | 检测图像中的所有文本块，包括照片上稀疏和不规则的文字。是大多数图像的通用选项，除表格和多列布局外。 |
| TABLE | 检测图像中的表格结构并提取各单元格中的文本。推荐用于扫描的电子表格、报告以及其他基于表格的文档。 |
| CURVED_TEXT | 自动校正图像中弯曲的文字行，提高识别准确率并使更多文字得以恢复和提取。需要大量的处理能力和内存。 |
| FORMULA |  |

### 另请参见

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.OCR](/ocr/python-net/)

