---
title: "ImageProcessing"
second_title: "适用于 Python via .NET 的 Aspose.OCR API 参考"
description: 
type: docs
weight: 120
url: /zh/python-net/aspose.ocr/imageprocessing/
---

## ImageProcessing class

Aspose OCR 库的辅助类。允许对图像进行预处理和保存。

ImageProcessing 类型公开以下成员：
## Methods
| 名称 | 描述 |
| :- | :- |
| save(images, folder_path) | 使用图像处理来提高 OCR 的准确性。<br/>            创建一个过滤器列表，这些过滤器将按您指定的顺序应用于输入图像。<br/>            创建过滤器的示例：<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            您不需要全部使用。仅设置您需要的部分。 |
| render(images) | 使用图像处理来提高 OCR 的准确性。<br/>            创建一个过滤器列表，这些过滤器将按您指定的顺序应用于输入图像。<br/>            示例创建过滤器：<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            您不需要全部使用。仅设置您需要的部分。 |

### 另请参见

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

